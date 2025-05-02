# UniEquipLevelUpViewModel

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Int32 charInstId`

- `String templateId`

- `UniEquipData uniEquipData`

- `Int32 currentLevel`

- `Int32 targetLevel`

- `UniEquipLevelUpSwitchBoardViewModel switchBoardViewModel`

- `PlayerCharacter m_playerChar`

- `CharacterData m_charData`


## Properties

- `String equipId`

- `String equipName`


## Methods

- `Void set_requireViewModels(List`1)`

- `String get_equipId()`

- `String get_equipName()`

- `Void LoadData(PlayerCharacter, CharacterData, String)`

- `Void RefreshRequires()`

- `Boolean CheckIfTargetMaxLevel()`

- `Boolean TrySelectLevel(Int32)`

- `Void _GeneRequireViewModels()`

- `Void _GeneSwitchBoardViewModel(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipLevelUpViewModel : IHotfixable
{
	public Int32 charInstId; // 0x10
	public String templateId; // 0x18
	public UniEquipData uniEquipData; // 0x20
	public Int32 currentLevel; // 0x28
	public Int32 targetLevel; // 0x2c
	public UniEquipLevelUpSwitchBoardViewModel switchBoardViewModel; // 0x30
	private PlayerCharacter m_playerChar; // 0x38
	private CharacterData m_charData; // 0x40
	private List`1 <requireViewModels>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_set_requireViewModels; // 0x0
	private static DelegateBridge __Hotfix0_get_requireViewModels; // 0x8
	private static DelegateBridge __Hotfix0_get_equipId; // 0x10
	private static DelegateBridge __Hotfix0_get_equipName; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_RefreshRequires; // 0x28
	private static DelegateBridge __Hotfix0_CheckIfTargetMaxLevel; // 0x30
	private static DelegateBridge __Hotfix0_TrySelectLevel; // 0x38
	private static DelegateBridge __Hotfix0__GeneRequireViewModels; // 0x40
	private static DelegateBridge __Hotfix0__GeneSwitchBoardViewModel; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public List`1 requireViewModels { get; set; }
	public String equipId { get; }
	public String equipName { get; }

	// RVA: 0x2309990 VA: 0x7594921990
	private Void set_requireViewModels(List`1 value) { }
	// RVA: 0x2303144 VA: 0x759491b144
	public List`1 get_requireViewModels() { }
	// RVA: 0x23067d0 VA: 0x759491e7d0
	public String get_equipId() { }
	// RVA: 0x2302a94 VA: 0x759491aa94
	public String get_equipName() { }
	// RVA: 0x2306260 VA: 0x759491e260
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData, String equipId) { }
	// RVA: 0x2306418 VA: 0x759491e418
	public Void RefreshRequires() { }
	// RVA: 0x2309cf8 VA: 0x7594921cf8
	public Boolean CheckIfTargetMaxLevel() { }
	// RVA: 0x2306be4 VA: 0x759491ebe4
	public Boolean TrySelectLevel(Int32 selectLevel) { }
	// RVA: 0x2309a14 VA: 0x7594921a14
	private Void _GeneRequireViewModels() { }
	// RVA: 0x2309c20 VA: 0x7594921c20
	private Void _GeneSwitchBoardViewModel(Boolean ifNeedSelectTween) { }
	// RVA: 0x23061f0 VA: 0x759491e1f0
	public Void .ctor() { }
}
```