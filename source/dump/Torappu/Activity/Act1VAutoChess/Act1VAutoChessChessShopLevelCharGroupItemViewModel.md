# Act1VAutoChessChessShopLevelCharGroupItemViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Int32 <groupLevel>k__BackingField`

- `Act1VAutoChessShopLevelTagViewModel <levelTagViewModel>k__BackingField`

- `Act1VAutoChessShopLevelDisplayData m_cachedShopLevelDisplayData`


## Properties

- `Int32 groupLevel`

- `Act1VAutoChessShopLevelTagViewModel levelTagViewModel`


## Methods

- `Int32 get_groupLevel()`

- `Void set_groupLevel(Int32)`

- `Act1VAutoChessShopLevelTagViewModel get_levelTagViewModel()`

- `Void set_levelTagViewModel(Act1VAutoChessShopLevelTagViewModel)`

- `Void LoadData(String, Act1VAutoChessShopLevelDisplayData, ListDict`2, Dictionary`2, Dictionary`2)`

- `Void RefreshByPlayerData(String, Boolean, Act1VAutoChessShopStatus, Dictionary`2, Dictionary`2)`

- `Void RefreshDataByShopStatus(Act1VAutoChessShopStatus)`

- `Void RefreshQuickEditType(Act1VAutoChessShopQuickEditType)`

- `Boolean RefreshChessMultiEditSelectSkillId(String, String, String)`

- `Boolean RefreshChessMultiEditSelectModuleId(String, String, String)`

- `Void RefreshCharCardSelectTag(String, String)`

- `Act1VAutoChessShopCharChessCardViewModel GetCharItemCardViewModel(String)`

- `Int32 GetCharItemCardViewModelWithCharId(String, out)`

- `Void _ResetLevelCharItemCardList(String, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopLevelCharGroupItemViewModel : IHotfixable
{
	private Int32 <groupLevel>k__BackingField; // 0x10
	private Act1VAutoChessShopLevelTagViewModel <levelTagViewModel>k__BackingField; // 0x18
	private List`1 m_levelCharItemCardViewModelList; // 0x20
	private Act1VAutoChessShopLevelDisplayData m_cachedShopLevelDisplayData; // 0x28
	private ListDict`2 m_cachedCharShopChessDatas; // 0x30
	private Dictionary`2 m_cachedCharChessDataDict; // 0x38
	private static DelegateBridge __Hotfix0_get_groupLevel; // 0x0
	private static DelegateBridge __Hotfix0_set_groupLevel; // 0x8
	private static DelegateBridge __Hotfix0_get_levelTagViewModel; // 0x10
	private static DelegateBridge __Hotfix0_set_levelTagViewModel; // 0x18
	private static DelegateBridge __Hotfix0_get_levelCharItemCardViewModelList; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_RefreshByPlayerData; // 0x30
	private static DelegateBridge __Hotfix0_RefreshDataByShopStatus; // 0x38
	private static DelegateBridge __Hotfix0_RefreshQuickEditType; // 0x40
	private static DelegateBridge __Hotfix0_RefreshChessMultiEditSelectSkillId; // 0x48
	private static DelegateBridge __Hotfix0_RefreshChessMultiEditSelectModuleId; // 0x50
	private static DelegateBridge __Hotfix0_RefreshCharCardSelectTag; // 0x58
	private static DelegateBridge __Hotfix0_GetCharItemCardViewModel; // 0x60
	private static DelegateBridge __Hotfix0_GetCharItemCardViewModelWithCharId; // 0x68
	private static DelegateBridge __Hotfix0__ResetLevelCharItemCardList; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Int32 groupLevel { get; set; }
	public Act1VAutoChessShopLevelTagViewModel levelTagViewModel { get; set; }
	public List`1 levelCharItemCardViewModelList { get; }

	// RVA: 0x332b50c VA: 0x759594350c
	public Int32 get_groupLevel() { }
	// RVA: 0x332b574 VA: 0x7595943574
	private Void set_groupLevel(Int32 value) { }
	// RVA: 0x332b5f0 VA: 0x75959435f0
	public Act1VAutoChessShopLevelTagViewModel get_levelTagViewModel() { }
	// RVA: 0x332b658 VA: 0x7595943658
	private Void set_levelTagViewModel(Act1VAutoChessShopLevelTagViewModel value) { }
	// RVA: 0x332b6dc VA: 0x75959436dc
	public List`1 get_levelCharItemCardViewModelList() { }
	// RVA: 0x332b744 VA: 0x7595943744
	public Void LoadData(String actId, Act1VAutoChessShopLevelDisplayData displayData, ListDict`2 charShopChessDatas, Dictionary`2 charChessDataDict, Dictionary`2 chessPool) { }
	// RVA: 0x332be84 VA: 0x7595943e84
	public Void RefreshByPlayerData(String actId, Boolean needResetList, Act1VAutoChessShopStatus status, Dictionary`2 chessPool, Dictionary`2 shopLv2DiyCharCntDict) { }
	// RVA: 0x332c04c VA: 0x759594404c
	public Void RefreshDataByShopStatus(Act1VAutoChessShopStatus shopStatus) { }
	// RVA: 0x332c14c VA: 0x759594414c
	public Void RefreshQuickEditType(Act1VAutoChessShopQuickEditType editType) { }
	// RVA: 0x332c238 VA: 0x7595944238
	public Boolean RefreshChessMultiEditSelectSkillId(String actId, String chessId, String skillId) { }
	// RVA: 0x332c3b4 VA: 0x75959443b4
	public Boolean RefreshChessMultiEditSelectModuleId(String actId, String chessId, String equipId) { }
	// RVA: 0x332c530 VA: 0x7595944530
	public Void RefreshCharCardSelectTag(String actId, String curSelectingChessId) { }
	// RVA: 0x332c68c VA: 0x759594468c
	public Act1VAutoChessShopCharChessCardViewModel GetCharItemCardViewModel(String chessId) { }
	// RVA: 0x332c7d0 VA: 0x75959447d0
	public Int32 GetCharItemCardViewModelWithCharId(String charId, out Act1VAutoChessShopCharChessCardViewModel card) { }
	// RVA: 0x332b928 VA: 0x7595943928
	private Void _ResetLevelCharItemCardList(String actId, Dictionary`2 chessPool) { }
	// RVA: 0x332c944 VA: 0x7595944944
	public Void .ctor() { }
}
```