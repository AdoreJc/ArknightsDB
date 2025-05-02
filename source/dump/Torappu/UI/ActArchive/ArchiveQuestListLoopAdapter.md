# ArchiveQuestListLoopAdapter

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveQuestListItemView _itemPrefab`

- `Boolean <initRender>k__BackingField`


## Properties

- `Boolean initRender`


## Methods

- `Void set_itemSelectEvent(Action`1)`

- `Boolean get_initRender()`

- `Void set_initRender(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestListLoopAdapter : LoopScrollAdapter`2
{
	private ArchiveQuestListItemView _itemPrefab; // 0x58
	private Action`1 <itemSelectEvent>k__BackingField; // 0x60
	private Boolean <initRender>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_initRender; // 0x10
	private static DelegateBridge __Hotfix0_set_initRender; // 0x18
	private static DelegateBridge __Hotfix0_CreateView; // 0x20
	private static DelegateBridge __Hotfix0_UpdateView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 itemSelectEvent { get; set; }
	private Boolean initRender { get; set; }

	// RVA: 0x3074650 VA: 0x759568c650
	private Action`1 get_itemSelectEvent() { }
	// RVA: 0x30746b8 VA: 0x759568c6b8
	public Void set_itemSelectEvent(Action`1 value) { }
	// RVA: 0x307473c VA: 0x759568c73c
	private Boolean get_initRender() { }
	// RVA: 0x30747a4 VA: 0x759568c7a4
	public Void set_initRender(Boolean value) { }
	// RVA: 0x3074824 VA: 0x759568c824
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x30748f4 VA: 0x759568c8f4
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, ViewParam data) { }
	// RVA: 0x3074aa4 VA: 0x759568caa4
	public Void .ctor() { }
}
```