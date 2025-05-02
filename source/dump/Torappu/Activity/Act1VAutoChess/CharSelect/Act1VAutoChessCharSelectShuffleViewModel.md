# Act1VAutoChessCharSelectShuffleViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `ProfessionCategory m_profFilter`

- `Boolean <showFilterPanel>k__BackingField`


## Properties

- `Boolean showFilterPanel`


## Methods

- `Boolean get_showFilterPanel()`

- `Void set_showFilterPanel(Boolean)`

- `Boolean SetFilter(ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1VAutoChessCharSelectShuffleViewModel : TemplateShuffleViewModelBase`1
{
	private ProfessionCategory m_profFilter; // 0x10
	private Boolean <showFilterPanel>k__BackingField; // 0x14
	private static DelegateBridge __Hotfix0_get_showFilterPanel; // 0x0
	private static DelegateBridge __Hotfix0_set_showFilterPanel; // 0x8
	private static DelegateBridge __Hotfix0_get_sortType; // 0x10
	private static DelegateBridge __Hotfix0_get_profFilter; // 0x18
	private static DelegateBridge __Hotfix0_SetFilter; // 0x20
	private static DelegateBridge __Hotfix0_OnSortChar; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean showFilterPanel { get; set; }
	public override CharacterSortType sortType { get; }
	public override ProfessionCategory profFilter { get; }

	// RVA: 0x338d190 VA: 0x75959a5190
	public Boolean get_showFilterPanel() { }
	// RVA: 0x338d3d8 VA: 0x75959a53d8
	public Void set_showFilterPanel(Boolean value) { }
	// RVA: 0x338d6f8 VA: 0x75959a56f8
	public override CharacterSortType get_sortType() { }
	// RVA: 0x338d760 VA: 0x75959a5760
	public override ProfessionCategory get_profFilter() { }
	// RVA: 0x338d344 VA: 0x75959a5344
	public Boolean SetFilter(ProfessionCategory filter) { }
	// RVA: 0x338d7c8 VA: 0x75959a57c8
	protected override Int32 OnSortChar(Act1VAutoChessCharSelectCardViewModel a, Act1VAutoChessCharSelectCardViewModel b) { }
	// RVA: 0x338d9c0 VA: 0x75959a59c0
	public Void .ctor() { }
}
```