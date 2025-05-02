# ArchiveAchievementDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveAchievementItemAdapter _adapter`

- `TwoStateToggle _toggleListWhetherEmpty`

- `ArchiveAchievementGotFilterView _gotFilterView`

- `ArchiveAchievementController m_controller`

- `Boolean m_hasInited`


## Properties

- `ArchiveAchievementController controller`


## Methods

- `ArchiveAchievementController get_controller()`

- `Void set_controller(ArchiveAchievementController)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveAchievementDataBinder : DataBinder`1
{
	private ArchiveAchievementItemAdapter _adapter; // 0x20
	private TwoStateToggle _toggleListWhetherEmpty; // 0x28
	private List`1 _filters; // 0x30
	private List`1 _rarityCountViews; // 0x38
	private ArchiveAchievementGotFilterView _gotFilterView; // 0x40
	private List`1 m_filters; // 0x48
	private ArchiveAchievementController m_controller; // 0x50
	private Boolean m_hasInited; // 0x58
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public ArchiveAchievementController controller { get; set; }

	// RVA: 0x3014ac0 VA: 0x759562cac0
	public ArchiveAchievementController get_controller() { }
	// RVA: 0x3011560 VA: 0x7595629560
	public Void set_controller(ArchiveAchievementController value) { }
	// RVA: 0x3014eb4 VA: 0x759562ceb4
	public override Void OnValueChanged(ArchiveAchievementProperty property) { }
	// RVA: 0x3014b28 VA: 0x759562cb28
	private Void _InitIfNot() { }
	// RVA: 0x3015550 VA: 0x759562d550
	public Void .ctor() { }
}
```