# SandboxV2CookFoodListLoopAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2CookFoodListItemView _itemViewPrefab`


## Methods

- `Void set_itemSelectEvent(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookFoodListLoopAdapter : LoopScrollAdapter`2
{
	private SandboxV2CookFoodListItemView _itemViewPrefab; // 0x58
	private Action`1 <itemSelectEvent>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 itemSelectEvent { get; set; }

	// RVA: 0x24c7a34 VA: 0x7594adfa34
	private Action`1 get_itemSelectEvent() { }
	// RVA: 0x24c7a9c VA: 0x7594adfa9c
	public Void set_itemSelectEvent(Action`1 value) { }
	// RVA: 0x24c7b20 VA: 0x7594adfb20
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x24c7c1c VA: 0x7594adfc1c
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, SandboxV2CookFoodListItemModel data) { }
	// RVA: 0x24c7dc4 VA: 0x7594adfdc4
	public Void .ctor() { }
}
```