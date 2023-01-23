| [Home](../README.md) |
|----------------------|

# Contents

The **FortiSOAR for Slack** solution pack contains the following resources.

## Connectors

| Name       | Description                                                                                                                                                                       |
|:-----------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Slack      | Slack is a cloud-based set of proprietary team collaboration tools and services. This connector facilitates automated operations like list channels, list users, and send message |
| VirusTotal | Scans and analyzes suspicious files, URLs, IP addresses and retrieves reports from VirusTotal about them                                                                          |
| IPStack    | IPStack provides geolocation facility for IP Address or Domain.                                                                                                                   |

## Notification Channel

| Name               | Description                                         |
|:-------------------|:----------------------------------------------------|
| Slack Link Channel | Sends a message on slack when a certain rule is met |
| Slack channel      | Configured for manual input form on Slack           |

## Rules

Rules provide a framework to define a condition that generates notifications.

| Name                                     | Description                                                                                                                                                          |
|:-----------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Slack > Notify For External Manual Input | It Sends a notification to the slack application when the manual input step for Slack is triggered.                                                                  |
| Slack > Notify On Playbook Failure       | Sends an error when a playbook which has `bot_enabled` tag fails. Error: `PlaybookName` Playbook has failed. Please check the *Executed Playbook Logs* in FortiSOAR. |
| Slack > Send Manual Input Link To Slack  | Sends a link to Slack that can be clicked to get the manual input.                                                                                                   |

## Playbook Collection

| 02 - Use Case - FortiSOAR for Slack |
|:------------------------------------|

| Playbook Name        | Description                                                                                                |
|:---------------------|:-----------------------------------------------------------------------------------------------------------|
| Create Indicator     | Create Indicator/Indicators from the text provided as Input                                                         |
| Create Alert         | Creates an alert based on the values provided in the form                                                  |
| Enrich IP From Slack | Reference playbook that gets triggered from Slack based and provides latest reputation formatted for Slack |