# Playbook walk-through

PlaybookCreation and PlaybookCreationDesign
- First we bind our playbook to access Alert metadata like custom details.
- We initialize some variables to store the custom details.
- We iterate through all the alerts, we parse them as JSON and then grab the custom details.

WebhookDiscord
- We send the custom details (IPaddr and User) to a discord webhook to be displayed in a private channel

