# ArchiveRelicRecycleAdapter

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _groupPrefab`

- `Int32 m_totalCount`

- `ArchiveRelicController <controller>k__BackingField`

- `String <selectItemId>k__BackingField`

- `Boolean <showSwitchAnim>k__BackingField`


## Properties

- `ArchiveRelicController controller`

- `String selectItemId`

- `Boolean showSwitchAnim`


## Methods

- `ArchiveRelicController get_controller()`

- `Void set_controller(ArchiveRelicController)`

- `Void set_groupModel(List`1)`

- `String get_selectItemId()`

- `Void set_selectItemId(String)`

- `Boolean get_showSwitchAnim()`

- `Void set_showSwitchAnim(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveRelicRecycleAdapter : RecycleLoopScrollAdapter
{
	private GameObject _groupPrefab; // 0x58
	private Int32 m_totalCount; // 0x60
	private ArchiveRelicController <controller>k__BackingField; // 0x68
	private List`1 <groupModel>k__BackingField; // 0x70
	private String <selectItemId>k__BackingField; // 0x78
	private Boolean <showSwitchAnim>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_get_groupModel; // 0x10
	private static DelegateBridge __Hotfix0_set_groupModel; // 0x18
	private static DelegateBridge __Hotfix0_get_selectItemId; // 0x20
	private static DelegateBridge __Hotfix0_set_selectItemId; // 0x28
	private static DelegateBridge __Hotfix0_get_showSwitchAnim; // 0x30
	private static DelegateBridge __Hotfix0_set_showSwitchAnim; // 0x38
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x40
	private static DelegateBridge __Hotfix0_UpdateView; // 0x48
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private ArchiveRelicController controller { get; set; }
	private List`1 groupModel { get; set; }
	private String selectItemId { get; set; }
	private Boolean showSwitchAnim { get; set; }
	public override Int32 totalCount { get; }

	// RVA: 0x307da74 VA: 0x7595695a74
	private ArchiveRelicController get_controller() { }
	// RVA: 0x3078420 VA: 0x7595690420
	public Void set_controller(ArchiveRelicController value) { }
	// RVA: 0x307dadc VA: 0x7595695adc
	private List`1 get_groupModel() { }
	// RVA: 0x3078fc8 VA: 0x7595690fc8
	public Void set_groupModel(List`1 value) { }
	// RVA: 0x307db44 VA: 0x7595695b44
	private String get_selectItemId() { }
	// RVA: 0x3078dcc VA: 0x7595690dcc
	public Void set_selectItemId(String value) { }
	// RVA: 0x307dbac VA: 0x7595695bac
	private Boolean get_showSwitchAnim() { }
	// RVA: 0x3078e50 VA: 0x7595690e50
	public Void set_showSwitchAnim(Boolean value) { }
	// RVA: 0x307dc14 VA: 0x7595695c14
	public override Int32 get_totalCount() { }
	// RVA: 0x307dc98 VA: 0x7595695c98
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x307de14 VA: 0x7595695e14
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x307df38 VA: 0x7595695f38
	public Void .ctor() { }
}
```