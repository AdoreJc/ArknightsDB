# RL04AlchemyController

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04AlchemyImplView _implView`

- `RectTransform _panelTopMenu`

- `UIAnimationLocation _entryAnimLocation`

- `RL04AlchemyViewModel m_viewModel`

- `Tween m_entryTween`

- `State m_bindState`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _PlayEntryAnim()`

- `Void _SendStartAlchemyRequest(Action)`

- `Void _OnStartAlchemyFailed()`

- `Void _OnStartAlchemyCompleted()`

- `Void _SendLeaveAlchemyRequest(Action)`

- `Void _OnLeaveAlchemyCompleted()`

- `Void _OnLeaveAlchemyResponseFinish()`

- `Void _SendClaimAlchemyRewardRequest(Int32, Action)`

- `Void _OnClaimAlchemyRewardCompleted()`

- `Void _OnStartAlchemyBtnClick()`

- `Void _OnLeaveBtnClick()`

- `Void _OnCancelLeaveClick()`

- `Void _OnFragmentItemClick(String)`

- `Void _OnSlotItemClick(Int32)`

- `Void _OnClaimAlchemyRewardClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyController : AbstractRoguelikeAlchemyController
{
	private RL04AlchemyImplView _implView; // 0x18
	private RectTransform _panelTopMenu; // 0x20
	private UIAnimationLocation _entryAnimLocation; // 0x28
	public const Int32 MSG_SLOT_ITEM_CLICK; // 0x0
	public const Int32 MSG_FRAGMENT_ITEM_CLICK; // 0x0
	public const Int32 MSG_LEAVE_BTN_CLICK; // 0x0
	public const Int32 MSG_START_ALCHEMY_BTN_CLICK; // 0x0
	public const Int32 MSG_RESULT_VIEW_CLAIM_REWARD_CLICK; // 0x0
	public const Int32 MSG_CANCEL_LEAVE_CLICK; // 0x0
	private RL04AlchemyViewModel m_viewModel; // 0x38
	private Tween m_entryTween; // 0x40
	private State m_bindState; // 0x48
	private Boolean m_hasInited; // 0x50
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_BindState; // 0x8
	private static DelegateBridge __Hotfix0_OnStateResume; // 0x10
	private static DelegateBridge __Hotfix0_GeneViewData; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x30
	private static DelegateBridge __Hotfix0__SendStartAlchemyRequest; // 0x38
	private static DelegateBridge __Hotfix0__OnStartAlchemyFailed; // 0x40
	private static DelegateBridge __Hotfix0__OnStartAlchemyCompleted; // 0x48
	private static DelegateBridge __Hotfix0__SendLeaveAlchemyRequest; // 0x50
	private static DelegateBridge __Hotfix0__OnLeaveAlchemyCompleted; // 0x58
	private static DelegateBridge __Hotfix0__OnLeaveAlchemyResponseFinish; // 0x60
	private static DelegateBridge __Hotfix0__SendClaimAlchemyRewardRequest; // 0x68
	private static DelegateBridge __Hotfix0__OnClaimAlchemyRewardCompleted; // 0x70
	private static DelegateBridge __Hotfix0__OnStartAlchemyBtnClick; // 0x78
	private static DelegateBridge __Hotfix0__OnLeaveBtnClick; // 0x80
	private static DelegateBridge __Hotfix0__OnCancelLeaveClick; // 0x88
	private static DelegateBridge __Hotfix0__OnFragmentItemClick; // 0x90
	private static DelegateBridge __Hotfix0__OnSlotItemClick; // 0x98
	private static DelegateBridge __Hotfix0__OnClaimAlchemyRewardClick; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x2afb540 VA: 0x7595113540
	public override Void OnInit() { }
	// RVA: 0x2afb87c VA: 0x759511387c
	public override Void BindState(State state) { }
	// RVA: 0x2afba48 VA: 0x7595113a48
	public override Void OnStateResume() { }
	// RVA: 0x2afbaac VA: 0x7595113aac
	public override IRoguelikeAlchemyViewModel GeneViewData(String topicId) { }
	// RVA: 0x2afbc10 VA: 0x7595113c10
	public override Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2afb5d4 VA: 0x75951135d4
	private Void _InitIfNot() { }
	// RVA: 0x2afb70c VA: 0x759511370c
	private Void _PlayEntryAnim() { }
	// RVA: 0x2afc2b8 VA: 0x75951142b8
	private Void _SendStartAlchemyRequest(Action requestCallback) { }
	// RVA: 0x2afc8c8 VA: 0x75951148c8
	private Void _OnStartAlchemyFailed() { }
	// RVA: 0x2afc990 VA: 0x7595114990
	private Void _OnStartAlchemyCompleted() { }
	// RVA: 0x2afcc88 VA: 0x7595114c88
	private Void _SendLeaveAlchemyRequest(Action requestCallback) { }
	// RVA: 0x2afd08c VA: 0x759511508c
	private Void _OnLeaveAlchemyCompleted() { }
	// RVA: 0x2afd2d4 VA: 0x75951152d4
	private Void _OnLeaveAlchemyResponseFinish() { }
	// RVA: 0x2afd39c VA: 0x759511539c
	private Void _SendClaimAlchemyRewardRequest(Int32 rewardIndex, Action requestCallback) { }
	// RVA: 0x2afd688 VA: 0x7595115688
	private Void _OnClaimAlchemyRewardCompleted() { }
	// RVA: 0x2afc054 VA: 0x7595114054
	private Void _OnStartAlchemyBtnClick() { }
	// RVA: 0x2afbf1c VA: 0x7595113f1c
	private Void _OnLeaveBtnClick() { }
	// RVA: 0x2afc1dc VA: 0x75951141dc
	private Void _OnCancelLeaveClick() { }
	// RVA: 0x2afbe38 VA: 0x7595113e38
	private Void _OnFragmentItemClick(String fragmentInstId) { }
	// RVA: 0x2afbd54 VA: 0x7595113d54
	private Void _OnSlotItemClick(Int32 slotIndex) { }
	// RVA: 0x2afc10c VA: 0x759511410c
	private Void _OnClaimAlchemyRewardClick(Int32 rewardIndex) { }
	// RVA: 0x2afda70 VA: 0x7595115a70
	public Void .ctor() { }
}
```