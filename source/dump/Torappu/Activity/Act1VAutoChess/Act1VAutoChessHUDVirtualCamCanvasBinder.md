# Act1VAutoChessHUDVirtualCamCanvasBinder

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `UIPageVirtualCamCanvasBinder _binder`


## Properties

- `UIPageVirtualCamCanvasBinder binder`


## Methods

- `UIPageVirtualCamCanvasBinder get_binder()`

- `Boolean IsCollectable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDVirtualCamCanvasBinder : MonoBehaviour, IPageCameraMarker, IPageComponentMarker, IHotfixable
{
	private UIPageVirtualCamCanvasBinder _binder; // 0x18
	private static DelegateBridge __Hotfix0_get_binder; // 0x0
	private static DelegateBridge __Hotfix0_IsCollectable; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public UIPageVirtualCamCanvasBinder binder { get; }

	// RVA: 0x33813a0 VA: 0x75959993a0
	public UIPageVirtualCamCanvasBinder get_binder() { }
	// RVA: 0x3381408 VA: 0x7595999408
	public Boolean IsCollectable() { }
	// RVA: 0x3381470 VA: 0x7595999470
	public Void .ctor() { }
}
```