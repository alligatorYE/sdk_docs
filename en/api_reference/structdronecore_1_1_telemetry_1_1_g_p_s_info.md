# dronecore::Telemetry::GPSInfo Struct Reference
`#include: telemetry.h`

----


GPS information type. 


## Data Fields


int [num_satellites](#structdronecore_1_1_telemetry_1_1_g_p_s_info_1acd6f37d3b511a6aae5895303fe61dc86)  - Number of visible satellites used for solution.

int [fix_type](#structdronecore_1_1_telemetry_1_1_g_p_s_info_1acc9d81d4b884bb2b229fe68d0c36f6cc)  - Fix type (0: no GPS, 1: no fix, 2: 2D fix, 3: 3D fix, 4: DGPS fix, 5: RTK float, 6: RTK fixed).


## Field Documentation


### num_satellites {#structdronecore_1_1_telemetry_1_1_g_p_s_info_1acd6f37d3b511a6aae5895303fe61dc86}

```cpp
int dronecore::Telemetry::GPSInfo::num_satellites
```


Number of visible satellites used for solution.


### fix_type {#structdronecore_1_1_telemetry_1_1_g_p_s_info_1acc9d81d4b884bb2b229fe68d0c36f6cc}

```cpp
int dronecore::Telemetry::GPSInfo::fix_type
```


Fix type (0: no GPS, 1: no fix, 2: 2D fix, 3: 3D fix, 4: DGPS fix, 5: RTK float, 6: RTK fixed).

