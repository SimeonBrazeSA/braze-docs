---
nav_title: "Recipients Object"
article_title: API Recipients Object
page_order: 9
page_type: reference
description: "This reference article explains the different components of the Braze recipients object."

---

# Recipients object

> The recipients object allows you to request or write information in our endpoints.

Either `external_user_id`, `user_alias`, or `email` is required in this object. **Requests must specify only one.**

{% alert important %}
Specifying a recipient by email address is currently in early access. Contact your customer success manager if you're interested in participating in this early access.
{% endalert %}

The recipients object allows you to combine the [user alias object]({{site.baseurl}}/api/objects_filters/user_alias_object/), the [trigger properties object]({{site.baseurl}}/api/objects_filters/trigger_properties_object/), and the [Canvas entry properties object]({{site.baseurl}}/api/objects_filters/canvas_entry_properties_object/).

## Object body

```json
[{
  "user_alias": (optional, User Alias Object) User alias of user to receive message,
  "external_user_id": (optional, string) see External user ID,
  "email": (optional, string) email address of user to receive message,
  "prioritization": (optional, array) see Prioritization; required when using email,
  "trigger_properties": (optional, object) personalization key-value pairs for this user when sending a campaign or message; see Trigger Properties,
  "canvas_entry_properties": (optional, object) personalization key-value pairs for this user when triggering a Canvas; see Canvas Entry Properties
}]
```

- [User aliases]({{site.baseurl}}/user_guide/data_and_analytics/user_data_collection/user_profile_lifecycle/#user-aliases)
- [External user ID]({{site.baseurl}}/api/objects_filters/user_attributes_object/#braze-user-profile-fields)
- [Prioritization]({{site.baseurl}}/api/endpoints/user_data/post_user_identify/#identifying-users-by-email)

## Recipient object deduping

When making an API call with the recipient object, **if there exists a duplicated recipient targeting the same address (that is, email, push), the user will be deduped**, meaning identical users will be removed, leaving one. 

For example, if the same `external_user_id` is used, then only one message will be received. Consider making multiple API calls if you need a workaround for this behavior.

```json
{"campaign_id":"#####","recipients":[
{"external_user_id":"userid1","trigger_properties":{"name":"Beth Test 1"}},
{"external_user_id":"userid1","trigger_properties":{"name":"Beth Test 2"}} 
]}
```