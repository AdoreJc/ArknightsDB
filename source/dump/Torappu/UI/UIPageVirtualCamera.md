# UIPageVirtualCamera

**Namespace:** `Torappu.UI`


## Fields

- `UIPageVirtualCamType m_cameraType`

- `CameraWrapper m_cameraWrapper`


## Methods

- `Void AttachCamera(UIPageCameraProvider)`

- `Void DetachCamera()`

- `Void Bind(IPageVirtualCamBinder)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPageVirtualCamera : IHotfixable
{
	private UIPageVirtualCamType m_cameraType; // 0x10
	private CameraWrapper m_cameraWrapper; // 0x18
	private List`1 m_binders; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_AttachCamera; // 0x8
	private static DelegateBridge __Hotfix0_DetachCamera; // 0x10
	private static DelegateBridge __Hotfix0_Bind; // 0x18


	// RVA: 0x215ab60 VA: 0x7594772b60
	public Void .ctor(UIPageVirtualCamType cameraType) { }
	// RVA: 0x215ac3c VA: 0x7594772c3c
	public Void AttachCamera(UIPageCameraProvider provider) { }
	// RVA: 0x215acf0 VA: 0x7594772cf0
	public Void DetachCamera() { }
	// RVA: 0x215aebc VA: 0x7594772ebc
	public Void Bind(IPageVirtualCamBinder binder) { }
}
```