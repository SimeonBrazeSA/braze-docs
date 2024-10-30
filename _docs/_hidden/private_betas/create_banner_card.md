---
nav_title: Creating a Banner Card
article_title: Creating a Banner Card
permalink: "/create_banner_card/"
description: "This reference article covers how to create and send Banner Cards using Braze campaigns."
page_type: reference
---

# Creating a Banner Card

> This article covers how to create a Banner Card in Braze when you build campaigns.

Similar to [Content Cards]({{site.baseurl}}/user_guide/message_building_by_channel/content_cards/about), Banner Cards are embedded directly in your app or website so that you can engage users with an experience that feels natural. They’re a quick and seamless solution to create personalized messaging for your users all while extending the reach of other channels (such as email or push notifications). 

Banner Cards are great for:

- Highlighting featured content
- Notifying users about upcoming events
- Sharing updates on loyalty programs

Because Banner Cards personalize each time a user starts a new session and can be configured to never expire, they’re a helpful tool to add to your engagement strategy.

{% alert important %}
Banner Cards are currently in early access. Contact your Braze account manager if you’re interested in participating in this early access.
{% endalert %}

## Prerequisite: determine placement

Before creating a Banner Card, you must designate areas in your app where you want to display the Banner Card. This is also referred to as the placement. Once you create a placement, you can select it when creating your Banner Card campaign. If you already have a placement, skip to [step 1](#step-1-create-your-campaign).

To create a placement:

1. Go to **Settings** > **Banner Card Placements**.
2. Give your Banner Card placement a name.
3. (Optional) Add a description to explain where this Banner Card is intended to be placed.
4. Enter a unique placement ID. Work with your developer team to define this ID, because they will need to use it during the integration. Avoid editing your placement ID after launch, as this can break the integration with your app or website.
5. Select **Save**.

Each placement can be used in up to 10 campaigns. 

{% alert important %}
Placement IDs are unique per workspace.
{% endalert %}

## Step 1: Create your campaign

After determining your Banner Card placement, it’s time to build your campaign.

1. Go to **Messaging** > **Campaigns** and select **Create Campaign**.
2. Select **Banner Card**.
3. Name your campaign something clear and meaningful.
4. Add Teams and Tags as needed. Tags make your campaigns easier to find and build reports out of. For example, when using the Report Builder, you can filter by the relevant tags.
5. Select a [placement](#prerequisite-determine-placement) to associate with your campaign. This is where the Banner Card will appear in your app or site.
6. Add and name as many variants as you like for your campaign. You can choose different message types and layouts for each added variant. For more information on variants, refer to [Multivariate and A/B testing]({{site.baseurl}}/user_guide/engagement_tools/testing/multivariant_testing/).

## Step 2: Compose a Banner Card

To edit the details of your message’s content:

1. Select **Edit message**. The composer will open.
2. Choose a row style that fits your message. Drag and drop a row into the canvas area.
3. Drag and drop blocks into the row to build your message.
4. Define the [style](#styles) of your message.

### Styles

Select **Style** to adjust the settings to apply to all blocks in the message.

![Style panel of the Banner Card composer.]({% image_buster /assets/img/banner_cards/banner_card_styles.png %})

Here, you can provide custom styling such as background properties, border settings, and defaults to your Banner Cards. Styles applied here can be overridden for a specific block or row. To override styles, select the specific block or row to view its properties and make changes.

### On-click behavior

When your customer clicks on a link in the Banner Card, you can either navigate them deeper into your app or redirect them to another webpage.

You can also choose to log a custom attribute or custom event. This will update your customer’s profile with custom data when they click the Banner Card.

## Step 3: Build the remainder of your campaign

Next, build the remainder of your campaign. Refer to the next sections for more details on how to best use our tools to build Banner Cards.

### Choose a campaign duration

Select the start date and time for the Banner Card campaign. 

By default, Banner Cards last indefinitely. If desired, select **End Time** to specify an end date and time.

### Choose users to target

Next, target users by choosing segments or filters to narrow down your audience. You’ll automatically be given a snapshot of what that approximate segment population looks like right now. Keep in mind that exact segment membership is always calculated just before the message is sent.

### Choose conversion events

Braze allows you to track how often users perform specific actions, and conversion events, after receiving a campaign. You can allow up to a 30-day window during which a conversion will be counted if the user takes the specified action.

## Step 4: Test and deploy

After building your campaign, test and review it to make sure your campaign works as expected. Then, you’re ready to launch your Banner Card campaign!

## Things to know

### Banner Cards expiration

By default, Banner Cards do not have an expiration date, but you can add an optional end date.

### Placement management

Placements are unique per workspace. Each placement can be used in up to 10 campaigns.  You can view all campaigns associated with a placement from **Settings** > **Banner Card Placements**. 

Placement IDs must be unique to a workspace, and should not be edited after launch. Work with your developer team to define this ID, because they will need to use it during the integration. 

### Analytics

The following table defines key Banner Card metrics.

| Metric               | Definition                                                                                                                                                       |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Total Impressions**     | Total Impressions is the number of times a Banner Card is loaded and appears on a user’s screen regardless of prior interaction.                               |
| **Unique Impressions**    | _Unique Impressions_ is the total number of users who received and viewed a given message in a day; each user is only counted once.                              |
| **Total Clicks**         | _Total Clicks_ is the total number of clicks within a Banner Card, regardless of whether the same user clicks multiple times.                                     |
| **Unique Clicks**        | _Unique Clicks_ is the distinct number of recipients who have clicked within a Banner Card at least once and is measured by dispatch_id; each user is only counted once. |
| **Primary Conversions**  | Includes both the count and rate of conversions for the [primary conversion event]({{site.baseurl}}/user_guide/engagement_tools/campaigns/building_campaigns/conversion_events/#primary-conversion-event). The primary conversion event is determined when you build the campaign. {::nomarkdown}<ul><li><i>Conversions</i> are the number of times a user performs an event after clicking on the Banner Card. Each user is only counted once.</li><li><i>Conversion Rate</i> is the percentage of times the conversion event occurred compared to all recipients of a message. <br> <i>(Conversions) / (Unique Impressions)</i></li></ul>{:/} |
{: .reset-td-br-1 .reset-td-br-2}

For a full list of metrics, definitions, and calculations, refer to our [Report Metrics Glossary]({{site.baseurl}}/user_guide/data_and_analytics/report_metrics).