# Act1VAutoChessChessShopLevelCharItemCardViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessShopLevelCharItemType <itemType>k__BackingField`

- `String <chessSlotId>k__BackingField`

- `Int32 <chessShopLv>k__BackingField`

- `Act1VAutoChessShopCharChessCardViewModel <charCardViewModel>k__BackingField`

- `Act1VAutoChessShopCharChessDiyCardViewModel <diyCharCardViewModel>k__BackingField`

- `Act1VAutoChessShopQuickEditType <quickEditType>k__BackingField`

- `String m_actId`

- `Act1VAutoChessMultiCharSkillEquipEditItemViewModel m_equipEditItemViewModel`

- `Act1VAutoChessShopStatus m_cachedShopStatus`

- `Int32 m_cachedCurPlayerDiyCnt`

- `InputShowAndClickParams m_cachedCharCardShowAndClickParams`


## Properties

- `Act1VAutoChessShopLevelCharItemType itemType`

- `String chessSlotId`

- `Int32 chessShopLv`

- `Act1VAutoChessShopCharChessCardViewModel charCardViewModel`

- `Act1VAutoChessShopCharChessDiyCardViewModel diyCharCardViewModel`

- `Act1VAutoChessMultiCharSkillEquipEditItemViewModel equipEditItemViewModel`

- `Boolean showQuickEditInfos`

- `Boolean showNew`

- `Act1VAutoChessShopQuickEditType quickEditType`


## Methods

- `Act1VAutoChessShopLevelCharItemType get_itemType()`

- `Void set_itemType(Act1VAutoChessShopLevelCharItemType)`

- `String get_chessSlotId()`

- `Void set_chessSlotId(String)`

- `Int32 get_chessShopLv()`

- `Void set_chessShopLv(Int32)`

- `Act1VAutoChessShopCharChessCardViewModel get_charCardViewModel()`

- `Void set_charCardViewModel(Act1VAutoChessShopCharChessCardViewModel)`

- `Act1VAutoChessShopCharChessDiyCardViewModel get_diyCharCardViewModel()`

- `Void set_diyCharCardViewModel(Act1VAutoChessShopCharChessDiyCardViewModel)`

- `Act1VAutoChessMultiCharSkillEquipEditItemViewModel get_equipEditItemViewModel()`

- `Boolean get_showQuickEditInfos()`

- `Boolean get_showNew()`

- `Act1VAutoChessShopQuickEditType get_quickEditType()`

- `Void set_quickEditType(Act1VAutoChessShopQuickEditType)`

- `Void LoadCharCardData(String, Act1VAutoChessShopCharChessCardViewModel)`

- `Void LoadDiyCardData(String, Act1VAutoChessShopCharChessDiyCardViewModel)`

