# Act1VAutoChessShopCharChessCardViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <chessId>k__BackingField`

- `AutoChessCharType <chessType>k__BackingField`

- `Int32 <chessLevel>k__BackingField`

- `Int32 <selectType>k__BackingField`

- `Int32 <shopLevelSortId>k__BackingField`

- `CharQuery <charQuery>k__BackingField`

- `Act1VAutoChessCharShopChessData <originChessShopData>k__BackingField`

- `Act1VAutoChessCharChessStatusData <charChessNormalStatusData>k__BackingField`

- `Act1VAutoChessCharChessStatusData <charChessGoldenStatusData>k__BackingField`

- `EvolvePhase <goldenEvolvePhase>k__BackingField`

- `String <skillId>k__BackingField`

- `Int32 <skillIndex>k__BackingField`

- `String <skinId>k__BackingField`

- `String <currentEquip>k__BackingField`

- `Int32 <potentialRank>k__BackingField`

- `CharacterData m_charData`

- `String m_goldenChessId`

- `Act1VAutoChessCharShopChessData m_chessShopData`

- `Boolean m_isSelecting`

- `Boolean m_needShowBackupTag`

- `Boolean m_needShowAssistTag`

- `Boolean m_needShowSelectTag`

- `Boolean m_needShowDiyCancelTag`

- `Boolean m_needShowNewTag`

- `Boolean m_isClickable`

- `Boolean m_isNew`


## Properties

- `String chessId`

- `AutoChessCharType chessType`

- `Int32 chessLevel`

- `Int32 selectType`

- `Int32 shopLevelSortId`

- `CharQuery charQuery`

- `CharacterData charData`

- `Act1VAutoChessCharShopChessData chessShopData`

- `Act1VAutoChessCharShopChessData originChessShopData`

- `Act1VAutoChessCharChessStatusData charChessNormalStatusData`

- `Act1VAutoChessCharChessStatusData charChessGoldenStatusData`

- `EvolvePhase goldenEvolvePhase`

- `String skillId`

- `Int32 skillIndex`

- `String skinId`

- `String currentEquip`

- `Int32 potentialRank`

- `Boolean showSelectTag`

- `Boolean showBackupTag`

- `Boolean showAssistTag`

- `Boolean showNewTag`

- `Boolean showCancelDiy`

- `Boolean isClickable`


## Methods

- `String get_chessId()`

- `Void set_chessId(String)`

- `AutoChessCharType get_chessType()`

- `Void set_chessType(AutoChessCharType)`

- `Int32 get_chessLevel()`

- `Void set_chessLevel(Int32)`

- `Int32 get_selectType()`

- `Void set_selectType(Int32)`

- `Int32 get_shopLevelSortId()`

- `Void set_shopLevelSortId(Int32)`

- `CharQuery get_charQuery()`

- `Void set_charQuery(CharQuery)`

- `CharacterData get_charData()`

- `Act1VAutoChessCharShopChessData get_chessShopData()`

- `Act1VAutoChessCharShopChessData get_originChessShopData()`

- `Void set_originChessShopData(Act1VAutoChessCharShopChessData)`

- `Act1VAutoChessCharChessStatusData get_charChessNormalStatusData()`

- `Void set_charChessNormalStatusData(Act1VAutoChessCharChessStatusData)`

- `Act1VAutoChessCharChessStatusData get_charChessGoldenStatusData()`

- `Void set_charChessGoldenStatusData(Act1VAutoChessCharChessStatusData)`

- `EvolvePhase get_goldenEvolvePhase()`

- `Void set_goldenEvolvePhase(EvolvePhase)`

- `String get_skillId()`

- `Void set_skillId(String)`

- `Int32 get_skillIndex()`

- `Void set_skillIndex(Int32)`

- `String get_skinId()`

- `Void set_skinId(String)`

- `String get_currentEquip()`

- `Void set_currentEquip(String)`

- `Int32 get_potentialRank()`

- `Void set_potentialRank(Int32)`

- `Boolean get_showSelectTag()`

- `Boolean get_showBackupTag()`

- `Boolean get_showAssistTag()`

- `Boolean get_showNewTag()`

- `Boolean get_showCancelDiy()`

- `Boolean get_isClickable()`

- `Void LoadData(InputParams)`

