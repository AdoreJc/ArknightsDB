# ClimbTowerSquadEditStateBean

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `FocusParams focusParams`

- `PackedRuneData <runeData>k__BackingField`

- `ClimbTowerSingleLevelData <layerData>k__BackingField`

- `String <towerId>k__BackingField`

- `Int32 <coord>k__BackingField`

- `Boolean <isTutorialTower>k__BackingField`

- `Int64 <gameStartTs>k__BackingField`

- `Boolean <isHardMode>k__BackingField`


## Properties

- `PackedRuneData runeData`

- `ClimbTowerSingleLevelData layerData`

- `String towerId`

- `Int32 coord`

- `Boolean isTutorialTower`

- `Int64 gameStartTs`

- `Boolean isHardMode`

- `ClimbTowerSquadItemModel focusCharModel`

- `String stageId`


## Methods

- `Void set_charList(List`1)`

- `Void set_trapList(List`1)`

- `PackedRuneData get_runeData()`

- `Void set_runeData(PackedRuneData)`

- `ClimbTowerSingleLevelData get_layerData()`

- `Void set_layerData(ClimbTowerSingleLevelData)`

- `String get_towerId()`

- `Void set_towerId(String)`

- `Int32 get_coord()`

- `Void set_coord(Int32)`

- `Boolean get_isTutorialTower()`

- `Void set_isTutorialTower(Boolean)`

- `Int64 get_gameStartTs()`

- `Void set_gameStartTs(Int64)`

- `Boolean get_isHardMode()`

- `Void set_isHardMode(Boolean)`

- `ClimbTowerSquadItemModel get_focusCharModel()`

- `String get_stageId()`

- `ClimbTowerSquadItemModel FindSquadItemByCardId(Int32)`

- `Void InitData(Boolean, UIPage, List`1)`

- `Void _InitTrapAndRuneData(TowerCurrent, ClimbTowerSingleTowerData)`

- `Void UpdateEditStatus()`

- `SquadModel ParseBattleStartRequestSquad()`

- `Int32 _GetSkillIndexFromCardModel(CharacterCardViewModel)`

- `BattlePlayerData CreateBattlePlayerData(List`1, LevelData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadEditStateBean : IStateBean, IHotfixable
{
	private List`1 <charList>k__BackingField; // 0x10
	public FocusParams focusParams; // 0x18
	private List`1 <trapList>k__BackingField; // 0x28
	private PackedRuneData <runeData>k__BackingField; // 0x30
	private ClimbTowerSingleLevelData <layerData>k__BackingField; // 0x38
	private String <towerId>k__BackingField; // 0x40
	private Int32 <coord>k__BackingField; // 0x48
	private Boolean <isTutorialTower>k__BackingField; // 0x4c
	private Int64 <gameStartTs>k__BackingField; // 0x50
	private Boolean <isHardMode>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_charList; // 0x0
	private static DelegateBridge __Hotfix0_set_charList; // 0x8
	private static DelegateBridge __Hotfix0_get_trapList; // 0x10
	private static DelegateBridge __Hotfix0_set_trapList; // 0x18
	private static DelegateBridge __Hotfix0_get_runeData; // 0x20
	private static DelegateBridge __Hotfix0_set_runeData; // 0x28
	private static DelegateBridge __Hotfix0_get_layerData; // 0x30
	private static DelegateBridge __Hotfix0_set_layerData; // 0x38
	private static DelegateBridge __Hotfix0_get_towerId; // 0x40
	private static DelegateBridge __Hotfix0_set_towerId; // 0x48
	private static DelegateBridge __Hotfix0_get_coord; // 0x50
	private static DelegateBridge __Hotfix0_set_coord; // 0x58
	private static DelegateBridge __Hotfix0_get_isTutorialTower; // 0x60
	private static DelegateBridge __Hotfix0_set_isTutorialTower; // 0x68
	private static DelegateBridge __Hotfix0_get_gameStartTs; // 0x70
	private static DelegateBridge __Hotfix0_set_gameStartTs; // 0x78
	private static DelegateBridge __Hotfix0_get_isHardMode; // 0x80
	private static DelegateBridge __Hotfix0_set_isHardMode; // 0x88
	private static DelegateBridge __Hotfix0_get_focusCharModel; // 0x90
	private static DelegateBridge __Hotfix0_get_stageId; // 0x98
	private static DelegateBridge __Hotfix0_FindSquadItemByCardId; // 0xa0
	private static DelegateBridge __Hotfix0_InitData; // 0xa8
	private static DelegateBridge __Hotfix0__InitTrapAndRuneData; // 0xb0
	private static DelegateBridge __Hotfix0_UpdateEditStatus; // 0xb8
	private static DelegateBridge __Hotfix0_CreateSquadToStartBattle; // 0xc0
	private static DelegateBridge __Hotfix0_ParseBattleStartRequestSquad; // 0xc8
	private static DelegateBridge __Hotfix0__GetSkillIndexFromCardModel; // 0xd0
	private static DelegateBridge __Hotfix0_CreateProfessionSkillPart; // 0xd8
	private static DelegateBridge __Hotfix0_CreateGivenTrapInfos; // 0xe0
	private static DelegateBridge __Hotfix0_CreateBattlePlayerData; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	public List`1 charList { get; set; }
	public List`1 trapList { get; set; }
	public PackedRuneData runeData { get; set; }
	public ClimbTowerSingleLevelData layerData { get; set; }
	public String towerId { get; set; }
	public Int32 coord { get; set; }
	public Boolean isTutorialTower { get; set; }
	public Int64 gameStartTs { get; set; }
	public Boolean isHardMode { get; set; }
	public ClimbTowerSquadItemModel focusCharModel { get; }
	public String stageId { get; }

	// RVA: 0x2cbb09c VA: 0x75952d309c
	public List`1 get_charList() { }
	// RVA: 0x2cbf344 VA: 0x75952d7344
	private Void set_charList(List`1 value) { }
	// RVA: 0x2cbf3c8 VA: 0x75952d73c8
	public List`1 get_trapList() { }
	// RVA: 0x2cbf430 VA: 0x75952d7430
	private Void set_trapList(List`1 value) { }
	// RVA: 0x2cbe83c VA: 0x75952d683c
	public PackedRuneData get_runeData() { }
	// RVA: 0x2cbf4b4 VA: 0x75952d74b4
	private Void set_runeData(PackedRuneData value) { }
	// RVA: 0x2cbd794 VA: 0x75952d5794
	public ClimbTowerSingleLevelData get_layerData() { }
	// RVA: 0x2cbf538 VA: 0x75952d7538
	private Void set_layerData(ClimbTowerSingleLevelData value) { }
	// RVA: 0x2cbd7fc VA: 0x75952d57fc
	public String get_towerId() { }
	// RVA: 0x2cbf5bc VA: 0x75952d75bc
	private Void set_towerId(String value) { }
	// RVA: 0x2cbd864 VA: 0x75952d5864
	public Int32 get_coord() { }
	// RVA: 0x2cbf640 VA: 0x75952d7640
	private Void set_coord(Int32 value) { }
	// RVA: 0x2cbb034 VA: 0x75952d3034
	public Boolean get_isTutorialTower() { }
	// RVA: 0x2cbf6bc VA: 0x75952d76bc
	private Void set_isTutorialTower(Boolean value) { }
	// RVA: 0x2cbb21c VA: 0x75952d321c
	public Int64 get_gameStartTs() { }
	// RVA: 0x2cbf73c VA: 0x75952d773c
	private Void set_gameStartTs(Int64 value) { }
	// RVA: 0x2cbee30 VA: 0x75952d6e30
	public Boolean get_isHardMode() { }
	// RVA: 0x2cbf7b8 VA: 0x75952d77b8
	private Void set_isHardMode(Boolean value) { }
	// RVA: 0x2cbb104 VA: 0x75952d3104
	public ClimbTowerSquadItemModel get_focusCharModel() { }
	// RVA: 0x2cbe200 VA: 0x75952d6200
	public String get_stageId() { }
	// RVA: 0x2cbc8b8 VA: 0x75952d48b8
	public ClimbTowerSquadItemModel FindSquadItemByCardId(Int32 cardId) { }
	// RVA: 0x2cba944 VA: 0x75952d2944
	public Void InitData(Boolean isTutorial, UIPage page, List`1 predefinedCharList) { }
	// RVA: 0x2cbfaf0 VA: 0x75952d7af0
	private Void _InitTrapAndRuneData(TowerCurrent playerTower, ClimbTowerSingleTowerData towerData) { }
	// RVA: 0x2cbb624 VA: 0x75952d3624
	public Void UpdateEditStatus() { }
	// RVA: 0x2cbd2dc VA: 0x75952d52dc
	public SquadItemStruct[] CreateSquadToStartBattle() { }
	// RVA: 0x2cbd4d4 VA: 0x75952d54d4
	public SquadModel ParseBattleStartRequestSquad() { }
	// RVA: 0x2cc0200 VA: 0x75952d8200
	private Int32 _GetSkillIndexFromCardModel(CharacterCardViewModel cardViewModel) { }
	// RVA: 0x2cbd8cc VA: 0x75952d58cc
	public List`1 CreateProfessionSkillPart() { }
	// RVA: 0x2cbdf88 VA: 0x75952d5f88
	public List`1 CreateGivenTrapInfos() { }
	// RVA: 0x2cbe2a8 VA: 0x75952d62a8
	public BattlePlayerData CreateBattlePlayerData(List`1 squadSlots, LevelData levelData) { }
	// RVA: 0x2cbeb80 VA: 0x75952d6b80
	public Void .ctor() { }
}
```