- `Void RefreshCharCardByPlayerData(Dictionary`2, ListDict`2, Dictionary`2)`

- `Void RefreshEditQuickEditType(Act1VAutoChessShopQuickEditType)`

- `Void RefreshCharCardSkillId(String)`

- `Void RefreshCharCardEquipId(String)`

- `Void RefreshCharCardIsNewTag(Boolean)`

- `Void RefreshDiyCardByPlayerData(Int32)`

- `Void RefreshCardByViewStatusChange(Act1VAutoChessShopStatus)`

- `Void RefreshCharCardSelectTag(Boolean)`

- `Int32 CompareTo(Act1VAutoChessChessShopLevelCharItemCardViewModel)`

- `InputShowAndClickParams _GenerateCharChessInputParams(Act1VAutoChessShopStatus)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopLevelCharItemCardViewModel : IHotfixable, IComparable`1
{
	private Act1VAutoChessShopLevelCharItemType <itemType>k__BackingField; // 0x10
	private String <chessSlotId>k__BackingField; // 0x18
	private Int32 <chessShopLv>k__BackingField; // 0x20
	private Act1VAutoChessShopCharChessCardViewModel <charCardViewModel>k__BackingField; // 0x28
	private Act1VAutoChessShopCharChessDiyCardViewModel <diyCharCardViewModel>k__BackingField; // 0x30
	private Act1VAutoChessShopQuickEditType <quickEditType>k__BackingField; // 0x38
	private String m_actId; // 0x40
	private Act1VAutoChessMultiCharSkillEquipEditItemViewModel m_equipEditItemViewModel; // 0x48
	private Act1VAutoChessShopStatus m_cachedShopStatus; // 0x50
	private Int32 m_cachedCurPlayerDiyCnt; // 0x54
	private InputShowAndClickParams m_cachedCharCardShowAndClickParams; // 0x58
	private static DelegateBridge __Hotfix0_get_itemType; // 0x0
	private static DelegateBridge __Hotfix0_set_itemType; // 0x8
	private static DelegateBridge __Hotfix0_get_chessSlotId; // 0x10
	private static DelegateBridge __Hotfix0_set_chessSlotId; // 0x18
	private static DelegateBridge __Hotfix0_get_chessShopLv; // 0x20
	private static DelegateBridge __Hotfix0_set_chessShopLv; // 0x28
	private static DelegateBridge __Hotfix0_get_charCardViewModel; // 0x30
	private static DelegateBridge __Hotfix0_set_charCardViewModel; // 0x38
	private static DelegateBridge __Hotfix0_get_diyCharCardViewModel; // 0x40
	private static DelegateBridge __Hotfix0_set_diyCharCardViewModel; // 0x48
	private static DelegateBridge __Hotfix0_get_equipEditItemViewModel; // 0x50
	private static DelegateBridge __Hotfix0_get_showQuickEditInfos; // 0x58
	private static DelegateBridge __Hotfix0_get_showNew; // 0x60
	private static DelegateBridge __Hotfix0_get_quickEditType; // 0x68
	private static DelegateBridge __Hotfix0_set_quickEditType; // 0x70
	private static DelegateBridge __Hotfix0_LoadCharCardData; // 0x78
	private static DelegateBridge __Hotfix0_LoadDiyCardData; // 0x80
	private static DelegateBridge __Hotfix0_RefreshCharCardByPlayerData; // 0x88
	private static DelegateBridge __Hotfix0_RefreshEditQuickEditType; // 0x90
	private static DelegateBridge __Hotfix0_RefreshCharCardSkillId; // 0x98
	private static DelegateBridge __Hotfix0_RefreshCharCardEquipId; // 0xa0
	private static DelegateBridge __Hotfix0_RefreshCharCardIsNewTag; // 0xa8
	private static DelegateBridge __Hotfix0_RefreshDiyCardByPlayerData; // 0xb0
	private static DelegateBridge __Hotfix0_RefreshCardByViewStatusChange; // 0xb8
	private static DelegateBridge __Hotfix0_RefreshCharCardSelectTag; // 0xc0
	private static DelegateBridge __Hotfix0_CompareTo; // 0xc8
	private static DelegateBridge __Hotfix0__GenerateCharChessInputParams; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public Act1VAutoChessShopLevelCharItemType itemType { get; set; }
	public String chessSlotId { get; set; }
	public Int32 chessShopLv { get; set; }
	public Act1VAutoChessShopCharChessCardViewModel charCardViewModel { get; set; }
	public Act1VAutoChessShopCharChessDiyCardViewModel diyCharCardViewModel { get; set; }
	public Act1VAutoChessMultiCharSkillEquipEditItemViewModel equipEditItemViewModel { get; }
	public Boolean showQuickEditInfos { get; }
	public Boolean showNew { get; }
	public Act1VAutoChessShopQuickEditType quickEditType { get; set; }

	// RVA: 0x331c9f4 VA: 0x75959349f4
	public Act1VAutoChessShopLevelCharItemType get_itemType() { }
	// RVA: 0x33298b4 VA: 0x75959418b4
	private Void set_itemType(Act1VAutoChessShopLevelCharItemType value) { }
	// RVA: 0x331ca5c VA: 0x7595934a5c
	public String get_chessSlotId() { }
	// RVA: 0x3329930 VA: 0x7595941930
	private Void set_chessSlotId(String value) { }
	// RVA: 0x331cac4 VA: 0x7595934ac4
	public Int32 get_chessShopLv() { }
	// RVA: 0x33299b4 VA: 0x75959419b4
	public Void set_chessShopLv(Int32 value) { }
	// RVA: 0x331cd80 VA: 0x7595934d80
	public Act1VAutoChessShopCharChessCardViewModel get_charCardViewModel() { }
	// RVA: 0x3329a30 VA: 0x7595941a30
	private Void set_charCardViewModel(Act1VAutoChessShopCharChessCardViewModel value) { }
	// RVA: 0x331cbb0 VA: 0x7595934bb0
	public Act1VAutoChessShopCharChessDiyCardViewModel get_diyCharCardViewModel() { }
	// RVA: 0x3329ab4 VA: 0x7595941ab4
	private Void set_diyCharCardViewModel(Act1VAutoChessShopCharChessDiyCardViewModel value) { }
	// RVA: 0x331d0fc VA: 0x75959350fc
	public Act1VAutoChessMultiCharSkillEquipEditItemViewModel get_equipEditItemViewModel() { }
	// RVA: 0x331cfe8 VA: 0x7595934fe8
	public Boolean get_showQuickEditInfos() { }
	// RVA: 0x331cde8 VA: 0x7595934de8
	public Boolean get_showNew() { }
	// RVA: 0x3329b38 VA: 0x7595941b38
	public Act1VAutoChessShopQuickEditType get_quickEditType() { }
	// RVA: 0x3329ba0 VA: 0x7595941ba0
	private Void set_quickEditType(Act1VAutoChessShopQuickEditType value) { }
	// RVA: 0x3329c1c VA: 0x7595941c1c
	public Void LoadCharCardData(String actId, Act1VAutoChessShopCharChessCardViewModel cardViewModel) { }
	// RVA: 0x3329dac VA: 0x7595941dac
	public Void LoadDiyCardData(String actId, Act1VAutoChessShopCharChessDiyCardViewModel diyCardViewModel) { }
	// RVA: 0x3329edc VA: 0x7595941edc
	public Void RefreshCharCardByPlayerData(Dictionary`2 charChessDataDict, ListDict`2 charShopChessDatas, Dictionary`2 chessPlayerDataPool) { }
	// RVA: 0x332a138 VA: 0x7595942138
	public Void RefreshEditQuickEditType(Act1VAutoChessShopQuickEditType editType) { }
	// RVA: 0x332a1f8 VA: 0x75959421f8
	public Void RefreshCharCardSkillId(String newSkillId) { }
	// RVA: 0x332a2d0 VA: 0x75959422d0
	public Void RefreshCharCardEquipId(String newEquipId) { }
	// RVA: 0x332a3a8 VA: 0x75959423a8
	public Void RefreshCharCardIsNewTag(Boolean isNew) { }
	// RVA: 0x332a464 VA: 0x7595942464
	public Void RefreshDiyCardByPlayerData(Int32 curPlayerDiyCnt) { }
	// RVA: 0x332a510 VA: 0x7595942510
	public Void RefreshCardByViewStatusChange(Act1VAutoChessShopStatus shopStatus) { }
	// RVA: 0x332a760 VA: 0x7595942760
	public Void RefreshCharCardSelectTag(Boolean isSelected) { }
	// RVA: 0x332a81c VA: 0x759594281c
	public Int32 CompareTo(Act1VAutoChessChessShopLevelCharItemCardViewModel other) { }
	// RVA: 0x332a63c VA: 0x759594263c
	private InputShowAndClickParams _GenerateCharChessInputParams(Act1VAutoChessShopStatus shopStatus) { }
	// RVA: 0x332a9a0 VA: 0x75959429a0
	public Void .ctor() { }
}
```