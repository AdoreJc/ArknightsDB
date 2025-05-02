# ArchiveDisasterListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `SimpleLayoutContent _levelContent`

- `ArchiveDisasterLeftPanelView _leftPanelView`

- `ArchiveDisasterTypeItemAdapter _typeAdapter`

- `Boolean m_hasInited`

- `LevelItemAdapter m_levelAdapter`

- `ArchiveDisasterController <controller>k__BackingField`


## Properties

- `ArchiveDisasterController controller`


## Methods

- `ArchiveDisasterController get_controller()`

- `Void set_controller(ArchiveDisasterController)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDisasterListDataBinder : DataBinder`1
{
	private SimpleLayoutContent _levelContent; // 0x20
	private ArchiveDisasterLeftPanelView _leftPanelView; // 0x28
	private ArchiveDisasterTypeItemAdapter _typeAdapter; // 0x30
	private Boolean m_hasInited; // 0x38
	private List`1 m_cachedItemModels; // 0x40
	private LevelItemAdapter m_levelAdapter; // 0x48
	private ArchiveDisasterController <controller>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ArchiveDisasterController controller { get; set; }

	// RVA: 0x3048864 VA: 0x7595660864
	private ArchiveDisasterController get_controller() { }
	// RVA: 0x30488cc VA: 0x75956608cc
	public Void set_controller(ArchiveDisasterController value) { }
	// RVA: 0x3048950 VA: 0x7595660950
	public override Void OnValueChanged(DisasterProperty property) { }
	// RVA: 0x3048b00 VA: 0x7595660b00
	private Void _InitIfNot() { }
	// RVA: 0x3048ef4 VA: 0x7595660ef4
	public Void .ctor() { }
}
```