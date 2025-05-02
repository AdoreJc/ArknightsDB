# Act1VAutoChessChessShopLevelCharGroupListViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Int32 m_charListRefreshSequenceNum`

- `Int32 m_detailCharListRefreshSequenceNum`

- `Int32 m_quickEditCharListRefreshSequenceNum`


## Properties

- `Int32 charListRefreshSequenceNum`

- `Int32 detailCharListRefreshSequenceNum`

- `Int32 quickEditCharListRefreshSequenceNum`


## Methods

- `Int32 get_charListRefreshSequenceNum()`

- `Int32 get_detailCharListRefreshSequenceNum()`

- `Int32 get_quickEditCharListRefreshSequenceNum()`

- `Void LoadData(String, ActivityAutoChessVerify1Data, Dictionary`2, Int32)`

- `Void RefreshPlayerData(String, Act1VAutoChessShopStatus, Boolean, Dictionary`2, Dictionary`2)`

- `Void RefreshViewStatus(Act1VAutoChessShopStatus)`

- `Void RefreshViewQuickEditType(Act1VAutoChessShopQuickEditType)`

- `Boolean RefreshMultiEditChessSelectSkillId(String, Int32, String, String)`

- `Boolean RefreshMultiEditChessSelectModuleId(String, Int32, String, String)`

- `Void RefreshChessSelectTag(String, String)`

- `Act1VAutoChessShopCharChessCardViewModel GetCharItemCardViewModel(Int32, String)`

- `Int32 TryGetCharChessCardViewModel(Int32, String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopLevelCharGroupListViewModel : IHotfixable
{
	private List`1 m_charGroupViewList; // 0x10
	private Int32 m_charListRefreshSequenceNum; // 0x18
	private Int32 m_detailCharListRefreshSequenceNum; // 0x1c
	private Int32 m_quickEditCharListRefreshSequenceNum; // 0x20
	private static DelegateBridge __Hotfix0_get_charGroupViewList; // 0x0
	private static DelegateBridge __Hotfix0_get_charListRefreshSequenceNum; // 0x8
	private static DelegateBridge __Hotfix0_get_detailCharListRefreshSequenceNum; // 0x10
	private static DelegateBridge __Hotfix0_get_quickEditCharListRefreshSequenceNum; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x28
	private static DelegateBridge __Hotfix0_RefreshViewStatus; // 0x30
	private static DelegateBridge __Hotfix0_RefreshViewQuickEditType; // 0x38
	private static DelegateBridge __Hotfix0_RefreshMultiEditChessSelectSkillId; // 0x40
	private static DelegateBridge __Hotfix0_RefreshMultiEditChessSelectModuleId; // 0x48
	private static DelegateBridge __Hotfix0_RefreshChessSelectTag; // 0x50
	private static DelegateBridge __Hotfix0_GetCharItemCardViewModel; // 0x58
	private static DelegateBridge __Hotfix0_TryGetCharChessCardViewModel; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public List`1 charGroupViewList { get; }
	public Int32 charListRefreshSequenceNum { get; }
	public Int32 detailCharListRefreshSequenceNum { get; }
	public Int32 quickEditCharListRefreshSequenceNum { get; }

	// RVA: 0x332cf20 VA: 0x7595944f20
	public List`1 get_charGroupViewList() { }
	// RVA: 0x332cf88 VA: 0x7595944f88
	public Int32 get_charListRefreshSequenceNum() { }
	// RVA: 0x331ddf8 VA: 0x7595935df8
	public Int32 get_detailCharListRefreshSequenceNum() { }
	// RVA: 0x3323998 VA: 0x759593b998
	public Int32 get_quickEditCharListRefreshSequenceNum() { }
	// RVA: 0x332cff0 VA: 0x7595944ff0
	public Void LoadData(String actId, ActivityAutoChessVerify1Data actData, Dictionary`2 chessPool, Int32 iSequenceNum) { }
	// RVA: 0x332d32c VA: 0x759594532c
	public Void RefreshPlayerData(String actId, Act1VAutoChessShopStatus status, Boolean needResetCharChessList, Dictionary`2 chessPool, Dictionary`2 shopLv2DiyCharCntDict) { }
	// RVA: 0x332d4a8 VA: 0x75959454a8
	public Void RefreshViewStatus(Act1VAutoChessShopStatus shopStatus) { }
	// RVA: 0x332d594 VA: 0x7595945594
	public Void RefreshViewQuickEditType(Act1VAutoChessShopQuickEditType editType) { }
	// RVA: 0x332d680 VA: 0x7595945680
	public Boolean RefreshMultiEditChessSelectSkillId(String actId, Int32 chessLevel, String chessId, String skillId) { }
	// RVA: 0x332d7d0 VA: 0x75959457d0
	public Boolean RefreshMultiEditChessSelectModuleId(String actId, Int32 chessLevel, String chessId, String moduleId) { }
	// RVA: 0x332d920 VA: 0x7595945920
	public Void RefreshChessSelectTag(String actId, String curSelectChessId) { }
	// RVA: 0x332da24 VA: 0x7595945a24
	public Act1VAutoChessShopCharChessCardViewModel GetCharItemCardViewModel(Int32 chessLevel, String chessId) { }
	// RVA: 0x332db4c VA: 0x7595945b4c
	public Int32 TryGetCharChessCardViewModel(Int32 chessLevel, String charId, out Act1VAutoChessShopCharChessCardViewModel cardViewModel) { }
	// RVA: 0x332dca0 VA: 0x7595945ca0
	public Void .ctor() { }
}
```