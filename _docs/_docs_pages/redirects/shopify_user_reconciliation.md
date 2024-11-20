---
nav_title: Shopify user reconciliation
article_title: Shopify user reconciliation
permalink: "/shopify_user_reconciliation/"
description: "This reference article covers how to reconcile your user’s device ID and personal information when they reach the checkout flow."
hidden: true
---

# Shopify user reconciliation outside the checkout flow 

> The Shopify integration reconciles your user’s device ID and personal information when they reach the checkout flow and perform any Shopify webhook events there.

{% alert note %}
This feature is currently in beta. If you’re interested, contact your customer success manager or account manager.
{% endalert %}

To support user reconciliation via your Shopify sign-up and login flow, we can implement a JavaScript function automatically to your Shopify store outside of the checkout flow. Braze will automatically implement a function wherever we see a form with a `type="email"` on the Shopify store, as in the example below.

![1]{:style="max-width:60%;"}

Once this function is called, the anonymous user on the web becomes associated with the provided email address. Moving forward, any Shopify events that reference any of the identifiers we use (for example, Shopify Customer ID, Email Address, Phone Number) will be assigned to the same Braze user if there is a match.

## Considerations

{% alert important %}
Braze isn't familiar with all the forms containing `type="email"` on a customer's Shopify site. This means there's a possibility the function could miss some input fields that should be utilized for user reconciliation or pick up incorrect fields that would set the wrong email address (for example, Referral form) on the user profile.
{% endalert %}

We encourage you to explore all the forms supported on the Shopify site and assess how this beta solution can cater to your requirements effectively. By opting to utilize this beta feature, you understand there is potentially unexpected behavior from making manual changes to your Shopify forms.

[1]: {% image_buster /assets/img/shopify_type_email.png %}
