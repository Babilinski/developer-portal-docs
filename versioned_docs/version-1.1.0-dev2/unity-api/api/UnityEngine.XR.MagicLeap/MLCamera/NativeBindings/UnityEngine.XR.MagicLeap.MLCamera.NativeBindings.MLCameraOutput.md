---
title: MLCameraOutput
summary: captured output 

---

# MLCameraOutput




Captured output   





## Public Methods

### [MLCameraOutput](/unity-api/api/UnityEngine.XR.MagicLeap/MLCamera/NativeBindings/UnityEngine.XR.MagicLeap.MLCamera.NativeBindings.MLCameraOutput.md) Create {#mlcameraoutput-create}

Create and return an initialized version of this struct. 

```csharp
public static MLCameraOutput Create()
```






**Returns**: Returns a new MLCamera.Output structure.



-----------

### [CameraOutput](/unity-api/api/UnityEngine.XR.MagicLeap/MLCamera/UnityEngine.XR.MagicLeap.MLCamera.CameraOutput.md) CreateFrameInfo {#cameraoutput-createframeinfo}

```csharp
public CameraOutput CreateFrameInfo(
    bool copyToManagedMemory,
    byte byteArraysToUse[][] =null
)
```


**Parameters**

| Type | Name  | Description  | 
|--|--|--|
| bool |copyToManagedMemory||
| byte |byteArraysToUse[][]||






-----------

## Public Attributes

### Format {#outputformat-format}

Supported output format specified by [MLCamera.OutputFormat](/unity-api/api/UnityEngine.XR.MagicLeap/MLCamera/UnityEngine.XR.MagicLeap.MLCamera.md#enums-outputformat)

```csharp

public OutputFormat Format;

```

| Type | Description  | 
|--|--|
| [OutputFormat](/unity-api/api/UnityEngine.XR.MagicLeap/MLCamera/UnityEngine.XR.MagicLeap.MLCamera.md#enums-outputformat) | Captured output format  |





-----------

### PlaneCount {#byte-planecount}

Number of output image planes: 

```csharp

public byte PlaneCount;

```


**Details**



* 1 for compressed output such as JPEG stream,
* 3 for separate color component output such as  YUV/YCbCr/RGB. 





-----------

### Planes {#mlcameraplaneinfo-planes}

Output image plane info. The number of output planes is specified by PlaneCount. 

```csharp

public MLCameraPlaneInfo [] Planes;

```

| Type | Description  | 
|--|--|
| [MLCameraPlaneInfo](/unity-api/api/UnityEngine.XR.MagicLeap/MLCamera/NativeBindings/UnityEngine.XR.MagicLeap.MLCamera.NativeBindings.MLCameraPlaneInfo.md) [] | Per plane info for captured output  |





-----------

### Version {#uint-version}

version contains the version number for this structure. 

```csharp

public uint Version;

```






-----------

