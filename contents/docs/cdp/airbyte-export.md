---
title: Airbyte
installUrl: https://docs.airbyte.com/integrations/sources/posthog/
thumbnail: ../../cdp/thumbnails/airbyte.png
tags:
    - airbyte
---

The Airbyte export sends data from PostHog, to Airbyte. It supports both Full Refresh and Incremental syncs. You can choose if it copies only the new or updated event data, or all rows in the tables and columns you set up for replication, every time a sync is run.

## Requirements

Using the Airbyte export requires either PostHog Cloud with the [data pipeline add-on](https://us.posthog.com/organization/billing), or a self-hosted PostHog instance running [version 1.30.0](https://posthog.com/blog/the-posthog-array-1-30-0) or later.

Not running 1.30.0? Find out [how to update your self-hosted PostHog deployment](https://posthog.com/docs/runbook/upgrading-posthog)!

## Getting started

The Airbyte export is an API integration. You will need to get a [PostHog Personal API key](https://posthog.com/docs/api) in order to [connect Airbyte as a data destination](https://docs.airbyte.com/integrations/sources/posthog/).

## Output schema

This destination is capable of syncing the following streams:

-   Annotations
-   Cohorts
-   Events
-   FeatureFlags
-   Insights
-   InsightsPath
-   InsightsSessions
-   Persons
-   Trends

For more info, please check [Airbyte's integration documentation](https://docs.airbyte.com/integrations/sources/posthog/).

## FAQ

### Where can I find out more?

Check [PostHog's API documentation](https://posthog.com/docs/api) for more information on pulling and pushing data from/to our API. Further information about Airbyte's connector is available in [Airbyte's integration documentation](https://docs.airbyte.com/integrations/sources/posthog/).

### Who maintains this destination?

This destination is maintained by Airbyte. For more information, check [Airbyte's integration documentation](https://docs.airbyte.com/integrations/sources/posthog/).

### What if I have feedback on this destination?

We love feature requests and feedback! Please [tell us what you think](http://app.posthog.com/home#supportModal)! to tell us what you think.

### What if my question isn't answered above?

We love answering questions. Ask us anything via [our community forum](/questions), or [drop us a message](http://app.posthog.com/home#supportModal). 
