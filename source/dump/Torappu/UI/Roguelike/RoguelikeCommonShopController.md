# RoguelikeCommonShopController

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeShopStatusView _shopViewsStatusBinder`

- `RoguelikeShopNormalView _normalView`

- `RoguelikeShopLineupView _lineupBuyView`

- `RoguelikeShopLineupView _lineupRecycleView`

- `RoguelikeShopDetailView _goodDetailView`

- `RoguelikeNpcDialogView _npcDialogView`

- `RoguelikeCommonShopBankViewBinder _bankViewsBinder`

- `RoguelikeGameBankEntryView _bankEntryView`

- `RoguelikeGameBankInvestView _bankInvestView`

- `RoguelikeGameBankFaultyView _bankFaultyView`

- `RectTransform _transBankWithdrawContainer`

- `RectTransform _transBattleShopConfirmContainer`

- `Boolean m_inited`

- `String m_topicId`

- `MenuAdapter m_menuAdapter`

- `UIPage m_page`

- `UIStateFinder m_finder`

- `RoguelikeShopStateBean m_stateBean`

- `IStateEngine m_engine`

- `RoguelikeDungeonController m_dungeonController`

- `RoguelikeCommonShopPlugin m_shopPlugin`

- `RoguelikeGameBankWithdrawCommonView m_bankWithdrawView`

- `RoguelikeGameShopBattleConfirmView m_battleConfirmView`

- `Int32 m_clickDealerCount`


## Methods

- `Void _InitIfNot()`

- `Void _TryInjectPlugin(String)`

- `Void _InitCommonChildView()`

- `Void _InitStatusController()`

- `Void _InitBankController()`

- `Void _BindPropForViews()`

- `Void _RegisterMenuAdapter(RoguelikeDungeonController)`

- `Boolean _IsCurrentStatusEqual(RoguelikeGameShopStatusEnum)`

- `Void _UpdateViewStatus(RoguelikeGameShopStatusEnum)`

- `Void _UpdateNpcDialog(RoguelikeGameShopDialogType, RoguelikeGameItemType)`

- `Void _OnGoodsClicked(RoguelikeGoodsViewModel)`

- `Void _OnBankSlotClicked()`

- `Void _OnLockSlotClicked(RoguelikeGoodsViewModel)`

- `Void _OnConfirmShopRefresh()`

- `Void _OnShopRefreshed()`

- `Void _OnDealerClick()`

- `Void _OnLeaveShop()`

- `Void _OnRefreshBtnClick()`

- `Void _OnSwitchOperationMode()`

- `Void _OnConfirmClicked()`

- `Void _OnBuyGoods(RoguelikeGoodsViewModel)`

- `Void _OnRecycleGoods(RoguelikeGoodsViewModel)`

- `Void _OnOpenInvest()`

- `Void _OnOpenWithdrawal()`

- `Void _LoadBankWithdrawView()`

- `Void _TryLoadBankWithdrawView()`

- `Void _OnWithdraw()`

- `Void _OnWithdrawUseItem(Int32)`

- `Boolean _WithdrawlPreCheck()`

- `Void _OnWithdrawSuccess()`

- `Void _OnWithdrawConsume()`

- `Void _OnWithdrawIncrementCurrent()`

- `Void _OnWithdrawDecrementCurrent()`

- `Void _OnWithdrawMaxCurrent()`

- `Void _OnWithdrawMinCurrent()`

- `Void _OnInvest()`

- `Void _LoadShopBattleConfirmView()`

- `Void _TryLoadBattleConfirmView()`

- `Void _InitBattleShopView()`

- `Void _InitNormalView()`

- `Void _InitLineupViews()`

- `Void _InitStatusView()`

- `Void _OnBattleConfirmClick()`

- `Void _ShowBattleConfirmView()`

- `Void _SendRobShopRequest(Action)`

- `Void _CloseSelf()`

- `IEnumerator _CloseSelfCoroutine()`

- `Void _EventOnOpenBankReward()`

- `Void _EventOnBackward()`

- `Void <_OnConfirmShopRefresh>b__47_0(RoguelikeShopRefreshResponse)`

- `Void <_OnLeaveShop>b__50_0(RoguelikeShopActionResponse)`

- `Void <_OnRefreshBtnClick>b__51_0()`

- `Void <_OnWithdraw>b__60_0(RoguelikeBankWithdrawResponse)`

- `Void <_OnWithdrawUseItem>b__61_0(RoguelikeBankWithdrawResponse)`

- `Void <_OnInvest>b__69_0(RoguelikeBankInvestResponse)`

- `Void <_OnBattleConfirmClick>b__76_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCommonShopController : MonoBehaviour, IHotfixable
{
	private RoguelikeShopStatusView _shopViewsStatusBinder; // 0x18
	private RoguelikeShopNormalView _normalView; // 0x20
	private RoguelikeShopLineupView _lineupBuyView; // 0x28
	private RoguelikeShopLineupView _lineupRecycleView; // 0x30
	private RoguelikeShopDetailView _goodDetailView; // 0x38
	private RoguelikeNpcDialogView _npcDialogView; // 0x40
	private RoguelikeCommonShopBankViewBinder _bankViewsBinder; // 0x48
	private RoguelikeGameBankEntryView _bankEntryView; // 0x50
	private RoguelikeGameBankInvestView _bankInvestView; // 0x58
	private RoguelikeGameBankFaultyView _bankFaultyView; // 0x60
	private RectTransform _transBankWithdrawContainer; // 0x68
	private RectTransform _transBattleShopConfirmContainer; // 0x70
	private Boolean m_inited; // 0x78
	private String m_topicId; // 0x80
	private MenuAdapter m_menuAdapter; // 0x88
	private UIPage m_page; // 0x90
	private UIStateFinder m_finder; // 0x98
	private RoguelikeShopStateBean m_stateBean; // 0xa8
	private IStateEngine m_engine; // 0xb0
	private RoguelikeDungeonController m_dungeonController; // 0xb8
	private RoguelikeCommonShopPlugin m_shopPlugin; // 0xc0
	private RoguelikeGameBankWithdrawCommonView m_bankWithdrawView; // 0xc8
	private RoguelikeGameShopBattleConfirmView m_battleConfirmView; // 0xd0
	private Int32 m_clickDealerCount; // 0xd8
	private const Int32 TO_BATTLE_CLICK_COUNT; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_LoadDynShopView; // 0x20
	private static DelegateBridge __Hotfix0_CollectDynShopView; // 0x28
	private static DelegateBridge __Hotfix0_CollectDynBankView; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__TryInjectPlugin; // 0x40
	private static DelegateBridge __Hotfix0__InitCommonChildView; // 0x48
	private static DelegateBridge __Hotfix0__InitStatusController; // 0x50
	private static DelegateBridge __Hotfix0__InitBankController; // 0x58
	private static DelegateBridge __Hotfix0__BindPropForViews; // 0x60
	private static DelegateBridge __Hotfix0__RegisterMenuAdapter; // 0x68
	private static DelegateBridge __Hotfix0__IsCurrentStatusEqual; // 0x70
	private static DelegateBridge __Hotfix0__UpdateViewStatus; // 0x78
	private static DelegateBridge __Hotfix0__UpdateNpcDialog; // 0x80
	private static DelegateBridge __Hotfix0__OnGoodsClicked; // 0x88
	private static DelegateBridge __Hotfix0__OnBankSlotClicked; // 0x90
	private static DelegateBridge __Hotfix0__OnLockSlotClicked; // 0x98
	private static DelegateBridge __Hotfix0__OnConfirmShopRefresh; // 0xa0
	private static DelegateBridge __Hotfix0__OnShopRefreshed; // 0xa8
	private static DelegateBridge __Hotfix0__OnDealerClick; // 0xb0
	private static DelegateBridge __Hotfix0__OnLeaveShop; // 0xb8
	private static DelegateBridge __Hotfix0__OnRefreshBtnClick; // 0xc0
	private static DelegateBridge __Hotfix0__OnSwitchOperationMode; // 0xc8
	private static DelegateBridge __Hotfix0__OnConfirmClicked; // 0xd0
	private static DelegateBridge __Hotfix0__OnBuyGoods; // 0xd8
	private static DelegateBridge __Hotfix0__OnRecycleGoods; // 0xe0
	private static DelegateBridge __Hotfix0__OnOpenInvest; // 0xe8
	private static DelegateBridge __Hotfix0__OnOpenWithdrawal; // 0xf0
	private static DelegateBridge __Hotfix0__LoadBankWithdrawView; // 0xf8
	private static DelegateBridge __Hotfix0__TryLoadBankWithdrawView; // 0x100
	private static DelegateBridge __Hotfix0__OnWithdraw; // 0x108
	private static DelegateBridge __Hotfix0__OnWithdrawUseItem; // 0x110
	private static DelegateBridge __Hotfix0__WithdrawlPreCheck; // 0x118
	private static DelegateBridge __Hotfix0__OnWithdrawSuccess; // 0x120
	private static DelegateBridge __Hotfix0__OnWithdrawConsume; // 0x128
	private static DelegateBridge __Hotfix0__OnWithdrawIncrementCurrent; // 0x130
	private static DelegateBridge __Hotfix0__OnWithdrawDecrementCurrent; // 0x138
	private static DelegateBridge __Hotfix0__OnWithdrawMaxCurrent; // 0x140
	private static DelegateBridge __Hotfix0__OnWithdrawMinCurrent; // 0x148
	private static DelegateBridge __Hotfix0__OnInvest; // 0x150
	private static DelegateBridge __Hotfix0__LoadShopBattleConfirmView; // 0x158
	private static DelegateBridge __Hotfix0__TryLoadBattleConfirmView; // 0x160
	private static DelegateBridge __Hotfix0__InitBattleShopView; // 0x168
	private static DelegateBridge __Hotfix0__InitNormalView; // 0x170
	private static DelegateBridge __Hotfix0__InitLineupViews; // 0x178
	private static DelegateBridge __Hotfix0__InitStatusView; // 0x180
	private static DelegateBridge __Hotfix0__OnBattleConfirmClick; // 0x188
	private static DelegateBridge __Hotfix0__ShowBattleConfirmView; // 0x190
	private static DelegateBridge __Hotfix0__SendRobShopRequest; // 0x198
	private static DelegateBridge __Hotfix0__CloseSelf; // 0x1a0
	private static DelegateBridge __Hotfix0__CloseSelfCoroutine; // 0x1a8
	private static DelegateBridge __Hotfix0__EventOnOpenBankReward; // 0x1b0
	private static DelegateBridge __Hotfix0__EventOnBackward; // 0x1b8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1c0


	// RVA: 0x2ad423c VA: 0x75950ec23c
	public virtual Void OnEnter(Builder builder) { }
	// RVA: 0x2ad4990 VA: 0x75950ec990
	public virtual Void OnResume(Boolean isResumedFromStack) { }
	// RVA: 0x2ad4ad0 VA: 0x75950ecad0
	public virtual Void OnExit() { }
	// RVA: 0x2ad4b34 VA: 0x75950ecb34
	public virtual IEnumerator HideCoroutine() { }
	// RVA: 0x2ad4c08 VA: 0x75950ecc08
	protected virtual Void LoadDynShopView() { }
	// RVA: 0x2ad51d8 VA: 0x75950ed1d8
	protected virtual Void CollectDynShopView(List`1 panelList) { }
	// RVA: 0x2ad5318 VA: 0x75950ed318
	protected virtual Void CollectDynBankView(List`1 panelList) { }
	// RVA: 0x2ad44b4 VA: 0x75950ec4b4
	private Void _InitIfNot() { }
	// RVA: 0x2ad556c VA: 0x75950ed56c
	private Void _TryInjectPlugin(String topicId) { }
	// RVA: 0x2ad5798 VA: 0x75950ed798
	private Void _InitCommonChildView() { }
	// RVA: 0x2ad6134 VA: 0x75950ee134
	private Void _InitStatusController() { }
	// RVA: 0x2ad6498 VA: 0x75950ee498
	private Void _InitBankController() { }
	// RVA: 0x2ad6688 VA: 0x75950ee688
	private Void _BindPropForViews() { }
	// RVA: 0x2ad456c VA: 0x75950ec56c
	private Void _RegisterMenuAdapter(RoguelikeDungeonController controller) { }
	// RVA: 0x2ad6b98 VA: 0x75950eeb98
	private Boolean _IsCurrentStatusEqual(RoguelikeGameShopStatusEnum shopStatus) { }
	// RVA: 0x2ad6cb8 VA: 0x75950eecb8
	private Void _UpdateViewStatus(RoguelikeGameShopStatusEnum shopStatus) { }
	// RVA: 0x2ad6ebc VA: 0x75950eeebc
	private Void _UpdateNpcDialog(RoguelikeGameShopDialogType dialogType, RoguelikeGameItemType itemType) { }
	// RVA: 0x2ad706c VA: 0x75950ef06c
	private Void _OnGoodsClicked(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ad71b8 VA: 0x75950ef1b8
	private Void _OnBankSlotClicked() { }
	// RVA: 0x2ad7258 VA: 0x75950ef258
	private Void _OnLockSlotClicked(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ad73bc VA: 0x75950ef3bc
	private Void _OnConfirmShopRefresh() { }
	// RVA: 0x2ad765c VA: 0x75950ef65c
	private Void _OnShopRefreshed() { }
	// RVA: 0x2ad77e0 VA: 0x75950ef7e0
	private Void _OnDealerClick() { }
	// RVA: 0x2ad79d8 VA: 0x75950ef9d8
	private Void _OnLeaveShop() { }
	// RVA: 0x2ad7e88 VA: 0x75950efe88
	private Void _OnRefreshBtnClick() { }
	// RVA: 0x2ad833c VA: 0x75950f033c
	private Void _OnSwitchOperationMode() { }
	// RVA: 0x2ad8438 VA: 0x75950f0438
	private Void _OnConfirmClicked() { }
	// RVA: 0x2ad8964 VA: 0x75950f0964
	private Void _OnBuyGoods(RoguelikeGoodsViewModel goods) { }
	// RVA: 0x2ad8620 VA: 0x75950f0620
	private Void _OnRecycleGoods(RoguelikeGoodsViewModel goods) { }
	// RVA: 0x2ad8d2c VA: 0x75950f0d2c
	private Void _OnOpenInvest() { }
	// RVA: 0x2ad8e8c VA: 0x75950f0e8c
	private Void _OnOpenWithdrawal() { }
	// RVA: 0x2ad4c78 VA: 0x75950ecc78
	private Void _LoadBankWithdrawView() { }
	// RVA: 0x2ad9020 VA: 0x75950f1020
	private Void _TryLoadBankWithdrawView() { }
	// RVA: 0x2ad92b0 VA: 0x75950f12b0
	private Void _OnWithdraw() { }
	// RVA: 0x2ad9648 VA: 0x75950f1648
	private Void _OnWithdrawUseItem(Int32 withdrawCount) { }
	// RVA: 0x2ad9490 VA: 0x75950f1490
	private Boolean _WithdrawlPreCheck() { }
	// RVA: 0x2ad983c VA: 0x75950f183c
	private Void _OnWithdrawSuccess() { }
	// RVA: 0x2ad9968 VA: 0x75950f1968
	private Void _OnWithdrawConsume() { }
	// RVA: 0x2ad9a0c VA: 0x75950f1a0c
	private Void _OnWithdrawIncrementCurrent() { }
	// RVA: 0x2ad9aac VA: 0x75950f1aac
	private Void _OnWithdrawDecrementCurrent() { }
	// RVA: 0x2ad9b4c VA: 0x75950f1b4c
	private Void _OnWithdrawMaxCurrent() { }
	// RVA: 0x2ad9bec VA: 0x75950f1bec
	private Void _OnWithdrawMinCurrent() { }
	// RVA: 0x2ad9c8c VA: 0x75950f1c8c
	private Void _OnInvest() { }
	// RVA: 0x2ad507c VA: 0x75950ed07c
	private Void _LoadShopBattleConfirmView() { }
	// RVA: 0x2ada004 VA: 0x75950f2004
	private Void _TryLoadBattleConfirmView() { }
	// RVA: 0x2ad48cc VA: 0x75950ec8cc
	private Void _InitBattleShopView() { }
	// RVA: 0x2ad4660 VA: 0x75950ec660
	private Void _InitNormalView() { }
	// RVA: 0x2ad471c VA: 0x75950ec71c
	private Void _InitLineupViews() { }
	// RVA: 0x2ad4810 VA: 0x75950ec810
	private Void _InitStatusView() { }
	// RVA: 0x2ada23c VA: 0x75950f223c
	private Void _OnBattleConfirmClick() { }
	// RVA: 0x2ad7920 VA: 0x75950ef920
	private Void _ShowBattleConfirmView() { }
	// RVA: 0x2ada2f4 VA: 0x75950f22f4
	private Void _SendRobShopRequest(Action onComplete) { }
	// RVA: 0x2ada78c VA: 0x75950f278c
	private Void _CloseSelf() { }
	// RVA: 0x2ada978 VA: 0x75950f2978
	private IEnumerator _CloseSelfCoroutine() { }
	// RVA: 0x2adaa4c VA: 0x75950f2a4c
	private Void _EventOnOpenBankReward() { }
	// RVA: 0x2adac70 VA: 0x75950f2c70
	private Void _EventOnBackward() { }
	// RVA: 0x2adae60 VA: 0x75950f2e60
	public Void .ctor() { }
	// RVA: 0x2adaed0 VA: 0x75950f2ed0
	private Void <_OnConfirmShopRefresh>b__47_0(RoguelikeShopRefreshResponse response) { }
	// RVA: 0x2adaed4 VA: 0x75950f2ed4
	private Void <_OnLeaveShop>b__50_0(RoguelikeShopActionResponse response) { }
	// RVA: 0x2adb02c VA: 0x75950f302c
	private Void <_OnRefreshBtnClick>b__51_0() { }
	// RVA: 0x2adb030 VA: 0x75950f3030
	private Void <_OnWithdraw>b__60_0(RoguelikeBankWithdrawResponse response) { }
	// RVA: 0x2adb034 VA: 0x75950f3034
	private Void <_OnWithdrawUseItem>b__61_0(RoguelikeBankWithdrawResponse response) { }
	// RVA: 0x2adb038 VA: 0x75950f3038
	private Void <_OnInvest>b__69_0(RoguelikeBankInvestResponse response) { }
	// RVA: 0x2adb220 VA: 0x75950f3220
	private Void <_OnBattleConfirmClick>b__76_0() { }
}
```