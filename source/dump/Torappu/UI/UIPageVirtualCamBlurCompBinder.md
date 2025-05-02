# UIPageVirtualCamBlurCompBinder

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform m_container`


## Methods

- `MgrBuilder GetCompDlgMgrBuilder()`

- `Void BindCamera(CameraWrapper)`

- `Void UnBindCamera()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPageVirtualCamBlurCompBinder : IPageVirtualCamBinder, IHotfixable
{
	private RectTransform m_container; // 0x10
	private List`1 m_blurOnlyCameras; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetCompDlgMgrBuilder; // 0x8
	private static DelegateBridge __Hotfix0_BindCamera; // 0x10
	private static DelegateBridge __Hotfix0_UnBindCamera; // 0x18


	// RVA: 0x215a8c4 VA: 0x75947728c4
	public Void .ctor(RectTransform dialogContainer) { }
	// RVA: 0x215a9ac VA: 0x75947729ac
	public MgrBuilder GetCompDlgMgrBuilder() { }
	// RVA: 0x215aa30 VA: 0x7594772a30
	public Void BindCamera(CameraWrapper camera) { }
	// RVA: 0x215aab8 VA: 0x7594772ab8
	public Void UnBindCamera() { }
}
```