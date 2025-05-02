# ItemRepoApItemState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoItemDetailStateBean _stateBean`

- `ItemRepoUseApSupplyItem _useApItem`


## Methods

- `Void DismissToHome()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoApItemState : PopupFloatState
{
	private ItemRepoItemDetailStateBean _stateBean; // 0x70
	private ItemRepoUseApSupplyItem _useApItem; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_DismissToHome; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d1acd4 VA: 0x7595332cd4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d1ad3c VA: 0x7595332d3c
	protected override Void OnEnter() { }
	// RVA: 0x2d1adc8 VA: 0x7595332dc8
	public Void DismissToHome() { }
	// RVA: 0x2d1aed4 VA: 0x7595332ed4
	public Void .ctor() { }
	// RVA: 0x2d1af44 VA: 0x7595332f44
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```