# UIPageVirtualCamCanvasBinder

**Namespace:** `Torappu.UI`


## Fields

- `Canvas _canvas`


## Methods

- `Void BindCamera(CameraWrapper)`

- `Void UnBindCamera()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPageVirtualCamCanvasBinder : IPageVirtualCamBinder, IHotfixable
{
	private Canvas _canvas; // 0x10
	private static DelegateBridge __Hotfix0_BindCamera; // 0x0
	private static DelegateBridge __Hotfix0_UnBindCamera; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x215a674 VA: 0x7594772674
	public Void BindCamera(CameraWrapper cameraWrapper) { }
	// RVA: 0x215a78c VA: 0x759477278c
	public Void UnBindCamera() { }
	// RVA: 0x215a854 VA: 0x7594772854
	public Void .ctor() { }
}
```