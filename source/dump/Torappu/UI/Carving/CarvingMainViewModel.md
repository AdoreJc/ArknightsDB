# CarvingMainViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `GameState gameState`

- `CarvingMainShopViewModel shopViewModel`

- `CarvingCardListViewModel cardListViewModel`

- `CarvingMainBoardModel boardViewModel`

- `CarvingMainChallengeTaskViewModel challengeTaskViewModel`

- `CarvingMainProcessModel processModel`

- `Boolean isProcessing`

- `String currRoundId`

- `Int32 firstLoadSeqNum`

- `Int32 enterBoardSeqNum`

- `String m_actId`

- `Act35SideData m_actData`

- `CarvingMainCardDetailViewModel m_cardDetailViewModel`


## Properties

- `CarvingMainCardDetailViewModel cardDetailViewModel`


## Methods

- `CarvingMainCardDetailViewModel get_cardDetailViewModel()`

- `Void LoadData(String)`

- `Void UpdateData(Boolean)`

- `Void ShopSelectSlot()`

- `Void ShopSelectCard(Int32)`

- `Void SelectHandCard(String)`

- `Void GoProcessing(List`1, Int32)`

- `Boolean TryProcessNextFrame()`

- `Boolean CheckIsBonusFrame()`

- `Boolean CheckIsTaskFrame()`

- `Void EndProcessing()`

- `Void UnSelectAllCard()`

- `Void SetChallengeTaskFinished(Boolean)`

- `Void NotifyEnterBoard()`

- `Void NotifyFirstLoad()`

- `CarvingMainCardViewModel _GetSelectedCardViewModel()`

- `Void _UpdateRoundId(PlayerAct35SideCarving)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainViewModel : IHotfixable
{
	public GameState gameState; // 0x10
	public CarvingMainShopViewModel shopViewModel; // 0x18
	public CarvingCardListViewModel cardListViewModel; // 0x20
	public CarvingMainBoardModel boardViewModel; // 0x28
	public CarvingMainChallengeTaskViewModel challengeTaskViewModel; // 0x30
	public CarvingMainProcessModel processModel; // 0x38
	public Boolean isProcessing; // 0x40
	public String currRoundId; // 0x48
	public Int32 firstLoadSeqNum; // 0x50
	public Int32 enterBoardSeqNum; // 0x54
	private String m_actId; // 0x58
	private Act35SideData m_actData; // 0x60
	private CarvingMainCardDetailViewModel m_cardDetailViewModel; // 0x68
	private static DelegateBridge __Hotfix0_get_cardDetailViewModel; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x10
	private static DelegateBridge __Hotfix0_ShopSelectSlot; // 0x18
	private static DelegateBridge __Hotfix0_ShopSelectCard; // 0x20
	private static DelegateBridge __Hotfix0_SelectHandCard; // 0x28
	private static DelegateBridge __Hotfix0_GoProcessing; // 0x30
	private static DelegateBridge __Hotfix0_TryProcessNextFrame; // 0x38
	private static DelegateBridge __Hotfix0_CheckIsBonusFrame; // 0x40
	private static DelegateBridge __Hotfix0_CheckIsTaskFrame; // 0x48
	private static DelegateBridge __Hotfix0_EndProcessing; // 0x50
	private static DelegateBridge __Hotfix0_UnSelectAllCard; // 0x58
	private static DelegateBridge __Hotfix0_SetChallengeTaskFinished; // 0x60
	private static DelegateBridge __Hotfix0_NotifyEnterBoard; // 0x68
	private static DelegateBridge __Hotfix0_NotifyFirstLoad; // 0x70
	private static DelegateBridge __Hotfix0__GetSelectedCardViewModel; // 0x78
	private static DelegateBridge __Hotfix0__UpdateRoundId; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public CarvingMainCardDetailViewModel cardDetailViewModel { get; }

	// RVA: 0x2dbe474 VA: 0x75953d6474
	public CarvingMainCardDetailViewModel get_cardDetailViewModel() { }
	// RVA: 0x2dbe590 VA: 0x75953d6590
	public Void LoadData(String actId) { }
	// RVA: 0x2dbe7fc VA: 0x75953d67fc
	public Void UpdateData(Boolean noNeedReloadCard) { }
	// RVA: 0x2dbea48 VA: 0x75953d6a48
	public Void ShopSelectSlot() { }
	// RVA: 0x2dbeae0 VA: 0x75953d6ae0
	public Void ShopSelectCard(Int32 pos) { }
	// RVA: 0x2dbeb94 VA: 0x75953d6b94
	public Void SelectHandCard(String cardId) { }
	// RVA: 0x2dbec2c VA: 0x75953d6c2c
	public Void GoProcessing(List`1 frames, Int32 fromScore) { }
	// RVA: 0x2dbecd0 VA: 0x75953d6cd0
	public Boolean TryProcessNextFrame() { }
	// RVA: 0x2dbed44 VA: 0x75953d6d44
	public Boolean CheckIsBonusFrame() { }
	// RVA: 0x2dbede0 VA: 0x75953d6de0
	public Boolean CheckIsTaskFrame() { }
	// RVA: 0x2dbee7c VA: 0x75953d6e7c
	public Void EndProcessing() { }
	// RVA: 0x2dbe77c VA: 0x75953d677c
	public Void UnSelectAllCard() { }
	// RVA: 0x2dbeee4 VA: 0x75953d6ee4
	public Void SetChallengeTaskFinished(Boolean isTaskFinished) { }
	// RVA: 0x2dbef70 VA: 0x75953d6f70
	public Void NotifyEnterBoard() { }
	// RVA: 0x2dbefe0 VA: 0x75953d6fe0
	public Void NotifyFirstLoad() { }
	// RVA: 0x2dbe500 VA: 0x75953d6500
	private CarvingMainCardViewModel _GetSelectedCardViewModel() { }
	// RVA: 0x2dbe934 VA: 0x75953d6934
	private Void _UpdateRoundId(PlayerAct35SideCarving playerData) { }
	// RVA: 0x2dbf050 VA: 0x75953d7050
	public Void .ctor() { }
}
```