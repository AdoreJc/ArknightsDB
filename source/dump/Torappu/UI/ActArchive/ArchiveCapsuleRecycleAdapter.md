# ArchiveCapsuleRecycleAdapter

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveCapsuleListItemView _itemPrefab`

- `ArchiveCapsuleController <controller>k__BackingField`

- `String <selectItemId>k__BackingField`


## Properties

- `ArchiveCapsuleController controller`

- `String selectItemId`


## Methods

- `ArchiveCapsuleController get_controller()`

- `Void set_controller(ArchiveCapsuleController)`

- `String get_selectItemId()`

- `Void set_selectItemId(String)`

- `Sprite LoadItemIcon(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveCapsuleRecycleAdapter : RecycleLoopScrollAdapter`2
{
	private ArchiveCapsuleListItemView _itemPrefab; // 0x68
	private ArchiveCapsuleController <controller>k__BackingField; // 0x70
	private String <selectItemId>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_get_selectItemId; // 0x10
	private static DelegateBridge __Hotfix0_set_selectItemId; // 0x18
	private static DelegateBridge __Hotfix0_LoadItemIcon; // 0x20
	private static DelegateBridge __Hotfix0_UpdateView; // 0x28
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private ArchiveCapsuleController controller { get; set; }
	private String selectItemId { get; set; }

	// RVA: 0x303cf44 VA: 0x7595654f44
	private ArchiveCapsuleController get_controller() { }
	// RVA: 0x303ad18 VA: 0x7595652d18
	public Void set_controller(ArchiveCapsuleController value) { }
	// RVA: 0x303cfac VA: 0x7595654fac
	private String get_selectItemId() { }
	// RVA: 0x303b450 VA: 0x7595653450
	public Void set_selectItemId(String value) { }
	// RVA: 0x303b31c VA: 0x759565331c
	public Sprite LoadItemIcon(String capsuleId) { }
	// RVA: 0x303d014 VA: 0x7595655014
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, CapsuleItemModel data) { }
	// RVA: 0x303d180 VA: 0x7595655180
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x303d294 VA: 0x7595655294
	public Void .ctor() { }
}
```