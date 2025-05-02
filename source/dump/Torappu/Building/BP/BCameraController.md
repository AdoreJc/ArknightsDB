# BCameraController

**Namespace:** `Torappu.Building.BP`


## Fields

- `MobileTouchCamera _touchCamera`

- `Single _zoomXRatioFitC`

- `Single _defaultPositionX`


## Properties

- `Camera camera`

- `MobileTouchCamera touchCamera`

- `Single camZoom`

- `Single camZoomMin`

- `Single camZoomMax`

- `Vector2 boundaryMin`

- `Vector2 boundaryMax`

- `Boolean allowCameraDrag`


## Methods

- `Camera get_camera()`

- `MobileTouchCamera get_touchCamera()`

- `Single get_camZoom()`

- `Void set_camZoom(Single)`

- `Single get_camZoomMin()`

- `Void set_camZoomMin(Single)`

- `Single get_camZoomMax()`

- `Void set_camZoomMax(Single)`

- `Vector2 get_boundaryMin()`

- `Void set_boundaryMin(Vector2)`

- `Vector2 get_boundaryMax()`

- `Void set_boundaryMax(Vector2)`

- `Void ResetPosition()`

- `Void ResetCameraBoundaries()`

- `Boolean get_allowCameraDrag()`

- `Void set_allowCameraDrag(Boolean)`

- `Single CalcCamZoom(Vector2, ScaleType)`

- `Single _TangentVertFOV()`

- `Single _TangentHoriFOV()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BCameraController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, IHotfixable
{
	private MobileTouchCamera _touchCamera; // 0x18
	private Single _zoomXRatioFitC; // 0x20
	private Single _defaultPositionX; // 0x24
	private Nullable`1 m_tanFOV; // 0x28
	private static DelegateBridge __Hotfix0_get_camera; // 0x0
	private static DelegateBridge __Hotfix0_get_touchCamera; // 0x8
	private static DelegateBridge __Hotfix0_get_camZoom; // 0x10
	private static DelegateBridge __Hotfix0_set_camZoom; // 0x18
	private static DelegateBridge __Hotfix0_get_camZoomMin; // 0x20
	private static DelegateBridge __Hotfix0_set_camZoomMin; // 0x28
	private static DelegateBridge __Hotfix0_get_camZoomMax; // 0x30
	private static DelegateBridge __Hotfix0_set_camZoomMax; // 0x38
	private static DelegateBridge __Hotfix0_get_boundaryMin; // 0x40
	private static DelegateBridge __Hotfix0_set_boundaryMin; // 0x48
	private static DelegateBridge __Hotfix0_get_boundaryMax; // 0x50
	private static DelegateBridge __Hotfix0_set_boundaryMax; // 0x58
	private static DelegateBridge __Hotfix0_ResetPosition; // 0x60
	private static DelegateBridge __Hotfix0_ResetCameraBoundaries; // 0x68
	private static DelegateBridge __Hotfix0_get_allowCameraDrag; // 0x70
	private static DelegateBridge __Hotfix0_set_allowCameraDrag; // 0x78
	private static DelegateBridge __Hotfix0_CalcCamZoom; // 0x80
	private static DelegateBridge __Hotfix0__TangentVertFOV; // 0x88
	private static DelegateBridge __Hotfix0__TangentHoriFOV; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public Camera camera { get; }
	public MobileTouchCamera touchCamera { get; }
	public Single camZoom { get; set; }
	public Single camZoomMin { get; set; }
	public Single camZoomMax { get; set; }
	public Vector2 boundaryMin { get; set; }
	public Vector2 boundaryMax { get; set; }
	public Boolean allowCameraDrag { get; set; }

	// RVA: 0x3d12588 VA: 0x759632a588
	public Camera get_camera() { }
	// RVA: 0x3d125fc VA: 0x759632a5fc
	public MobileTouchCamera get_touchCamera() { }
	// RVA: 0x3d12664 VA: 0x759632a664
	public Single get_camZoom() { }
	// RVA: 0x3d126d8 VA: 0x759632a6d8
	public Void set_camZoom(Single value) { }
	// RVA: 0x3d12764 VA: 0x759632a764
	public Single get_camZoomMin() { }
	// RVA: 0x3d127d8 VA: 0x759632a7d8
	public Void set_camZoomMin(Single value) { }
	// RVA: 0x3d12860 VA: 0x759632a860
	public Single get_camZoomMax() { }
	// RVA: 0x3d128d4 VA: 0x759632a8d4
	public Void set_camZoomMax(Single value) { }
	// RVA: 0x3d1295c VA: 0x759632a95c
	public Vector2 get_boundaryMin() { }
	// RVA: 0x3d129cc VA: 0x759632a9cc
	public Void set_boundaryMin(Vector2 value) { }
	// RVA: 0x3d12a5c VA: 0x759632aa5c
	public Vector2 get_boundaryMax() { }
	// RVA: 0x3d12acc VA: 0x759632aacc
	public Void set_boundaryMax(Vector2 value) { }
	// RVA: 0x3d12b5c VA: 0x759632ab5c
	public Void ResetPosition() { }
	// RVA: 0x3d12c08 VA: 0x759632ac08
	public Void ResetCameraBoundaries() { }
	// RVA: 0x3d12c7c VA: 0x759632ac7c
	public Boolean get_allowCameraDrag() { }
	// RVA: 0x3d12cf0 VA: 0x759632acf0
	public Void set_allowCameraDrag(Boolean value) { }
	// RVA: 0x3d12d90 VA: 0x759632ad90
	public Single CalcCamZoom(Vector2 viewPortSize, ScaleType scaleType) { }
	// RVA: 0x3d12f44 VA: 0x759632af44
	private Single _TangentVertFOV() { }
	// RVA: 0x3d12e84 VA: 0x759632ae84
	private Single _TangentHoriFOV() { }
	// RVA: 0x3d13058 VA: 0x759632b058
	public Void .ctor() { }
}
```