- `Void _LoadChar(ICharInfo)`

- `Void UpdateChar(ICharInfo)`

- `Void RefreshSelectState(Boolean)`

- `Boolean SetSkillId(String)`

- `Boolean SetEquip(String)`

- `Void RefreshIsNewTag(Boolean)`

- `Void RefreshShowAndClickTags(InputShowAndClickParams)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessShopCharChessCardViewModel : IHotfixable
{
	private String <chessId>k__BackingField; // 0x10
	private AutoChessCharType <chessType>k__BackingField; // 0x18
	private Int32 <chessLevel>k__BackingField; // 0x1c
	private Int32 <selectType>k__BackingField; // 0x20
	private Int32 <shopLevelSortId>k__BackingField; // 0x24
	private CharQuery <charQuery>k__BackingField; // 0x28
	private Act1VAutoChessCharShopChessData <originChessShopData>k__BackingField; // 0x40
	private Act1VAutoChessCharChessStatusData <charChessNormalStatusData>k__BackingField; // 0x48
	private Act1VAutoChessCharChessStatusData <charChessGoldenStatusData>k__BackingField; // 0x50
	private EvolvePhase <goldenEvolvePhase>k__BackingField; // 0x58
	private String <skillId>k__BackingField; // 0x60
	private Int32 <skillIndex>k__BackingField; // 0x68
	private String <skinId>k__BackingField; // 0x70
	private String <currentEquip>k__BackingField; // 0x78
	private Int32 <potentialRank>k__BackingField; // 0x80
	private CharacterData m_charData; // 0x88
	private String m_goldenChessId; // 0x90
	private Act1VAutoChessCharShopChessData m_chessShopData; // 0x98
	private Boolean m_isSelecting; // 0xa0
	private Boolean m_needShowBackupTag; // 0xa1
	private Boolean m_needShowAssistTag; // 0xa2
	private Boolean m_needShowSelectTag; // 0xa3
	private Boolean m_needShowDiyCancelTag; // 0xa4
	private Boolean m_needShowNewTag; // 0xa5
	private Boolean m_isClickable; // 0xa6
	private Boolean m_isNew; // 0xa7
	private static DelegateBridge __Hotfix0_get_chessId; // 0x0
	private static DelegateBridge __Hotfix0_set_chessId; // 0x8
	private static DelegateBridge __Hotfix0_get_chessType; // 0x10
	private static DelegateBridge __Hotfix0_set_chessType; // 0x18
	private static DelegateBridge __Hotfix0_get_chessLevel; // 0x20
	private static DelegateBridge __Hotfix0_set_chessLevel; // 0x28
	private static DelegateBridge __Hotfix0_get_selectType; // 0x30
	private static DelegateBridge __Hotfix0_set_selectType; // 0x38
	private static DelegateBridge __Hotfix0_get_shopLevelSortId; // 0x40
	private static DelegateBridge __Hotfix0_set_shopLevelSortId; // 0x48
	private static DelegateBridge __Hotfix0_get_charQuery; // 0x50
	private static DelegateBridge __Hotfix0_set_charQuery; // 0x58
	private static DelegateBridge __Hotfix0_get_charData; // 0x60
	private static DelegateBridge __Hotfix0_get_chessShopData; // 0x68
	private static DelegateBridge __Hotfix0_get_originChessShopData; // 0x70
	private static DelegateBridge __Hotfix0_set_originChessShopData; // 0x78
	private static DelegateBridge __Hotfix0_get_charChessNormalStatusData; // 0x80
	private static DelegateBridge __Hotfix0_set_charChessNormalStatusData; // 0x88
	private static DelegateBridge __Hotfix0_get_charChessGoldenStatusData; // 0x90
	private static DelegateBridge __Hotfix0_set_charChessGoldenStatusData; // 0x98
	private static DelegateBridge __Hotfix0_get_goldenEvolvePhase; // 0xa0
	private static DelegateBridge __Hotfix0_set_goldenEvolvePhase; // 0xa8
	private static DelegateBridge __Hotfix0_get_skillId; // 0xb0
	private static DelegateBridge __Hotfix0_set_skillId; // 0xb8
	private static DelegateBridge __Hotfix0_get_skillIndex; // 0xc0
	private static DelegateBridge __Hotfix0_set_skillIndex; // 0xc8
	private static DelegateBridge __Hotfix0_get_skinId; // 0xd0
	private static DelegateBridge __Hotfix0_set_skinId; // 0xd8
	private static DelegateBridge __Hotfix0_get_currentEquip; // 0xe0
	private static DelegateBridge __Hotfix0_set_currentEquip; // 0xe8
	private static DelegateBridge __Hotfix0_get_potentialRank; // 0xf0
	private static DelegateBridge __Hotfix0_set_potentialRank; // 0xf8
	private static DelegateBridge __Hotfix0_get_showSelectTag; // 0x100
	private static DelegateBridge __Hotfix0_get_showBackupTag; // 0x108
	private static DelegateBridge __Hotfix0_get_showAssistTag; // 0x110
	private static DelegateBridge __Hotfix0_get_showNewTag; // 0x118
	private static DelegateBridge __Hotfix0_get_showCancelDiy; // 0x120
	private static DelegateBridge __Hotfix0_get_isClickable; // 0x128
	private static DelegateBridge __Hotfix0_LoadData; // 0x130
	private static DelegateBridge __Hotfix0__LoadChar; // 0x138
	private static DelegateBridge __Hotfix0_UpdateChar; // 0x140
	private static DelegateBridge __Hotfix0_RefreshSelectState; // 0x148
	private static DelegateBridge __Hotfix0_SetSkillId; // 0x150
	private static DelegateBridge __Hotfix0_SetEquip; // 0x158
	private static DelegateBridge __Hotfix0_RefreshIsNewTag; // 0x160
	private static DelegateBridge __Hotfix0_RefreshShowAndClickTags; // 0x168
	private static DelegateBridge _c__Hotfix0_ctor; // 0x170

	public String chessId { get; set; }
	public AutoChessCharType chessType { get; set; }
	public Int32 chessLevel { get; set; }
	public Int32 selectType { get; set; }
	public Int32 shopLevelSortId { get; set; }
	public CharQuery charQuery { get; set; }
	public CharacterData charData { get; }
	public Act1VAutoChessCharShopChessData chessShopData { get; }
	public Act1VAutoChessCharShopChessData originChessShopData { get; set; }
	public Act1VAutoChessCharChessStatusData charChessNormalStatusData { get; set; }
	public Act1VAutoChessCharChessStatusData charChessGoldenStatusData { get; set; }
	public EvolvePhase goldenEvolvePhase { get; set; }
	public String skillId { get; set; }
	public Int32 skillIndex { get; set; }
	public String skinId { get; set; }
	public String currentEquip { get; set; }
	public Int32 potentialRank { get; set; }
	public Boolean showSelectTag { get; }
	public Boolean showBackupTag { get; }
	public Boolean showAssistTag { get; }
	public Boolean showNewTag { get; }
	public Boolean showCancelDiy { get; }
	public Boolean isClickable { get; }

	// RVA: 0x3308ed0 VA: 0x7595920ed0
	public String get_chessId() { }
	// RVA: 0x330a20c VA: 0x759592220c
	private Void set_chessId(String value) { }
	// RVA: 0x330a290 VA: 0x7595922290
	public AutoChessCharType get_chessType() { }
	// RVA: 0x330a2f8 VA: 0x75959222f8
	private Void set_chessType(AutoChessCharType value) { }
	// RVA: 0x3309174 VA: 0x7595921174
	public Int32 get_chessLevel() { }
	// RVA: 0x330a374 VA: 0x7595922374
	private Void set_chessLevel(Int32 value) { }
	// RVA: 0x3309320 VA: 0x7595921320
	public Int32 get_selectType() { }
	// RVA: 0x330a3f0 VA: 0x75959223f0
	public Void set_selectType(Int32 value) { }
	// RVA: 0x330a46c VA: 0x759592246c
	public Int32 get_shopLevelSortId() { }
	// RVA: 0x330a4d4 VA: 0x75959224d4
	private Void set_shopLevelSortId(Int32 value) { }
	// RVA: 0x3309d8c VA: 0x7595921d8c
	public CharQuery get_charQuery() { }
	// RVA: 0x330a550 VA: 0x7595922550
	private Void set_charQuery(CharQuery value) { }
	// RVA: 0x3309c54 VA: 0x7595921c54
	public CharacterData get_charData() { }
	// RVA: 0x330a600 VA: 0x7595922600
	public Act1VAutoChessCharShopChessData get_chessShopData() { }
	// RVA: 0x330a668 VA: 0x7595922668
	public Act1VAutoChessCharShopChessData get_originChessShopData() { }
	// RVA: 0x330a6d0 VA: 0x75959226d0
	private Void set_originChessShopData(Act1VAutoChessCharShopChessData value) { }
	// RVA: 0x3309cbc VA: 0x7595921cbc
	public Act1VAutoChessCharChessStatusData get_charChessNormalStatusData() { }
	// RVA: 0x330a754 VA: 0x7595922754
	private Void set_charChessNormalStatusData(Act1VAutoChessCharChessStatusData value) { }
	// RVA: 0x3309d24 VA: 0x7595921d24
	public Act1VAutoChessCharChessStatusData get_charChessGoldenStatusData() { }
	// RVA: 0x330a7d8 VA: 0x75959227d8
	private Void set_charChessGoldenStatusData(Act1VAutoChessCharChessStatusData value) { }
	// RVA: 0x3309e84 VA: 0x7595921e84
	public EvolvePhase get_goldenEvolvePhase() { }
	// RVA: 0x330a85c VA: 0x759592285c
	public Void set_goldenEvolvePhase(EvolvePhase value) { }
	// RVA: 0x3309f54 VA: 0x7595921f54
	public String get_skillId() { }
	// RVA: 0x330a8d8 VA: 0x75959228d8
	private Void set_skillId(String value) { }
	// RVA: 0x330a95c VA: 0x759592295c
	public Int32 get_skillIndex() { }
	// RVA: 0x330a9c4 VA: 0x75959229c4
	private Void set_skillIndex(Int32 value) { }
	// RVA: 0x3309e1c VA: 0x7595921e1c
	public String get_skinId() { }
	// RVA: 0x330aa40 VA: 0x7595922a40
	private Void set_skinId(String value) { }
	// RVA: 0x3309fbc VA: 0x7595921fbc
	public String get_currentEquip() { }
	// RVA: 0x330aac4 VA: 0x7595922ac4
	private Void set_currentEquip(String value) { }
	// RVA: 0x3309eec VA: 0x7595921eec
	public Int32 get_potentialRank() { }
	// RVA: 0x330ab48 VA: 0x7595922b48
	private Void set_potentialRank(Int32 value) { }
	// RVA: 0x3309ae8 VA: 0x7595921ae8
	public Boolean get_showSelectTag() { }
	// RVA: 0x33099e0 VA: 0x75959219e0
	public Boolean get_showBackupTag() { }
	// RVA: 0x3309a64 VA: 0x7595921a64
	public Boolean get_showAssistTag() { }
	// RVA: 0x330abc4 VA: 0x7595922bc4
	public Boolean get_showNewTag() { }
	// RVA: 0x3309b68 VA: 0x7595921b68
	public Boolean get_showCancelDiy() { }
	// RVA: 0x3309bec VA: 0x7595921bec
	public Boolean get_isClickable() { }
	// RVA: 0x330ac44 VA: 0x7595922c44
	public Void LoadData(InputParams inputParams) { }
	// RVA: 0x330b080 VA: 0x7595923080
	private Void _LoadChar(ICharInfo charInfo) { }
	// RVA: 0x330b618 VA: 0x7595923618
	public Void UpdateChar(ICharInfo charInfo) { }
	// RVA: 0x330b698 VA: 0x7595923698
	public Void RefreshSelectState(Boolean isSelect) { }
	// RVA: 0x330b718 VA: 0x7595923718
	public Boolean SetSkillId(String newSkillId) { }
	// RVA: 0x330b858 VA: 0x7595923858
	public Boolean SetEquip(String newEquipId) { }
	// RVA: 0x330b904 VA: 0x7595923904
	public Void RefreshIsNewTag(Boolean isNew) { }
	// RVA: 0x330b984 VA: 0x7595923984
	public Void RefreshShowAndClickTags(InputShowAndClickParams param) { }
	// RVA: 0x330ba30 VA: 0x7595923a30
	public Void .ctor() { }
}
```