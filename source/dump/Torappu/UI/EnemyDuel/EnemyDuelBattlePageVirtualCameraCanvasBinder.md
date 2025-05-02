# EnemyDuelBattlePageVirtualCameraCanvasBinder

**Namespace:** `Torappu.UI.EnemyDuel`


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
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBattlePageVirtualCameraCanvasBinder : MonoBehaviour, IPageCameraMarker, IPageComponentMarker, IHotfixable
{
	private UIPageVirtualCamCanvasBinder _binder; // 0x18
	private static DelegateBridge __Hotfix0_get_binder; // 0x0
	private static DelegateBridge __Hotfix0_IsCollectable; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public UIPageVirtualCamCanvasBinder binder { get; }

	// RVA: 0x2988bdc VA: 0x7594fa0bdc
	public UIPageVirtualCamCanvasBinder get_binder() { }
	// RVA: 0x298963c VA: 0x7594fa163c
	public Boolean IsCollectable() { }
	// RVA: 0x29896a4 VA: 0x7594fa16a4
	public Void .ctor() { }
}
```