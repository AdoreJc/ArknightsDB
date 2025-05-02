# ItemRepoIssueVoucherItemListAdapter

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoIssueVoucherItemView _itemPrefab`


## Methods

- `Void set_onSelectItem(Func`3)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoIssueVoucherItemListAdapter : LoopScrollAdapter`2
{
	private ItemRepoIssueVoucherItemView _itemPrefab; // 0x58
	private Func`3 <onSelectItem>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onSelectItem; // 0x0
	private static DelegateBridge __Hotfix0_set_onSelectItem; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge __Hotfix0_CreateView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Func`3 onSelectItem { get; set; }

	// RVA: 0x2d33638 VA: 0x759534b638
	private Func`3 get_onSelectItem() { }
	// RVA: 0x2d336a0 VA: 0x759534b6a0
	public Void set_onSelectItem(Func`3 value) { }
	// RVA: 0x2d33724 VA: 0x759534b724
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, ItemRepoIssueVoucherItemViewModel data) { }
	// RVA: 0x2d33c2c VA: 0x759534bc2c
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2d33cfc VA: 0x759534bcfc
	public Void .ctor() { }
}
```