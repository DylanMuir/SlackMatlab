# README #

This repository contains ```Matlab``` functions to send notifications to a Slack channel or user, via the Slack [Incoming Webhooks](https://slack.com/services/new/incoming-webhook) API.

## Usage ##

```SendSlackNotification``` is used to send a notification to a URL provided by Slack, for a configured [Incoming Webhooks](https://slack.com/services/new/incoming-webhook) integration.

```MakeSlackAttachments``` can be used to generate Slack [message attachments](https://api.slack.com/docs/attachments), which can then be sent as notifications using ```SendSlackNotification```.