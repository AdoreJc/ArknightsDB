# ArchiveTotemRecycleAdapter

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _itemPrefab`

- `ArchiveTotemController <controller>k__BackingField`

- `String <selectItemId>k__BackingField`

- `Boolean <showSwitchAnim>k__BackingField`


## Properties

- `ArchiveTotemController controller`

- `String selectItemId`

- `Boolean showSwitchAnim`


## Methods

- `ArchiveTotemController get_controller()`

- `Void set_controller(ArchiveTotemController)`

- `Void set_groupSource(List`1)`

- `String get_selectItemId()`

- `Void set_selectItemId(String)`

- `Boolean get_showSwitchAnim()`

- `Void set_showSwitchAnim(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTotemRecycleAdapter : RecycleLoopScrollAdapter
{
	private GameObject _itemPrefab; // 0x58
	private ArchiveTotemController <controller>k__BackingField; // 0x60
	private List`1 <groupSource>k__BackingField; // 0x68
	private String <selectItemId>k__BackingField; // 0x70
	private Boolean <showSwitchAnim>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_get_groupSource; // 0x10
	private static DelegateBridge __Hotfix0_set_groupSource; // 0x18
	private static DelegateBridge __Hotfix0_get_selectItemId; // 0x20
	private static DelegateBridge __Hotfix0_set_selectItemId; // 0x28
	private static DelegateBridge __Hotfix0_get_showSwitchAnim; // 0x30
	private static DelegateBridge __Hotfix0_set_showSwitchAnim; // 0x38
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x40
	private static DelegateBridge __Hotfix0_UpdateView; // 0x48
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private ArchiveTotemController controller { get; set; }
	private List`1 groupSource { get; set; }
	private String selectItemId { get; set; }
	private Boolean showSwitchAnim { get; set; }
	public override Int32 totalCount { get; }

	// RVA: 0x308dfd4 VA: 0x75956a5fd4
	private ArchiveTotemController get_controller() { }
	// RVA: 0x308add0 VA: 0x75956a2dd0
	public Void set_controller(ArchiveTotemController value) { }
	// RVA: 0x308e03c VA: 0x75956a603c
	private List`1 get_groupSource() { }
	// RVA: 0x308ab78 VA: 0x75956a2b78
	public Void set_groupSource(List`1 value) { }
	// RVA: 0x308e0a4 VA: 0x75956a60a4
	private String get_selectItemId() { }
	// RVA: 0x308ac64 VA: 0x75956a2c64
	public Void set_selectItemId(String value) { }
	// RVA: 0x308e10c VA: 0x75956a610c
	private Boolean get_showSwitchAnim() { }
	// RVA: 0x308ad50 VA: 0x75956a2d50
	public Void set_showSwitchAnim(Boolean value) { }
	// RVA: 0x308e174 VA: 0x75956a6174
	public override Int32 get_totalCount() { }
	// RVA: 0x308e1f8 VA: 0x75956a61f8
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x308e374 VA: 0x75956a6374
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x308e498 VA: 0x75956a6498
	public Void .ctor() { }
}
```