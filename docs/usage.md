| [Home](../README.md) |
|--------------------------------------------|

# Usage

This section gives a brief description on some of the commands used in FortiSOAR for Slack application:

## `/fortisoar createAlert`

This commands performs the following actions:

1. Displays a new alert form.
2. Uses the details from the form to create a new alert in FortiSOAR.

You can create placeholder alerts on the fly for further investigation by the Security Operations Center (SOC) team.

## `/fortisoar createIndicator`

This commands performs the following actions:

1. Displays a new indicator form.
2. Uses the details from the form to create a new indicator in FortiSOAR.
3. Takes an indicator value in the command to create the indicator with the specified value.

    `/fortisoar createIndicator <indicator_value>` adds an indicator in FortiSOAR and gets the latest enrichment details back to Slack within seconds.

    For example, `/fortisoar createIndicator gumblar.cn` creates an indicator of value `gumblar.cn`.

You can create indicators on the fly for enrichment and further investigation by the Security Operations Center (SOC) team.

## `fortisoar invokePlaybook`

This command takes another argument `tag:<value>` to trigger the playbook containing the tag `<value>`.

For example, the command `/invokePlaybook tag:getIPRep` invokes playbooks with the tag `getIPRep`.

This powerful action opens the automation capabilities for FortiSOAR where you can create and invoke playbooks in FortiSOAR.

>**NOTE**: The playbook you are trying to invoked must have an existing `bot_enabled` tag. 

## `/fortisoar help`

This command brings up the available commands and their usage details.

The command `/fortisoar availableCommands` lists all the available tags and labels that can be used with FortiSOAR commands for triggering playbooks.