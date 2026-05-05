# Bug repro playbook




**Enabled:** False

**Version:** 1

**Type:** Playbook

**Priority:** 2

**Playbook Simulator:** False


### Playbook Trigger
**Trigger Type:** All

**Conditions Operator:** And

##### Conditions
|Key|Operator|Value|
|---|--------|-----|
||Equals||


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|Siemplify_Case Tag_1|Add given tag to the case the current alert is grouped to|Siemplify|Case Tag|
|Siemplify_Case Tag_2|Add given tag to the case the current alert is grouped to|Siemplify|Case Tag|
|Siemplify_Change Alert Priority_2|Automatically change the alert priority to the given input. Note: This action is compatible only with Siemplify version 5.6 and higher.|Siemplify|Change Alert Priority|
|Siemplify_Change Priority_1|Automatically change case priority to the given input|Siemplify|Change Priority|
|GitSync_Ping_2|Test connectivity to GitSync|GitSync|Ping|
|Siemplify_Assign Case_1|Use the "Assign Case" action to assign the case to a user.|Siemplify|Assign Case|
|GitSync_Ping_1|Test connectivity to GitSync|GitSync|Ping|
|Siemplify_Change Alert Priority_1|Automatically change the alert priority to the given input. Note: This action is compatible only with Siemplify version 5.6 and higher.|Siemplify|Change Alert Priority|

### Involved Blocks
|Name|Description|
|----|-----------|
|Bug repro block|An embedded workflow that can receive inputs and return an output.|
