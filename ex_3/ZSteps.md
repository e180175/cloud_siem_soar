# Data Source, Rule and Workspace/Sentinel creation

(Workspace.png)
- First we create a workspace

(AddSentinelToWorkspace.png)
- We added Sentinel to our workspace

(DataCollectionRule, DataCollectionRuleSource and DataCollectionRuleSourceSyslog.png)
- We created a datasource to extract the log from the VM and feed Sentinel SIEM

(AnalyticsRuleWizard*.png)
- We created an AnalyticsRule using the wizard. We specified the log we wanted to handle at that time (auth through SSH)
- We also set some things up, like the response, the scheduling and the custom details we want to pass to the Alert (User, Ip and some metadata like time, facility and so on..)