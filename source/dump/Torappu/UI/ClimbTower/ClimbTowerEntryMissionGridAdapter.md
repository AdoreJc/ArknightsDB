# ClimbTowerEntryMissionGridAdapter

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerEntryMissionItemView _itemPrefab`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `Void set_onMissionItemClicked(Action`1)`

- `UIPage get_page()`

- `Void set_page(UIPage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryMissionGridAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private ClimbTowerEntryMissionItemView _itemPrefab; // 0x68
	private Action`1 <onMissionItemClicked>k__BackingField; // 0x70
	private UIPage <page>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onMissionItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onMissionItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_page; // 0x10
	private static DelegateBridge __Hotfix0_set_page; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onMissionItemClicked { get; set; }
	private UIPage page { get; set; }

	// RVA: 0x2c681f4 VA: 0x75952801f4
	private Action`1 get_onMissionItemClicked() { }
	// RVA: 0x2c6825c VA: 0x759528025c
	public Void set_onMissionItemClicked(Action`1 value) { }
	// RVA: 0x2c682e0 VA: 0x75952802e0
	private UIPage get_page() { }
	// RVA: 0x2c68348 VA: 0x7595280348
	public Void set_page(UIPage value) { }
	// RVA: 0x2c683cc VA: 0x75952803cc
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, ClimbTowerEntryMissionItemViewModel data) { }
	// RVA: 0x2c689d4 VA: 0x75952809d4
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x2c68acc VA: 0x7595280acc
	public Void .ctor() { }
}
```