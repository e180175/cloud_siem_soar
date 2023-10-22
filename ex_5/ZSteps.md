# Playbook walk-through

- First we bin our playbook to access Alert metadata like custom details.
- We initialize an array to store the custom details.
- We iterate through all the alerts, we parse them as JSON and then grab the custom details.
- We append the details to the array
- We send the data to a discord webhook to be displayed in a private channel


