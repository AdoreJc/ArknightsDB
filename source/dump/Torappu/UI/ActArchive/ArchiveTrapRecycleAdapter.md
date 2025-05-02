# ArchiveTrapRecycleAdapter

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveTrapListItemView _itemPrefab`

- `ArchiveTrapController <controller>k__BackingField`

- `String <selectItemId>k__BackingField`


## Properties

- `ArchiveTrapController controller`

- `String selectItemId`


## Methods

- `ArchiveTrapController get_controller()`

- `Void set_controller(ArchiveTrapController)`

- `String get_selectItemId()`

- `Void set_selectItemId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTrapRecycleAdapter : RecycleLoopScrollAdapter`2
{
	private ArchiveTrapListItemView _itemPrefab; // 0x68
	private ArchiveTrapController <controller>k__BackingField; // 0x70
	private String <selectItemId>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_get_selectItemId; // 0x10
	private static DelegateBridge __Hotfix0_set_selectItemId; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private ArchiveTrapController controller { get; set; }
	private String selectItemId { get; set; }

	// RVA: 0x3090ca8 VA: 0x75956a8ca8
	private ArchiveTrapController get_controller() { }
	// RVA: 0x308efd0 VA: 0x75956a6fd0
	public Void set_controller(ArchiveTrapController value) { }
	// RVA: 0x3090d10 VA: 0x75956a8d10
	private String get_selectItemId() { }
	// RVA: 0x308f300 VA: 0x75956a7300
	public Void set_selectItemId(String value) { }
	// RVA: 0x3090d78 VA: 0x75956a8d78
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, TrapItemModel data) { }
	// RVA: 0x3090ea8 VA: 0x75956a8ea8
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x3090fbc VA: 0x75956a8fbc
	public Void .ctor() { }
}
```