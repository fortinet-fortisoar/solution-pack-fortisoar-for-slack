| [Home](../README.md) |
|--------------------------------------------|

# Usage
**Slack Commands**

• Create Alert: A quick slash command, */fortisoar createAlert*, shows up a new alert form, using which you can quickly create an alert in FortiSOAR. Use this as part of your communications, and create placeholder alerts on the fly for further investigation by the SOC team. 
• Create Indicator: A quick slash command, */fortisoar createIndicator*, shows up a new indicator form, using which you can quickly create an indicator in FortiSOAR. Now, the moment you hear about some new suspicious artifact or an indicator as part of your communications, you can quickly create an indicator in FortiSOAR for further enrichment and follow-up. 

• Invoke Playbook: A quick slash command, */fortisoar invokePlaybook* followed by a syntax, *tag:<anyPlaybookContainingThisTag>*, triggers the playbook which contained that tag. For example, */invokePlaybook tag:getIPRep*, will invoke the playbook that has the tag “getIpRep” linked to it. This is a very powerful action, that opens up the full automation power of FortiSOAR, allowing you to create and invoke any playbook in FortiSOAR. 

•Help: Use */fortisoar help*, to revisit the actions and more about what they do through this quick action. 

