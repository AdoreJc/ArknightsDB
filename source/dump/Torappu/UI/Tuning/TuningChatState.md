# TuningChatState

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningChatController _chatController`

- `TuningChatView _chatView`

- `TuningChatNarrationView _narrationView`

- `RectTransform _backRt`

- `UIAnimationLocation _enterAnim`

- `Boolean m_isInited`

- `Boolean m_isReceiving`

- `String m_actId`

- `TuningChatProperty m_property`

- `TuningProductBagProperty m_bagProperty`

- `TuningChatStateBean m_stateBean`

- `Tween m_enterTween`

- `AnswerParam m_cachedAnswerParam`


## Methods

- `Void _InitIfNot()`

- `Void _PlayEnterAnim()`

- `Void _UpdateData(String)`

- `Void _OnBackPress()`

- `Void _OnDismiss()`

- `Void OnBackPress()`

- `Void _StartPlayImpl(String, String, Int32)`

- `Void _ResetPlayImpl()`

- `Void _OnStartPlay()`

- `Void _OnSelectInvest(String)`

- `Void _OnChatSkip()`

- `Void _OnHandleNarration(Int32)`

- `Void _OnNarrationPlay(Int32, String, String)`

- `Void _OnNarrationHandled()`

- `Void _OnOpenBackPack()`

- `Void _OnSubmit(Int32)`

- `Void _OnFinish()`

- `Void _OnSelectBagType(String)`

- `Void _OnSelectBagProduct(String)`

- `Void _OnOpenTuning()`

- `Void _UpdateBackPack(Boolean, Boolean)`

- `Void _ShowBag(Boolean)`

- `Void _TriggerAudioStart(String, String)`

- `Void _TriggerAudioStop()`

- `Void _HandleService(String, String, Action`1)`

- `Void _HandleDailyResponse(Int32, TuningChatItemViewModel, TuningChatDailyResponse)`

- `Void _HandleMajorHiddenResponse(Int32, TuningChatItemViewModel, TuningChatMajorHiddenResponse)`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `Void _HandleSuccess(Int32, TuningChatItemViewModel, TuningChatCommitResponse)`

- `Void _DoArchiveTrackTrigger(TuningChatItemViewModel)`

- `Void _OnShowDialogConfirm(Int32, TuningChatItemViewModel, TuningChatCommitResponse)`

- `Void _OnItemsGained(Int32, TuningChatItemViewModel)`

- `Void _HandleDaily(TuningChatItemViewModel, TuningChatDailyResponse)`

- `Void _HandleMajorHidden(TuningChatItemViewModel, TuningChatMajorHiddenResponse)`

- `Void _ShowDialog(Options)`

- `Void _OnDailyFailDialog(String, String, Boolean)`

- `Void _OnMajorHiddenFailDialog(String, Boolean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatState : PopupFadeState, IValueMsgReceiver, IHotfixable
{
	private TuningChatController _chatController; // 0x70
	private TuningChatView _chatView; // 0x78
	private TuningChatNarrationView _narrationView; // 0x80
	private RectTransform _backRt; // 0x88
	private UIAnimationLocation _enterAnim; // 0x90
	private Boolean m_isInited; // 0xa0
	private Boolean m_isReceiving; // 0xa1
	private String m_actId; // 0xa8
	private TuningChatProperty m_property; // 0xb0
	private TuningProductBagProperty m_bagProperty; // 0xb8
	private TuningChatStateBean m_stateBean; // 0xc0
	private Tween m_enterTween; // 0xc8
	private AnswerParam m_cachedAnswerParam; // 0xd0
	public const Int32 MSG_CHAT_SKIP; // 0x0
	public const Int32 MSG_OPEN_BACKPACK; // 0x0
	public const Int32 MSG_SUBMIT; // 0x0
	public const Int32 MSG_FINISH; // 0x0
	public const Int32 MSG_NEXT; // 0x0
	public const Int32 MSG_SELECT_INVEST; // 0x0
	public const Int32 MSG_OPEN_TUNING; // 0x0
	public const Int32 MSG_SELECT_BAG_TYPE; // 0x0
	public const Int32 MSG_SELECT_BAG_PRODUCT; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x20
	private static DelegateBridge __Hotfix0__UpdateData; // 0x28
	private static DelegateBridge __Hotfix0__OnBackPress; // 0x30
	private static DelegateBridge __Hotfix0__OnDismiss; // 0x38
	private static DelegateBridge __Hotfix0_OnBackPress; // 0x40
	private static DelegateBridge __Hotfix0__StartPlayImpl; // 0x48
	private static DelegateBridge __Hotfix0__ResetPlayImpl; // 0x50
	private static DelegateBridge __Hotfix0__OnStartPlay; // 0x58
	private static DelegateBridge __Hotfix0__OnSelectInvest; // 0x60
	private static DelegateBridge __Hotfix0__OnChatSkip; // 0x68
	private static DelegateBridge __Hotfix0__OnHandleNarration; // 0x70
	private static DelegateBridge __Hotfix0__OnNarrationPlay; // 0x78
	private static DelegateBridge __Hotfix0__OnNarrationHandled; // 0x80
	private static DelegateBridge __Hotfix0__OnOpenBackPack; // 0x88
	private static DelegateBridge __Hotfix0__OnSubmit; // 0x90
	private static DelegateBridge __Hotfix0__OnFinish; // 0x98
	private static DelegateBridge __Hotfix0__OnSelectBagType; // 0xa0
	private static DelegateBridge __Hotfix0__OnSelectBagProduct; // 0xa8
	private static DelegateBridge __Hotfix0__OnOpenTuning; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateBackPack; // 0xb8
	private static DelegateBridge __Hotfix0__ShowBag; // 0xc0
	private static DelegateBridge __Hotfix0__TriggerAudioStart; // 0xc8
	private static DelegateBridge __Hotfix0__TriggerAudioStop; // 0xd0
	private static DelegateBridge __Hotfix0__HandleService; // 0xd8
	private static DelegateBridge __Hotfix0__HandleDailyResponse; // 0xe0
	private static DelegateBridge __Hotfix0__HandleMajorHiddenResponse; // 0xe8
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0xf0
	private static DelegateBridge __Hotfix0__HandleSuccess; // 0xf8
	private static DelegateBridge __Hotfix0__DoArchiveTrackTrigger; // 0x100
	private static DelegateBridge __Hotfix0__OnShowDialogConfirm; // 0x108
	private static DelegateBridge __Hotfix0__OnItemsGained; // 0x110
	private static DelegateBridge __Hotfix0__HandleDaily; // 0x118
	private static DelegateBridge __Hotfix0__HandleMajorHidden; // 0x120
	private static DelegateBridge __Hotfix0__ShowDialog; // 0x128
	private static DelegateBridge __Hotfix0__OnDailyFailDialog; // 0x130
	private static DelegateBridge __Hotfix0__OnMajorHiddenFailDialog; // 0x138
	private static DelegateBridge __Hotfix0_OnMessage; // 0x140
	private static DelegateBridge _c__Hotfix0_ctor; // 0x148


	// RVA: 0x231b3a4 VA: 0x75949333a4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x231b40c VA: 0x759493340c
	protected override Void OnEnter() { }
	// RVA: 0x231c1d4 VA: 0x75949341d4
	protected override Void OnResume() { }
	// RVA: 0x231b52c VA: 0x759493352c
	private Void _InitIfNot() { }
	// RVA: 0x231c024 VA: 0x7594934024
	private Void _PlayEnterAnim() { }
	// RVA: 0x231c648 VA: 0x7594934648
	private Void _UpdateData(String investId) { }
	// RVA: 0x231c878 VA: 0x7594934878
	private Void _OnBackPress() { }
	// RVA: 0x231c764 VA: 0x7594934764
	private Void _OnDismiss() { }
	// RVA: 0x231ca2c VA: 0x7594934a2c
	public Void OnBackPress() { }
	// RVA: 0x231ca94 VA: 0x7594934a94
	private Void _StartPlayImpl(String storyId, String npcName, Int32 index) { }
	// RVA: 0x231bf40 VA: 0x7594933f40
	private Void _ResetPlayImpl() { }
	// RVA: 0x231c504 VA: 0x7594934504
	private Void _OnStartPlay() { }
	// RVA: 0x231cdb0 VA: 0x7594934db0
	private Void _OnSelectInvest(String investId) { }
	// RVA: 0x231ce90 VA: 0x7594934e90
	private Void _OnChatSkip() { }
	// RVA: 0x231cf04 VA: 0x7594934f04
	private Void _OnHandleNarration(Int32 index) { }
	// RVA: 0x231cf90 VA: 0x7594934f90
	private Void _OnNarrationPlay(Int32 index, String content, String narType) { }
	// RVA: 0x231d214 VA: 0x7594935214
	private Void _OnNarrationHandled() { }
	// RVA: 0x231d2e4 VA: 0x75949352e4
	private Void _OnOpenBackPack() { }
	// RVA: 0x231d388 VA: 0x7594935388
	private Void _OnSubmit(Int32 index) { }
	// RVA: 0x231d70c VA: 0x759493570c
	private Void _OnFinish() { }
	// RVA: 0x231d780 VA: 0x7594935780
	private Void _OnSelectBagType(String typeId) { }
	// RVA: 0x231d86c VA: 0x759493586c
	private Void _OnSelectBagProduct(String productId) { }
	// RVA: 0x231db5c VA: 0x7594935b5c
	private Void _OnOpenTuning() { }
	// RVA: 0x231c328 VA: 0x7594934328
	private Void _UpdateBackPack(Boolean useCacheAnswer, Boolean isFastMode) { }
	// RVA: 0x231b6dc VA: 0x75949336dc
	private Void _ShowBag(Boolean isShow) { }
	// RVA: 0x231da00 VA: 0x7594935a00
	private Void _TriggerAudioStart(String musicMainId, String musicSubId) { }
	// RVA: 0x231dcf0 VA: 0x7594935cf0
	private Void _TriggerAudioStop() { }
	// RVA: 0x VA: 0x0
	private Void _HandleService(String investId, String productId, Action`1 onPreceed) { }
	// RVA: 0x231de68 VA: 0x7594935e68
	private Void _HandleDailyResponse(Int32 index, TuningChatItemViewModel selectedViewModel, TuningChatDailyResponse response) { }
	// RVA: 0x231e4f0 VA: 0x75949364f0
	private Void _HandleMajorHiddenResponse(Int32 index, TuningChatItemViewModel selectedViewModel, TuningChatMajorHiddenResponse response) { }
	// RVA: 0x231e908 VA: 0x7594936908
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x231df4c VA: 0x7594935f4c
	private Void _HandleSuccess(Int32 index, TuningChatItemViewModel selectedViewModel, TuningChatCommitResponse response) { }
	// RVA: 0x231ea10 VA: 0x7594936a10
	private Void _DoArchiveTrackTrigger(TuningChatItemViewModel selectedViewModel) { }
	// RVA: 0x231eda0 VA: 0x7594936da0
	private Void _OnShowDialogConfirm(Int32 index, TuningChatItemViewModel selectedViewModel, TuningChatCommitResponse response) { }
	// RVA: 0x231efc0 VA: 0x7594936fc0
	private Void _OnItemsGained(Int32 index, TuningChatItemViewModel selectedViewModel) { }
	// RVA: 0x231e1cc VA: 0x75949361cc
	private Void _HandleDaily(TuningChatItemViewModel selectedViewModel, TuningChatDailyResponse response) { }
	// RVA: 0x231e5d4 VA: 0x75949365d4
	private Void _HandleMajorHidden(TuningChatItemViewModel selectedViewModel, TuningChatMajorHiddenResponse response) { }
	// RVA: 0x231ec88 VA: 0x7594936c88
	private Void _ShowDialog(Options options) { }
	// RVA: 0x231f1f8 VA: 0x75949371f8
	private Void _OnDailyFailDialog(String productTypeId, String orcheId, Boolean openRare) { }
	// RVA: 0x231f77c VA: 0x759493777c
	private Void _OnMajorHiddenFailDialog(String productId, Boolean openRare) { }
	// RVA: 0x231f8ec VA: 0x75949378ec
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x231faf8 VA: 0x7594937af8
	public Void .ctor() { }
	// RVA: 0x231fcf4 VA: 0x7594937cf4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x231fcfc VA: 0x7594937cfc
	private Void <>xLuaBaseProxy_OnResume() { }
}
```