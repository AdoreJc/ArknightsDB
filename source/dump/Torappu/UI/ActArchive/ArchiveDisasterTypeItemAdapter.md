# ArchiveDisasterTypeItemAdapter

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _prefab`

- `ArchiveDisasterController <controller>k__BackingField`

- `String <selectTypeId>k__BackingField`

- `Boolean <showSwitchAnim>k__BackingField`


## Properties

- `ArchiveDisasterController controller`

- `String selectTypeId`

- `Boolean showSwitchAnim`


## Methods

- `ArchiveDisasterController get_controller()`

- `Void set_controller(ArchiveDisasterController)`

- `Void set_dataSource(List`1)`

- `String get_selectTypeId()`

- `Void set_selectTypeId(String)`

- `Boolean get_showSwitchAnim()`

- `Void set_showSwitchAnim(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDisasterTypeItemAdapter : RecycleLoopScrollAdapter
{
	private GameObject _prefab; // 0x58
	private ArchiveDisasterController <controller>k__BackingField; // 0x60
	private List`1 <dataSource>k__BackingField; // 0x68
	private String <selectTypeId>k__BackingField; // 0x70
	private Boolean <showSwitchAnim>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_get_dataSource; // 0x10
	private static DelegateBridge __Hotfix0_set_dataSource; // 0x18
	private static DelegateBridge __Hotfix0_get_selectTypeId; // 0x20
	private static DelegateBridge __Hotfix0_set_selectTypeId; // 0x28
	private static DelegateBridge __Hotfix0_get_showSwitchAnim; // 0x30
	private static DelegateBridge __Hotfix0_set_showSwitchAnim; // 0x38
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x40
	private static DelegateBridge __Hotfix0_UpdateView; // 0x48
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private ArchiveDisasterController controller { get; set; }
	private List`1 dataSource { get; set; }
	private String selectTypeId { get; set; }
	private Boolean showSwitchAnim { get; set; }
	public override Int32 totalCount { get; }

	// RVA: 0x304bc60 VA: 0x7595663c60
	private ArchiveDisasterController get_controller() { }
	// RVA: 0x3048bd0 VA: 0x7595660bd0
	public Void set_controller(ArchiveDisasterController value) { }
	// RVA: 0x304bcc8 VA: 0x7595663cc8
	private List`1 get_dataSource() { }
	// RVA: 0x3048d58 VA: 0x7595660d58
	public Void set_dataSource(List`1 value) { }
	// RVA: 0x304bd30 VA: 0x7595663d30
	private String get_selectTypeId() { }
	// RVA: 0x3048c54 VA: 0x7595660c54
	public Void set_selectTypeId(String value) { }
	// RVA: 0x304bd98 VA: 0x7595663d98
	private Boolean get_showSwitchAnim() { }
	// RVA: 0x3048cd8 VA: 0x7595660cd8
	public Void set_showSwitchAnim(Boolean value) { }
	// RVA: 0x304be00 VA: 0x7595663e00
	public override Int32 get_totalCount() { }
	// RVA: 0x304be84 VA: 0x7595663e84
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x304c000 VA: 0x7595664000
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x304c124 VA: 0x7595664124
	public Void .ctor() { }
}
```