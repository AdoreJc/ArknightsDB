# CarvingMainController

**Namespace:** `Torappu.UI.Carving`


## Fields

- `StateEngine _stateEngine`

- `CarvingMainCardDetailView _cardDetailViewPrefab`

- `CarvingBoardView _boardView`

- `GameObject _panelHandCard`

- `GameObject _panelGoldCount`

- `CarvingAVGAdapter _tutorialAdapter`

- `CarvingMainChallengeTaskView _taskViewPrefab`

- `Transform _detailHolder`

- `Transform _taskHolder`

- `RectTransform _topBackMenu`

- `Text _topBackBtnTxt`

- `RectTransform _dialogContainer`

- `Single _processFrameDuration`

- `Single _processEndDuration`

- `GameObject _dragBlocker`

- `Boolean m_inited`

- `String m_actId`

- `CarvingMainProperty m_mainProperty`

- `CarvingMainCardDetailView m_cardDetailView`

- `CarvingMainChallengeTaskView m_taskView`

- `UICompDialogMgr m_dialogMgr`

- `Coroutine m_processCoroutine`

- `Boolean m_isBonusing`

- `Int32 m_createGameSeqNum`

- `Int32 m_handbookDialogInstId`

- `Int32 m_bonusDialogInstId`

- `Boolean m_isDragging`


## Properties

- `CarvingMainProperty mainProperty`

- `UICompDialogMgr dialogMgr`

- `DragHandler dragHandler`


## Methods

- `CarvingMainProperty get_mainProperty()`

- `UICompDialogMgr get_dialogMgr()`

- `DragHandler get_dragHandler()`

