---
ns: VEHICLE
aliases: ["_GET_VEHICLE_MODEL_MAX_NUMBER_OF_PASSENGERS"]
---
## GET_VEHICLE_MODEL_NUMBER_OF_SEATS

```c
// 0x2AD93716F184EDA4 0x838F7BF7
int GET_VEHICLE_MODEL_NUMBER_OF_SEATS(Hash modelHash);
```

```
Returns max number of passengers (including the driver) for the specified vehicle model.
```
Uses the model name returned by the GetEntityArchetypeName command. The return from GetEntityModel will work for some vehicles, but not for all.

## Parameters
* **modelHash**: 

## Return value
