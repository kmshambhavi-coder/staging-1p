# Bug repro block
An embedded workflow that can receive inputs and return an output.



**Enabled:** True

**Version:** 1

**Type:** Block

**Priority:** 2

**Playbook Simulator:** False


##### Input Parameters
|Name|Default Value|
|----|-------------|


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|GitSync_Ping_3|Test connectivity to GitSync|GitSync|Ping|
|Siemplify_Case Comment_3|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|Siemplify_Change Priority_1|Automatically change case priority to the given input|Siemplify|Change Priority|
|Siemplify_Case Comment_4|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|GitSync_Ping_1|Test connectivity to GitSync|GitSync|Ping|
|GitSync_Ping_2|Test connectivity to GitSync|GitSync|Ping|
|Siemplify_Case Comment_5|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|Siemplify_Case Comment_1|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|Siemplify_Case Comment_2|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|Siemplify_Case Tag_1|Add given tag to the case the current alert is grouped to|Siemplify|Case Tag|
|Siemplify_Case Comment_6|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|Siemplify_Change Alert Priority_1|Automatically change the alert priority to the given input. Note: This action is compatible only with Siemplify version 5.6 and higher.|Siemplify|Change Alert Priority|

