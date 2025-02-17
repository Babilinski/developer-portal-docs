---
title: Gesture Classification System
summary: apis for the gesture classification system. 

---

# Gesture Classification System

APIs for the Gesture Classification system.  [More...](#detailed-description)

## Classes

|                | Name           |
| -------------- | -------------- |
| struct | **[MLGestureClassificationStaticData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_static_data.md)** <br></br>Static information about the gesture classification.  |
| struct | **[MLGestureClassificationPostureFingerData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_posture_finger_data.md)** <br></br>Gesture classification posture related finger data.  |
| struct | **[MLGestureClassificationFingerState](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_finger_state.md)** <br></br>Gesture classification state of a single finger.  |
| struct | **[MLGestureClassificationState](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_state.md)** <br></br>Gesture classification state of a single hand.  |
| struct | **[MLGestureClassificationData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_data.md)** <br></br>Data which is received when querying tracker from [MLGestureClassificationGetData()](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationgetdata).  |

## Types

|                | Name           |
| -------------- | -------------- |
| typedef struct [MLGestureClassificationStaticData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_static_data.md) | **[MLGestureClassificationStaticData](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#struct--mlgestureclassificationstaticdata)** <br></br>Static information about the gesture classification.  |
| typedef struct [MLGestureClassificationPostureFingerData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_posture_finger_data.md) | **[MLGestureClassificationPostureFingerData](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#struct--mlgestureclassificationposturefingerdata)** <br></br>Gesture classification posture related finger data.  |
| typedef struct [MLGestureClassificationFingerState](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_finger_state.md) | **[MLGestureClassificationFingerState](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#struct--mlgestureclassificationfingerstate)** <br></br>Gesture classification state of a single finger.  |
| typedef struct [MLGestureClassificationState](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_state.md) | **[MLGestureClassificationState](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#struct--mlgestureclassificationstate)** <br></br>Gesture classification state of a single hand.  |
| typedef struct [MLGestureClassificationData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_data.md) | **[MLGestureClassificationData](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#struct--mlgestureclassificationdata)** <br></br>Data which is received when querying tracker from [MLGestureClassificationGetData()](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationgetdata).  |

## Enums

|                | Name           |
| -------------- | -------------- |
| enum | **[MLGestureClassificationHandType](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationhandtype)** <br></br> { <br></br>[MLGestureClassificationHandType_Left](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationhandtype-left) = 0,<br></br> [MLGestureClassificationHandType_Right](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationhandtype-right) = 1,<br></br> [MLGestureClassificationHandType_Count](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationhandtype-count) = 2,<br></br> [MLGestureClassificationHandType_Ensure32Bits](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationhandtype-ensure32bits) = 0x7FFFFFFF<br></br>} |
| enum | **[MLGestureClassificationPostureType](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationposturetype)** <br></br> { <br></br>[MLGestureClassificationPostureType_None](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationposturetype-none) = 0,<br></br> [MLGestureClassificationPostureType_Pinch](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationposturetype-pinch) = 1,<br></br> [MLGestureClassificationPostureType_Point](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationposturetype-point) = 2,<br></br> [MLGestureClassificationPostureType_Grasp](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationposturetype-grasp) = 3,<br></br> [MLGestureClassificationPostureType_Open](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationposturetype-open) = 4,<br></br> [MLGestureClassificationPostureType_Ensure32Bits](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationposturetype-ensure32bits) = 0x7FFFFFFF<br></br>}<br></br>System gesture classification posture type.  |
| enum | **[MLGestureClassificationKeyPoseType](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype)** <br></br> { <br></br>[MLGestureClassificationKeyPoseType_None](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype-none) = 0,<br></br> [MLGestureClassificationKeyPoseType_OK](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype-ok) = 1,<br></br> [MLGestureClassificationKeyPoseType_C](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype-c) = 2,<br></br> [MLGestureClassificationKeyPoseType_Pinch](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype-pinch) = 3,<br></br> [MLGestureClassificationKeyPoseType_Finger](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype-finger) = 4,<br></br> [MLGestureClassificationKeyPoseType_L](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype-l) = 5,<br></br> [MLGestureClassificationKeyPoseType_Thumb](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype-thumb) = 6,<br></br> [MLGestureClassificationKeyPoseType_Fist](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype-fist) = 7,<br></br> [MLGestureClassificationKeyPoseType_Open](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype-open) = 8,<br></br> [MLGestureClassificationKeyPoseType_Ensure32Bits](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype-ensure32bits) = 0x7FFFFFFF<br></br>}<br></br>System gesture classification key pose type.  |

## Functions

|                | Name           |
| -------------- | -------------- |
| void | **[MLGestureClassificationStaticDataInit](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#void-mlgestureclassificationstaticdatainit)**([MLGestureClassificationStaticData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_static_data.md) * inout_data)<br></br>Initializes default values for [MLGestureClassificationStaticData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_static_data.md).  |
| void | **[MLGestureClassificationDataInit](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#void-mlgestureclassificationdatainit)**([MLGestureClassificationData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_data.md) * inout_data)<br></br>Initializes default values for [MLGestureClassificationData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_data.md).  |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) | **[MLGestureClassificationCreate](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationcreate)**([MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) * out_handle)<br></br>Creates a gesture classification tracker.  |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) | **[MLGestureClassificationDestroy](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationdestroy)**([MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) handle)<br></br>Destroys a gesture classification tracker.  |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) | **[MLGestureClassificationGetStaticData](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationgetstaticdata)**([MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) handle, [MLGestureClassificationStaticData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_static_data.md) * out_data)<br></br>Gets static information about the gesture classification.  |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) | **[MLGestureClassificationGetData](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationgetdata)**([MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) handle, [MLGestureClassificationData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_data.md) * out_data)<br></br>Queries the state of the gesture classification.  |

## Detailed Description

APIs for the Gesture Classification system. 



1. Postures ([MLGestureClassificationPostureType](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationposturetype)).
2. Key Poses ([MLGestureClassificationKeyPoseType](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationkeyposetype)).

# Postures

Postures is a collection of hand configuration that allows for meaningful variations of the same configuration. For example a hand configuration is classified as pinch posture when the index and thumb tip is touching while the other three fingers are fully extended. At the same time a hand configuration where the index and thumb tips are touching but the other three fingers are partially curled will still be treated as a pinch posture.

Postures will be more accommodative to variations seen between users and the same user doing the gesture in slightly different ways.

Postures will work well for use cases where the user is interacting with the UI over time. Examples: grab and move, point and click.


# KeyPoses

KeyPoses on the other hand is a discrete collection of static hand configurations. It looks for specific geometric relationship between the hand key points.

KeyPoses will work well for use cases where the user need a on-off switch, a button. Examples: start capture, save session.


# Point

The interaction point is a transform which dynamically adapts, in both translation and rotation, based on the current classified posture ([MLGestureClassificationPostureType](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#enums-mlgestureclassificationposturetype)). It provides a single optimal point of reference to simplify common direct and indirect hand interactions. 




**Shared Object:**
  * perception.magicleap The gesture classification system identifies specific hand configurations and exposes them via the APIs here. These hand configurations can be broadly divided into two groups:




-----------
## Enums Documentation

### MLGestureClassificationHandType {#enums-mlgestureclassificationhandtype}

| Enumerator | Value | Description |
| ---------- | ----- | ----------- |
| MLGestureClassificationHandType_Left |  0| Left hand. |
| MLGestureClassificationHandType_Right |  1| Right hand. |
| MLGestureClassificationHandType_Count |  2| Number of hands. |
| MLGestureClassificationHandType_Ensure32Bits |  0x7FFFFFFF| Ensure enum is represented as 32 bits. |




Available hand types. 





-----------

### MLGestureClassificationPostureType {#enums-mlgestureclassificationposturetype}

| Enumerator | Value | Description |
| ---------- | ----- | ----------- |
| MLGestureClassificationPostureType_None |  0| None. |
| MLGestureClassificationPostureType_Pinch |  1| Pinch posture. |
| MLGestureClassificationPostureType_Point |  2| Point posture. |
| MLGestureClassificationPostureType_Grasp |  3| Grasp posture. |
| MLGestureClassificationPostureType_Open |  4| Open hand. |
| MLGestureClassificationPostureType_Ensure32Bits |  0x7FFFFFFF| Ensure enum is represented as 32 bits. |



System gesture classification posture type. 




**API Level:**
  * 20 




-----------

### MLGestureClassificationKeyPoseType {#enums-mlgestureclassificationkeyposetype}

| Enumerator | Value | Description |
| ---------- | ----- | ----------- |
| MLGestureClassificationKeyPoseType_None |  0| None. |
| MLGestureClassificationKeyPoseType_OK |  1| OK pose. |
| MLGestureClassificationKeyPoseType_C |  2| C pose. |
| MLGestureClassificationKeyPoseType_Pinch |  3| Pinch pose. |
| MLGestureClassificationKeyPoseType_Finger |  4| Finger pose. |
| MLGestureClassificationKeyPoseType_L |  5| L pose. |
| MLGestureClassificationKeyPoseType_Thumb |  6| Thumb up pose. |
| MLGestureClassificationKeyPoseType_Fist |  7| Fist pose. |
| MLGestureClassificationKeyPoseType_Open |  8| Open pose. |
| MLGestureClassificationKeyPoseType_Ensure32Bits |  0x7FFFFFFF| Ensure enum is represented as 32 bits. |



System gesture classification key pose type. 




**API Level:**
  * 20 




-----------


## Types Documentation

### MLGestureClassificationStaticData {#struct--mlgestureclassificationstaticdata}

```cpp
typedef struct MLGestureClassificationStaticData  MLGestureClassificationStaticData;
```

Static information about the gesture classification. 

Populate with [MLGestureClassificationGetStaticData()](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationgetstaticdata). This structure must be initialized by calling [MLGestureClassificationStaticDataInit()](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#void-mlgestureclassificationstaticdatainit) before use.



[More Info](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_static_data.md)


**API Level:**
  * 20 




-----------

### MLGestureClassificationPostureFingerData {#struct--mlgestureclassificationposturefingerdata}

```cpp
typedef struct MLGestureClassificationPostureFingerData  MLGestureClassificationPostureFingerData;
```

Gesture classification posture related finger data. 

Pinch values are measured between the finger and thumb. In case thumb is the finger, values are same with index's values.



[More Info](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_posture_finger_data.md)


**API Level:**
  * 20 




-----------

### MLGestureClassificationFingerState {#struct--mlgestureclassificationfingerstate}

```cpp
typedef struct MLGestureClassificationFingerState  MLGestureClassificationFingerState;
```

Gesture classification state of a single finger. 



[More Info](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_finger_state.md)


**API Level:**
  * 20 




-----------

### MLGestureClassificationState {#struct--mlgestureclassificationstate}

```cpp
typedef struct MLGestureClassificationState  MLGestureClassificationState;
```

Gesture classification state of a single hand. 



[More Info](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_state.md)


**API Level:**
  * 20 




-----------

### MLGestureClassificationData {#struct--mlgestureclassificationdata}

```cpp
typedef struct MLGestureClassificationData  MLGestureClassificationData;
```

Data which is received when querying tracker from [MLGestureClassificationGetData()](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationgetdata). 

This structure must be initialized by calling [MLGestureClassificationDataInit()](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#void-mlgestureclassificationdatainit) before use.



[More Info](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_data.md)


**API Level:**
  * 20 




-----------


## Functions Documentation

### MLGestureClassificationStaticDataInit {#void-mlgestureclassificationstaticdatainit}

```cpp
static inline void MLGestureClassificationStaticDataInit(
    MLGestureClassificationStaticData * inout_data
)
```

Initializes default values for [MLGestureClassificationStaticData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_static_data.md). 

**Parameters**

|  |   |   |
|--|--|--|
| [MLGestureClassificationStaticData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_static_data.md) * |inout_data|The object to initialize with default settings. |



**API Level:**
  * 20




-----------

### MLGestureClassificationDataInit {#void-mlgestureclassificationdatainit}

```cpp
static inline void MLGestureClassificationDataInit(
    MLGestureClassificationData * inout_data
)
```

Initializes default values for [MLGestureClassificationData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_data.md). 

**Parameters**

|  |   |   |
|--|--|--|
| [MLGestureClassificationData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_data.md) * |inout_data|The object to initialize with default settings. |



**API Level:**
  * 20




-----------

### MLGestureClassificationCreate {#mlresult-mlgestureclassificationcreate}

```cpp
MLResult MLGestureClassificationCreate(
    MLHandle * out_handle
)
```

Creates a gesture classification tracker. 

**Parameters**

|  |   |   |
|--|--|--|
| [MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) * |out_handle|A handle to the created gesture classification tracker. Only valid if the return value is MLResult_Ok.|

**Returns**

|  |   |   |
|--|--|--|
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_InvalidParam|Failed to create a tracker due to an invalid parameter. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_Ok|The tracker was created successfully. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_PerceptionSystemNotStarted|Perception System has not been started. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_PrivilegeDenied|The application lacks privilege. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_UnspecifiedFailure|The operation failed with an unspecified error.|
**Required Permissions**:

  * com.magicleap.permission.HAND_TRACKING (protection level: normal) 





**API Level:**
  * 20




-----------

### MLGestureClassificationDestroy {#mlresult-mlgestureclassificationdestroy}

```cpp
MLResult MLGestureClassificationDestroy(
    MLHandle handle
)
```

Destroys a gesture classification tracker. 

**Parameters**

|  |   |   |
|--|--|--|
| [MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) |handle|A handle to a gesture classification tracker created by [MLGestureClassificationCreate()](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationcreate).|

**Returns**

|  |   |   |
|--|--|--|
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_InvalidParam|Failed to destroy a tracker due to an invalid parameter. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_Ok|It successfully destroyed the tracker. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_PerceptionSystemNotStarted|Perception System has not been started. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_UnspecifiedFailure|The operation failed with an unspecified error.|
**Required Permissions**:

  * None 





**API Level:**
  * 20




-----------

### MLGestureClassificationGetStaticData {#mlresult-mlgestureclassificationgetstaticdata}

```cpp
MLResult MLGestureClassificationGetStaticData(
    MLHandle handle,
    MLGestureClassificationStaticData * out_data
)
```

Gets static information about the gesture classification. 

**Parameters**

|  |   |   |
|--|--|--|
| [MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) |handle|A handle to a gesture classification tracker created by [MLGestureClassificationCreate()](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationcreate). |
| [MLGestureClassificationStaticData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_static_data.md) * |out_data|Target to populate the data about the gesture classification.|

**Returns**

|  |   |   |
|--|--|--|
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_InvalidParam|Failed to get static data due to an invalid parameter. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_Ok|Gesture classification static data was successfully received. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_PerceptionSystemNotStarted|Perception System has not been started. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_UnspecifiedFailure|The operation failed with an unspecified error.|
**Required Permissions**:

  * None 





**API Level:**
  * 20




-----------

### MLGestureClassificationGetData {#mlresult-mlgestureclassificationgetdata}

```cpp
MLResult MLGestureClassificationGetData(
    MLHandle handle,
    MLGestureClassificationData * out_data
)
```

Queries the state of the gesture classification. 

**Parameters**

|  |   |   |
|--|--|--|
| [MLHandle](/api-ref/api/Modules/group___platform/group___platform.md#uint64-t-mlhandle) |handle|A handle to a gesture classification tracker created by [MLGestureClassificationCreate()](/api-ref/api/Modules/group___gesture_classification/group___gesture_classification.md#mlresult-mlgestureclassificationcreate). |
| [MLGestureClassificationData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_data.md) * |out_data|Pointer to [MLGestureClassificationData](/api-ref/api/Modules/group___gesture_classification/struct_m_l_gesture_classification_data.md) structure.|

**Returns**

|  |   |   |
|--|--|--|
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_InvalidParam|Failed to retrieve data due to an invalid parameter. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_Ok|The state information was available and the information in out_data is valid. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_PerceptionSystemNotStarted|Perception System has not been started. |
| [MLResult](/api-ref/api/Modules/group___platform/group___platform.md#int32-t-mlresult) |MLResult_UnspecifiedFailure|The operation failed with an unspecified error.|
**Required Permissions**:

  * None 





**API Level:**
  * 20




-----------





