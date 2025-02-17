---
title: Request

---

# Request







Inherits from: <br></br>[MLRequest< Request.Params, Request.Result >](/unity-api/api/UnityEngine.XR.MagicLeap/UnityEngine.XR.MagicLeap.MLRequest.md),<br></br>[IMLRequest< Params, Result >](/unity-api/api/UnityEngine.XR.MagicLeap/UnityEngine.XR.MagicLeap.IMLRequest.md)




## Public Methods

###  Request {#functions-request}

```csharp
public Request()
```






-----------

### override [MLResult](/unity-api/api/UnityEngine.XR.MagicLeap/UnityEngine.XR.MagicLeap.MLResult.md) Start {#override--start}

```csharp
public override MLResult Start(
    Params parameters
)
```


**Parameters**

| Type | Name  | Description  | 
|--|--|--|
| [Params](/unity-api/api/UnityEngine.XR.MagicLeap/MLAnchors/Request/UnityEngine.XR.MagicLeap.MLAnchors.Request.Params.md) |parameters|A collection of filters for Spatial [Anchor](/unity-api/api/UnityEngine.XR.MagicLeap/MLAnchors/UnityEngine.XR.MagicLeap.MLAnchors.Anchor.md) queries. Filters that have been set will be combined via logical conjunction. E. g. results must match the ids filter AND fall within the radius constraint when both have been set. This struct must be initialized by calling #MLSpatialAnchorQueryFilterInit before use. |






-----------

### [MLResult](/unity-api/api/UnityEngine.XR.MagicLeap/UnityEngine.XR.MagicLeap.MLResult.md) Start {#mlresult-start}

```csharp
public MLResult Start(
    Params parameters,
    out uint resultsCount
)
```


**Parameters**

| Type | Name  | Description  | 
|--|--|--|
| [Params](/unity-api/api/UnityEngine.XR.MagicLeap/MLAnchors/Request/UnityEngine.XR.MagicLeap.MLAnchors.Request.Params.md) |parameters|A collection of filters for Spatial [Anchor](/unity-api/api/UnityEngine.XR.MagicLeap/MLAnchors/UnityEngine.XR.MagicLeap.MLAnchors.Anchor.md) queries. Filters that have been set will be combined via logical conjunction. E. g. results must match the ids filter AND fall within the radius constraint when both have been set. This struct must be initialized by calling #MLSpatialAnchorQueryFilterInit before use. |
| out uint |resultsCount||






-----------

### override [MLResult](/unity-api/api/UnityEngine.XR.MagicLeap/UnityEngine.XR.MagicLeap.MLResult.md) TryGetResult {#override--trygetresult}

```csharp
public override MLResult TryGetResult(
    out Result result
)
```


**Parameters**

| Type | Name  | Description  | 
|--|--|--|
| out [Result](/unity-api/api/UnityEngine.XR.MagicLeap/MLAnchors/Request/UnityEngine.XR.MagicLeap.MLAnchors.Request.Result.md) |result||






-----------

### [MLResult](/unity-api/api/UnityEngine.XR.MagicLeap/UnityEngine.XR.MagicLeap.MLResult.md) TryGetResult {#mlresult-trygetresult}

```csharp
public MLResult TryGetResult(
    int firstIndex,
    int lastIndex,
    out Result result
)
```


**Parameters**

| Type | Name  | Description  | 
|--|--|--|
| int |firstIndex||
| int |lastIndex||
| out [Result](/unity-api/api/UnityEngine.XR.MagicLeap/MLAnchors/Request/UnityEngine.XR.MagicLeap.MLAnchors.Request.Result.md) |result||






-----------

## Protected Methods

### Dispose {#override-void-dispose}

```csharp
protected virtual override void Dispose(
    bool disposing
)
```


**Parameters**

| Type | Name  | Description  | 
|--|--|--|
| bool |disposing||




**Reimplements**: [Dispose](/unity-api/api/UnityEngine.XR.MagicLeap/UnityEngine.XR.MagicLeap.MLRequest.md#abstract-void-dispose)



-----------

