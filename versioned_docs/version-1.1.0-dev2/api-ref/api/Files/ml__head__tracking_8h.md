---
title: ml_head_tracking.h

---

# ml_head_tracking.h



## Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[MLHeadTrackingStaticData](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_static_data.md)**  |
| struct | **[MLHeadTrackingState](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_state.md)**  |

## Types

|                | Name           |
| -------------- | -------------- |
| typedef struct [MLHeadTrackingStaticData](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_static_data.md) | **[MLHeadTrackingStaticData](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#struct--mlheadtrackingstaticdata)**  |
| typedef struct [MLHeadTrackingState](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_state.md) | **[MLHeadTrackingState](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#struct--mlheadtrackingstate)**  |

## Enums

|                | Name           |
| -------------- | -------------- |
| enum | **[MLHeadTrackingError](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#enums-mlheadtrackingerror)** <br></br> { <br></br>[MLHeadTrackingError_None](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingerror-none),<br></br> [MLHeadTrackingError_NotEnoughFeatures](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingerror-notenoughfeatures),<br></br> [MLHeadTrackingError_LowLight](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingerror-lowlight),<br></br> [MLHeadTrackingError_Unknown](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingerror-unknown),<br></br> [MLHeadTrackingError_Ensure32Bits](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingerror-ensure32bits) = 0x7FFFFFFF<br></br>} |
| enum | **[MLHeadTrackingMode](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#enums-mlheadtrackingmode)** <br></br> { <br></br>[MLHeadTrackingMode_6DOF](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingmode-6dof) = 0,<br></br> [MLHeadTrackingMode_Unavailable](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingmode-unavailable) = 1,<br></br> [MLHeadTrackingMode_Ensure32Bits](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingmode-ensure32bits) = 0x7FFFFFFF<br></br>} |
| enum | **[MLHeadTrackingMapEvent](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#enums-mlheadtrackingmapevent)** <br></br> { <br></br>[MLHeadTrackingMapEvent_Lost](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingmapevent-lost) = (1 << 0),<br></br> [MLHeadTrackingMapEvent_Recovered](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingmapevent-recovered) = (1 << 1),<br></br> [MLHeadTrackingMapEvent_RecoveryFailed](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingmapevent-recoveryfailed) = (1 << 2),<br></br> [MLHeadTrackingMapEvent_NewSession](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingmapevent-newsession) = (1 << 3),<br></br> [MLHeadTrackingMapEvent_Ensure32Bits](/api-ref/api/Files/ml__head__tracking_8h.md#enums-mlheadtrackingmapevent-ensure32bits) = 0x7FFFFFFF<br></br>}<br></br>Different types of map events that can occur that a developer may have to handle.  |

## Functions

|                | Name           |
| -------------- | -------------- |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) | **[MLHeadTrackingCreate](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#mlresult-mlheadtrackingcreate)**([MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) * out_handle)<br></br>Creates a Head Tracker.  |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) | **[MLHeadTrackingDestroy](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#mlresult-mlheadtrackingdestroy)**([MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) head_tracker)<br></br>Destroys a Head Tracker.  |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) | **[MLHeadTrackingGetStaticData](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#mlresult-mlheadtrackinggetstaticdata)**([MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) head_tracker, [MLHeadTrackingStaticData](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_static_data.md) * out_data)<br></br>Returns static information about the Head Tracker.  |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) | **[MLHeadTrackingGetState](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#mlresult-mlheadtrackinggetstate)**([MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) head_tracker, [MLHeadTrackingState](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_state.md) * out_state)<br></br>Returns the most recent head tracking state.  |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) | **[MLHeadTrackingGetMapEvents](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#mlresult-mlheadtrackinggetmapevents)**([MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) head_tracker, uint64_t * out_map_events)<br></br>Gets map events.  |

## Enums Documentation

### MLHeadTrackingError {#enums-mlheadtrackingerror}

| Enumerator | Value | Description |
| ---------- | ----- | ----------- |
| MLHeadTrackingError_None | | No error, tracking is nominal. |
| MLHeadTrackingError_NotEnoughFeatures | | There are not enough features in the environment. |
| MLHeadTrackingError_LowLight | | Lighting in the environment is not sufficient to track accurately. |
| MLHeadTrackingError_Unknown | | Head tracking failed for an unkown reason. |
| MLHeadTrackingError_Ensure32Bits |  0x7FFFFFFF| Ensure enum is represented as 32 bits. |




A set of possible error conditions that can cause Head Tracking to be less than ideal. 





-----------

### MLHeadTrackingMode {#enums-mlheadtrackingmode}

| Enumerator | Value | Description |
| ---------- | ----- | ----------- |
| MLHeadTrackingMode_6DOF |  0| Full 6 degrees of freedom tracking (position and orientation). |
| MLHeadTrackingMode_Unavailable |  1| Head tracking is unavailable. |
| MLHeadTrackingMode_Ensure32Bits |  0x7FFFFFFF| Ensure enum is represented as 32 bits. |




A set of possible tracking modes the Head Tracking system can be in. 





-----------

### MLHeadTrackingMapEvent {#enums-mlheadtrackingmapevent}

| Enumerator | Value | Description |
| ---------- | ----- | ----------- |
| MLHeadTrackingMapEvent_Lost |  (1 << 0)| Map was lost. It could possibly recover. |
| MLHeadTrackingMapEvent_Recovered |  (1 << 1)| Previous map was recovered. |
| MLHeadTrackingMapEvent_RecoveryFailed |  (1 << 2)| Failed to recover previous map. |
| MLHeadTrackingMapEvent_NewSession |  (1 << 3)| New map session created. |
| MLHeadTrackingMapEvent_Ensure32Bits |  0x7FFFFFFF| Ensure enum is represented as 32 bits. |



Different types of map events that can occur that a developer may have to handle. 




**API Level:**
  * 2 




-----------


## Types Documentation

### MLHeadTrackingStaticData {#struct--mlheadtrackingstaticdata}

```cpp
typedef struct MLHeadTrackingStaticData  MLHeadTrackingStaticData;
```


Static information about a Head Tracker. Populate this structure with [MLHeadTrackingGetStaticData()](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#mlresult-mlheadtrackinggetstaticdata). 



[More Info](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_static_data.md)



-----------

### MLHeadTrackingState {#struct--mlheadtrackingstate}

```cpp
typedef struct MLHeadTrackingState  MLHeadTrackingState;
```


A structure containing information on the current state of the Head Tracking system. 



[More Info](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_state.md)



-----------


## Functions Documentation

### MLHeadTrackingCreate {#mlresult-mlheadtrackingcreate}

```cpp
MLResult MLHeadTrackingCreate(
    MLHandle * out_handle
)
```

Creates a Head Tracker. 

**Parameters**

|  |   |   |
|--|--|--|
| [MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) * |out_handle|A pointer to an MLHandle which will contain the handle of the head tracker. If this operation fails, out_handle will be [ML_INVALID_HANDLE](/api-ref/api/Modules/group___platform/group___platform.md#enums-ml-invalid-handle).|

**Returns**

|  |   |   |
|--|--|--|
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_Ok|Successfully created head tracker. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_UnspecifiedFailure|Failed to create head tracker due to an unknown error. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_PermissionDenied|The application lacks permission.|
**Required Permissions**:

  * None 






-----------

### MLHeadTrackingDestroy {#mlresult-mlheadtrackingdestroy}

```cpp
MLResult MLHeadTrackingDestroy(
    MLHandle head_tracker
)
```

Destroys a Head Tracker. 

**Parameters**

|  |   |   |
|--|--|--|
| [MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) |head_tracker|A handle to a Head Tracker created by [MLHeadTrackingCreate()](/api-ref/api/Modules/group___head_tracking/group___head_tracking.md#mlresult-mlheadtrackingcreate).|

**Returns**

|  |   |   |
|--|--|--|
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_Ok|Successfully destroyed head tracker. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_UnspecifiedFailure|Failed to destroy head tracker due to an unknown error.|
**Required Permissions**:

  * None 






-----------

### MLHeadTrackingGetStaticData {#mlresult-mlheadtrackinggetstaticdata}

```cpp
MLResult MLHeadTrackingGetStaticData(
    MLHandle head_tracker,
    MLHeadTrackingStaticData * out_data
)
```

Returns static information about the Head Tracker. 

**Parameters**

|  |   |   |
|--|--|--|
| [MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) |head_tracker|A handle to the tracker. |
| [MLHeadTrackingStaticData](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_static_data.md) * |out_data|Target to populate the data about that Head Tracker.|

**Returns**

|  |   |   |
|--|--|--|
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_InvalidParam|Failed to receive static data due to an invalid input parameter. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_Ok|Successfully received static data. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_UnspecifiedFailure|Failed to receive static data due to an unknown error.|
**Required Permissions**:

  * None 






-----------

### MLHeadTrackingGetState {#mlresult-mlheadtrackinggetstate}

```cpp
MLResult MLHeadTrackingGetState(
    MLHandle head_tracker,
    MLHeadTrackingState * out_state
)
```

Returns the most recent head tracking state. 

**Parameters**

|  |   |   |
|--|--|--|
| [MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) |head_tracker|A handle to the tracker. |
| [MLHeadTrackingState](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_state.md) * |out_state|Pointer to valid [MLHeadTrackingState](/api-ref/api/Modules/group___head_tracking/struct_m_l_head_tracking_state.md) object to be filled with current state information.|

**Returns**

|  |   |   |
|--|--|--|
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_InvalidParam|Failed to return the most recent head tracking state due to an invalid input parameter. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_Ok|Successfully returned the most recent head tracking state. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_UnspecifiedFailure|Failed to return the most recent head tracking state due to an unknown error.|
**Required Permissions**:

  * None 






-----------

### MLHeadTrackingGetMapEvents {#mlresult-mlheadtrackinggetmapevents}

```cpp
MLResult MLHeadTrackingGetMapEvents(
    MLHandle head_tracker,
    uint64_t * out_map_events
)
```

Gets map events. 

**Parameters**

|  |   |   |
|--|--|--|
| [MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) |head_tracker|A handle to the tracker. |
| uint64_t * |out_map_events|Pointer to a uint64_t representing a bitmask of MLHeadTrackingMapEvent, allocated by the caller.|

**Returns**

|  |   |   |
|--|--|--|
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_InvalidParam|Failed to get map events due to an invalid input parameter. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_Ok|Successfully got map events. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_UnspecifiedFailure|Failed to get map events due to an unknown error.|
**Required Permissions**:

  * None 


A developer must be aware of certain events that can occur under degenerative conditions in order to cleanly handle it. The most important event to be aware of is when a map changes.

In the case that a new map session begins, or recovery fails, all formerly cached transform and world reconstruction data (raycast, planes, mesh) is invalidated and must be updated.




**API Level:**
  * 2




-----------



## Source code

```cpp
// %BANNER_BEGIN%
// ---------------------------------------------------------------------
// %COPYRIGHT_BEGIN%
// Copyright (c) 2017 Magic Leap, Inc. All Rights Reserved.
// Use of this file is governed by the Software License Agreement,
// located here: https://www.magicleap.com/software-license-agreement-ml2
// Terms and conditions applicable to third-party materials accompanying
// this distribution may also be found in the top-level NOTICE file
// appearing herein.
// %COPYRIGHT_END%
// ---------------------------------------------------------------------
// %BANNER_END%

#pragma once

#include "ml_api.h"

ML_EXTERN_C_BEGIN

typedef struct MLHeadTrackingStaticData {
  MLCoordinateFrameUID coord_frame_head;
} MLHeadTrackingStaticData;

typedef enum MLHeadTrackingError {
  MLHeadTrackingError_None,
  MLHeadTrackingError_NotEnoughFeatures,
  MLHeadTrackingError_LowLight,
  MLHeadTrackingError_Unknown,
  MLHeadTrackingError_Ensure32Bits = 0x7FFFFFFF
} MLHeadTrackingError;

typedef enum MLHeadTrackingMode {
  MLHeadTrackingMode_6DOF = 0,
  MLHeadTrackingMode_Unavailable = 1,
  MLHeadTrackingMode_Ensure32Bits = 0x7FFFFFFF
} MLHeadTrackingMode;

typedef struct MLHeadTrackingState {
  MLHeadTrackingMode mode;
  float confidence;
  MLHeadTrackingError error;
} MLHeadTrackingState;

typedef enum MLHeadTrackingMapEvent {
  MLHeadTrackingMapEvent_Lost = (1 << 0),
  MLHeadTrackingMapEvent_Recovered = (1 << 1),
  MLHeadTrackingMapEvent_RecoveryFailed = (1 << 2),
  MLHeadTrackingMapEvent_NewSession = (1 << 3),
  MLHeadTrackingMapEvent_Ensure32Bits = 0x7FFFFFFF
} MLHeadTrackingMapEvent;

ML_API MLResult ML_CALL MLHeadTrackingCreate(MLHandle *out_handle);

ML_API MLResult ML_CALL MLHeadTrackingDestroy(MLHandle head_tracker);

ML_API MLResult ML_CALL MLHeadTrackingGetStaticData(MLHandle head_tracker, MLHeadTrackingStaticData *out_data);

ML_API MLResult ML_CALL MLHeadTrackingGetState(MLHandle head_tracker, MLHeadTrackingState *out_state);

ML_API MLResult ML_CALL MLHeadTrackingGetMapEvents(MLHandle head_tracker, uint64_t *out_map_events);

ML_EXTERN_C_END
```