- `Void RegisterSlotViewListToDragHandler(List`1)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnShopSelectSlot()`

- `Void _OnShopSelectCard(Int32)`

- `Void _OnShopRefresh()`

- `Void _OnShopBuyGood()`

- `Void _BuySlot()`

- `Void _BuyCard()`

- `Void _OnShopToProcess()`

- `Void _OnCardSelected(String)`

- `Void _OnSlotClickedWhenHandSelected()`

- `Void _OnRegisterTutorialGO()`

- `Void _OnHandCardDraggedOut(String)`

- `Void _OnSlotCardDraggedOut(String)`

- `Void _OnDragCancelToHandCard(String)`

- `Void _OnDragCancelToSlotCard(ValueBundle)`

- `Void _OnTokenHoverSlotChanged(ValueBundle)`

- `Void _OnTokenMovedIntoSlot(String)`

- `Void _OnTokenHoverInHandAreaChanged(ValueBundle)`

- `Void OpenIntroDialogIfNeed(GameState, DialogueType, out)`

- `String GetCurrentTutorialTriggerKey(GameState)`

- `Void _OnClickProcessBtn()`

- `Void _OnClickCardDetailBlocker()`

- `Void _CheckChallengeInfo()`

- `Void _CheckHandbook(Boolean)`

- `Void _StartDragBlocker()`

- `Void _EndDragBlocker()`

- `Boolean CheckIsTriggerUnlockChallengeToast()`

- `Void _InitController()`

- `Boolean _CheckUIStable()`

- `IEnumerator _ProcessCoroutine(List`1, Int32)`

- `IEnumerator _TriggerBonus()`

- `Void _PlayCardBounceAudio(CarvingMainProcessModel)`

- `Void _OpenBonusDialog()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void OnClickBackBtn()`

- `Void SetBackBtnActive(Boolean, Boolean)`

- `Void <_OnShopToProcess>b__67_0(CarvingShopToProcessResponse)`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainController : PageSingleComponent, IValueMsgReceiver, ICompDialogCallBack
{
	private StateEngine _stateEngine; // 0x20
	private CarvingMainCardDetailView _cardDetailViewPrefab; // 0x28
	private CarvingBoardView _boardView; // 0x30
	private GameObject _panelHandCard; // 0x38
	private GameObject _panelGoldCount; // 0x40
	private CarvingAVGAdapter _tutorialAdapter; // 0x48
	private CarvingMainChallengeTaskView _taskViewPrefab; // 0x50
	private Transform _detailHolder; // 0x58
	private Transform _taskHolder; // 0x60
	private RectTransform _topBackMenu; // 0x68
	private Text _topBackBtnTxt; // 0x70
	private RectTransform _dialogContainer; // 0x78
	private Single _processFrameDuration; // 0x80
	private Single _processEndDuration; // 0x84
	private GameObject _dragBlocker; // 0x88
	private Boolean m_inited; // 0x90
	private String m_actId; // 0x98
	private CarvingMainProperty m_mainProperty; // 0xa0
	private CarvingMainCardDetailView m_cardDetailView; // 0xa8
	private CarvingMainChallengeTaskView m_taskView; // 0xb0
	private UICompDialogMgr m_dialogMgr; // 0xb8
	private Coroutine m_processCoroutine; // 0xc0
	private Boolean m_isBonusing; // 0xc8
	private Int32 m_createGameSeqNum; // 0xcc
	private Int32 m_handbookDialogInstId; // 0xd0
	private Int32 m_bonusDialogInstId; // 0xd4
	private Boolean m_isDragging; // 0xd8
	public const Int32 COMMON_CHECK_INFO; // 0x0
	public const Int32 COMMON_ON_CLICK_CARD_DETAIL_BLOCK; // 0x0
	public const Int32 COMMON_CHECK_HANDBOOK; // 0x0
	public const Int32 CHECK_HANDBOOK_DONOT_NEED_DARK; // 0x0
	public const Int32 CHECK_HANDBOOK_NEED_DARK; // 0x0
	public const Int32 SHOP_SELECT_SLOT; // 0x0
	public const Int32 SHOP_SELECT_CARD; // 0x0
	public const Int32 SHOP_REFRESH; // 0x0
	public const Int32 SHOP_BUY; // 0x0
	public const Int32 SHOP_TO_PROCESS; // 0x0
	public const Int32 BOARD_PROCESS; // 0x0
	public const Int32 BOARD_SLOT_CLICKED; // 0x0
	public const Int32 CARD_SELECTED; // 0x0
	public const Int32 MSG_HAND_CARD_DRAGGED_OUT; // 0x0
	public const Int32 MSG_SLOT_CARD_DRAGGED_OUT; // 0x0
	public const Int32 MSG_DRAG_CANCEL_TO_HAND_CARD; // 0x0
	public const Int32 MSG_DRAG_CANCEL_TO_SLOT_CARD; // 0x0
	public const Int32 MSG_SLOT_CLICKED_WHEN_HAND_SELECTED; // 0x0
	public const Int32 MSG_TOKEN_HOVER_SLOT_CHANGED; // 0x0
	public const Int32 MSG_TOKEN_HOVER_IN_HAND_AREA_CHANGED; // 0x0
	public const Int32 MSG_TOKEN_MOVED_INTO_SLOT; // 0x0
	public const Int32 MSG_START_DRAG_BLOCKER; // 0x0
	public const Int32 MSG_END_DRAG_BLOCKER; // 0x0
	public const Int32 MSG_TUTORIAL_REGISTER_GO; // 0x0
	private static DelegateBridge __Hotfix0_get_mainProperty; // 0x0
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x8
	private static DelegateBridge __Hotfix0_get_dragHandler; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge __Hotfix0_RegisterSlotViewListToDragHandler; // 0x28
	private static DelegateBridge __Hotfix0_OnMessage; // 0x30
	private static DelegateBridge __Hotfix0__OnShopSelectSlot; // 0x38
	private static DelegateBridge __Hotfix0__OnShopSelectCard; // 0x40
	private static DelegateBridge __Hotfix0__OnShopRefresh; // 0x48
	private static DelegateBridge __Hotfix0__OnShopBuyGood; // 0x50
	private static DelegateBridge __Hotfix0__BuySlot; // 0x58
	private static DelegateBridge __Hotfix0__BuyCard; // 0x60
	private static DelegateBridge __Hotfix0__OnShopToProcess; // 0x68
	private static DelegateBridge __Hotfix0__OnCardSelected; // 0x70
	private static DelegateBridge __Hotfix0__OnSlotClickedWhenHandSelected; // 0x78
	private static DelegateBridge __Hotfix0__OnRegisterTutorialGO; // 0x80
	private static DelegateBridge __Hotfix0__OnHandCardDraggedOut; // 0x88
	private static DelegateBridge __Hotfix0__OnSlotCardDraggedOut; // 0x90
	private static DelegateBridge __Hotfix0__OnDragCancelToHandCard; // 0x98
	private static DelegateBridge __Hotfix0__OnDragCancelToSlotCard; // 0xa0
	private static DelegateBridge __Hotfix0__OnTokenHoverSlotChanged; // 0xa8
	private static DelegateBridge __Hotfix0__OnTokenMovedIntoSlot; // 0xb0
	private static DelegateBridge __Hotfix0__OnTokenHoverInHandAreaChanged; // 0xb8
	private static DelegateBridge __Hotfix0_OpenIntroDialogIfNeed; // 0xc0
	private static DelegateBridge __Hotfix0_GetCurrentTutorialTriggerKey; // 0xc8
	private static DelegateBridge __Hotfix0__OnClickProcessBtn; // 0xd0
	private static DelegateBridge __Hotfix0__OnClickCardDetailBlocker; // 0xd8
	private static DelegateBridge __Hotfix0__CheckChallengeInfo; // 0xe0
	private static DelegateBridge __Hotfix0__CheckHandbook; // 0xe8
	private static DelegateBridge __Hotfix0__StartDragBlocker; // 0xf0
	private static DelegateBridge __Hotfix0__EndDragBlocker; // 0xf8
	private static DelegateBridge __Hotfix0_CheckIsTriggerUnlockChallengeToast; // 0x100
	private static DelegateBridge __Hotfix0__InitController; // 0x108
	private static DelegateBridge __Hotfix0__CheckUIStable; // 0x110
	private static DelegateBridge __Hotfix0__ProcessCoroutine; // 0x118
	private static DelegateBridge __Hotfix0__TriggerBonus; // 0x120
	private static DelegateBridge __Hotfix0__PlayCardBounceAudio; // 0x128
	private static DelegateBridge __Hotfix0__OpenBonusDialog; // 0x130
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x138
	private static DelegateBridge __Hotfix0_OnClickBackBtn; // 0x140
	private static DelegateBridge __Hotfix0_SetBackBtnActive; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150

	public CarvingMainProperty mainProperty { get; }
	public UICompDialogMgr dialogMgr { get; }
	public DragHandler dragHandler { get; }

	// RVA: 0x2dabe50 VA: 0x75953c3e50
	public CarvingMainProperty get_mainProperty() { }
	// RVA: 0x2daf78c VA: 0x75953c778c
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x2daf7f4 VA: 0x75953c77f4
	public DragHandler get_dragHandler() { }
	// RVA: 0x2daf868 VA: 0x75953c7868
	protected override Void OnCreate() { }
	// RVA: 0x2dafcb8 VA: 0x75953c7cb8
	protected override Void OnDestroy() { }
	// RVA: 0x2dafdb0 VA: 0x75953c7db0
	public Void RegisterSlotViewListToDragHandler(List`1 carvingSlots) { }
	// RVA: 0x2dafe3c VA: 0x75953c7e3c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2db053c VA: 0x75953c853c
	private Void _OnShopSelectSlot() { }
	// RVA: 0x2db060c VA: 0x75953c860c
	private Void _OnShopSelectCard(Int32 pos) { }
	// RVA: 0x2db0710 VA: 0x75953c8710
	private Void _OnShopRefresh() { }
	// RVA: 0x2db0a00 VA: 0x75953c8a00
	private Void _OnShopBuyGood() { }
	// RVA: 0x2db1d5c VA: 0x75953c9d5c
	private Void _BuySlot() { }
	// RVA: 0x2db1ff4 VA: 0x75953c9ff4
	private Void _BuyCard() { }
	// RVA: 0x2db0ae8 VA: 0x75953c8ae8
	private Void _OnShopToProcess() { }
	// RVA: 0x2db0d74 VA: 0x75953c8d74
	private Void _OnCardSelected(String cardId) { }
	// RVA: 0x2db19c4 VA: 0x75953c99c4
	private Void _OnSlotClickedWhenHandSelected() { }
	// RVA: 0x2db1b18 VA: 0x75953c9b18
	private Void _OnRegisterTutorialGO() { }
	// RVA: 0x2db0e78 VA: 0x75953c8e78
	private Void _OnHandCardDraggedOut(String cardId) { }
	// RVA: 0x2db0f80 VA: 0x75953c8f80
	private Void _OnSlotCardDraggedOut(String cardId) { }
	// RVA: 0x2db10a4 VA: 0x75953c90a4
	private Void _OnDragCancelToHandCard(String cardId) { }
	// RVA: 0x2db1198 VA: 0x75953c9198
	private Void _OnDragCancelToSlotCard(ValueBundle param) { }
	// RVA: 0x2db1304 VA: 0x75953c9304
	private Void _OnTokenHoverSlotChanged(ValueBundle param) { }
	// RVA: 0x2db1514 VA: 0x75953c9514
	private Void _OnTokenMovedIntoSlot(String cardId) { }
	// RVA: 0x2db1408 VA: 0x75953c9408
	private Void _OnTokenHoverInHandAreaChanged(ValueBundle param) { }
	// RVA: 0x2db22ac VA: 0x75953ca2ac
	public Void OpenIntroDialogIfNeed(GameState gameState, DialogueType dialogueType, out Int32 instId) { }
	// RVA: 0x2db24bc VA: 0x75953ca4bc
	public String GetCurrentTutorialTriggerKey(GameState gameState) { }
	// RVA: 0x2db1608 VA: 0x75953c9608
	private Void _OnClickProcessBtn() { }
	// RVA: 0x2db0218 VA: 0x75953c8218
	private Void _OnClickCardDetailBlocker() { }
	// RVA: 0x2db0178 VA: 0x75953c8178
	private Void _CheckChallengeInfo() { }
	// RVA: 0x2db02dc VA: 0x75953c82dc
	private Void _CheckHandbook(Boolean isNeedDarken) { }
	// RVA: 0x2db0448 VA: 0x75953c8448
	private Void _StartDragBlocker() { }
	// RVA: 0x2db04c4 VA: 0x75953c84c4
	private Void _EndDragBlocker() { }
	// RVA: 0x2db25c8 VA: 0x75953ca5c8
	public Boolean CheckIsTriggerUnlockChallengeToast() { }
	// RVA: 0x2daf9c0 VA: 0x75953c79c0
	private Void _InitController() { }
	// RVA: 0x2db1c14 VA: 0x75953c9c14
	private Boolean _CheckUIStable() { }
	// RVA: 0x2db26cc VA: 0x75953ca6cc
	private IEnumerator _ProcessCoroutine(List`1 frames, Int32 fromScore) { }
	// RVA: 0x2db27d0 VA: 0x75953ca7d0
	private IEnumerator _TriggerBonus() { }
	// RVA: 0x2db28a4 VA: 0x75953ca8a4
	private Void _PlayCardBounceAudio(CarvingMainProcessModel processModel) { }
	// RVA: 0x2db29dc VA: 0x75953ca9dc
	private Void _OpenBonusDialog() { }
	// RVA: 0x2db2bb4 VA: 0x75953cabb4
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2db2c4c VA: 0x75953cac4c
	public Void OnClickBackBtn() { }
	// RVA: 0x2dabeb8 VA: 0x75953c3eb8
	public Void SetBackBtnActive(Boolean isShow, Boolean isInfo) { }
	// RVA: 0x2db2e08 VA: 0x75953cae08
	public Void .ctor() { }
	// RVA: 0x2db2eb8 VA: 0x75953caeb8
	private Void <_OnShopToProcess>b__67_0(CarvingShopToProcessResponse res) { }
	// RVA: 0x2db2f3c VA: 0x75953caf3c
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x2db2f44 VA: 0x75953caf44
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```