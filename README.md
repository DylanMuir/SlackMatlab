# README #

This repository contains ```Matlab``` functions to send notifications to a Slack channel or user, via the Slack [Incoming Webhooks](https://slack.com/services/new/incoming-webhook) API.

## Usage ##

```SendSlackNotification``` is used to send a notification to a URL provided by Slack, for a configured [Incoming Webhooks](https://slack.com/services/new/incoming-webhook) integration. See the documentation for this function for information on options.

```MakeSlackAttachments``` can be used to generate Slack [message attachments](https://api.slack.com/docs/attachments), which can then be sent as notifications using ```SendSlackNotification```. See the documentation for this function for more information.

## Emojis ##

A list of Emojis supported by Slack is available from (http://www.mathworks.com/matlabcentral/fileexchange/48508-slackmatlab).
