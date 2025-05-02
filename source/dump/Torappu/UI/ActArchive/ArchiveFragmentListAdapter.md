# ArchiveFragmentListAdapter

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveFragmentGroupView _itemPrefab`

- `Boolean <showSwitchAnim>k__BackingField`

- `String <selectedItemId>k__BackingField`


## Properties

- `Boolean showSwitchAnim`

- `String selectedItemId`


## Methods

- `Void set_onItemClicked(Action`1)`

- `Boolean get_showSwitchAnim()`

- `Void set_showSwitchAnim(Boolean)`

- `String get_selectedItemId()`

- `Void set_selectedItemId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveFragmentListAdapter : LoopScrollAdapter`2, IHotfixable
{
	private ArchiveFragmentGroupView _itemPrefab; // 0x58
	private Action`1 <onItemClicked>k__BackingField; // 0x60
	private Boolean <showSwitchAnim>k__BackingField; // 0x68
	private String <selectedItemId>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_showSwitchAnim; // 0x10
	private static DelegateBridge __Hotfix0_set_showSwitchAnim; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedItemId; // 0x20
	private static DelegateBridge __Hotfix0_set_selectedItemId; // 0x28
	private static DelegateBridge __Hotfix0_CreateView; // 0x30
	private static DelegateBridge __Hotfix0_UpdateView; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Action`1 onItemClicked { get; set; }
	private Boolean showSwitchAnim { get; set; }
	private String selectedItemId { get; set; }

	// RVA: 0x3054cac VA: 0x759566ccac
	private Action`1 get_onItemClicked() { }
	// RVA: 0x3054d14 VA: 0x759566cd14
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x3054d98 VA: 0x759566cd98
	private Boolean get_showSwitchAnim() { }
	// RVA: 0x3054e00 VA: 0x759566ce00
	public Void set_showSwitchAnim(Boolean value) { }
	// RVA: 0x3054e80 VA: 0x759566ce80
	private String get_selectedItemId() { }
	// RVA: 0x3054ee8 VA: 0x759566cee8
	public Void set_selectedItemId(String value) { }
	// RVA: 0x3054f6c VA: 0x759566cf6c
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x3055058 VA: 0x759566d058
	public override Void UpdateView(Int32 position, GameObject viewObj, ViewHolder holder, ArchiveFragmentGroupModel data) { }
	// RVA: 0x30551d0 VA: 0x759566d1d0
	public Void .ctor() { }
}
```