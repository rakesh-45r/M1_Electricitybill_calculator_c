## Table no: High Level test plan

|**Test ID**|**Description**|**Exp i/P**|**Exp O/P**|**Actual O/P**|
| :- | :-: | :-: | :-: | :-: |
|HP01|Electricity bill calculation|Choice|SUCCESS|SUCCESS|
|HP02|Units consumed|Choice|SUCCESS|SUCCESS|



## Table no: Low Level test plan


|Test ID|Previous reading|Current reading|Exp input|Exp Output|Actual Output|
| :- | :- | :- | :- | :- | :- |
|LP01|Previous reading current reading is given| Integer 1|View the readings|pass| Requirement|
|LP02|Units will be calculated|Integer 2|View the units|pass| Requirement|
|LP03|Selection of group to calculate the bill amount|Integer 3|Exit|Pass| Requirement | 
|LP04|Three groups are available |char group|Pass|Pass| Requirement|
|LP05|You can select group | char group|Pass| pass | Requirement|
|LP06|The rate of charge will be noted |Integer 4|Pass|Pass | Requirement |
|LP07|The energy charges will be added to customer charges ,ED,Fixed charges |Integer 5| Pass | Requirements |
|LP08| Bill amounts will get as output |Integer 6| Exits from loop | Pass | Requirement |
