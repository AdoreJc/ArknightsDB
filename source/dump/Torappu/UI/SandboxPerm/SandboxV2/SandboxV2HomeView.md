# SandboxV2HomeView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2HomeGameEntryView _gameEntryView`

- `SandboxV2HomeMonthEntryView _monthEntryView`

- `SandboxV2HomeShopEntryView _shopEntryView`

- `SandboxV2HomeChallengeEntryView _challengeEntryView`

- `DisplayTweenConfig _topCanvasDisplayConfig`

- `UICommonTrackPoint _trackPointArchive`

- `SandboxV2HomeExploreModeView _exploreModeView`

- `SandboxV2HomeChallengeModeView _challengeModeView`

- `UIAnimationLocation _challengeViewShowAnim`

- `Action <onEnterGameAction>k__BackingField`

- `Action <onEnterMonthAction>k__BackingField`

- `Action <onEnterArchiveAction>k__BackingField`

- `Action <onEnterShopAction>k__BackingField`

- `Action <onOpenMedalGroupAction>k__BackingField`

- `Action <onOpenGuideAction>k__BackingField`

- `Action <onEnterChallengeAction>k__BackingField`

- `Action <onSettleChallengeAction>k__BackingField`

- `Action <onOpenChallengeRewardDialogAction>k__BackingField`

- `Action <onExploreModeClickAction>k__BackingField`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `UITwoStepAnimation m_animPlayer`

- `Coroutine m_showEffectCoroutine`

- `TrackPointViewProperty m_trackPointArchive`

- `Boolean m_hasInited`

- `String m_topicId`

- `UISwitchTween m_challengeViewShowTween`

- `Int32 m_cachedInitSeq`

- `SandboxV2HomeModel m_cachedViewModel`


## Properties

- `Action onEnterGameAction`

- `Action onEnterMonthAction`

- `Action onEnterArchiveAction`

- `Action onEnterShopAction`

- `Action onOpenMedalGroupAction`

- `Action onOpenGuideAction`

- `Action onEnterChallengeAction`

- `Action onSettleChallengeAction`

- `Action onOpenChallengeRewardDialogAction`

- `Action onExploreModeClickAction`


## Methods

- `Action get_onEnterGameAction()`

- `Void set_onEnterGameAction(Action)`

- `Action get_onEnterMonthAction()`

- `Void set_onEnterMonthAction(Action)`

- `Action get_onEnterArchiveAction()`

- `Void set_onEnterArchiveAction(Action)`

- `Action get_onEnterShopAction()`

- `Void set_onEnterShopAction(Action)`

- `Action get_onOpenMedalGroupAction()`

- `Void set_onOpenMedalGroupAction(Action)`

- `Action get_onOpenGuideAction()`

- `Void set_onOpenGuideAction(Action)`

- `Void set_onToggleChallengeAction(Action`1)`

- `Action get_onEnterChallengeAction()`

- `Void set_onEnterChallengeAction(Action)`

- `Action get_onSettleChallengeAction()`

- `Void set_onSettleChallengeAction(Action)`

- `Action get_onOpenChallengeRewardDialogAction()`

- `Void set_onOpenChallengeRewardDialogAction(Action)`

- `Action get_onExploreModeClickAction()`

- `Void set_onExploreModeClickAction(Action)`

- `Coroutine StartShowEffect(Boolean, Boolean)`

- `DisplayTweenConfig GetDisplayTweenConfig(Boolean)`

- `Void SetEffectEnable(Boolean)`

- `Void _InitIfNot()`

- `IEnumerator _ShowEffectCoroutine(Boolean, Boolean)`

- `Void _TryToTriggerAvg(String, Action)`

- `Void EventOnEnterGame()`

- `Void EventOnEnterMonth()`

- `Void EventOnEnterArchive()`

- `Void EventOnEnterShop()`

- `Void EventOnOpenMedalGroup()`

- `Void EventOnOpenGuide()`

- `Void EventOnOpenChallenge()`

- `Void EventOnCloseChallenge()`

- `Void EventOnEnterChallenge()`

- `Void EventOnSettleChallenge()`

- `Void EventOnOpenChallengeRewardDialog()`

- `Void EventOnExploreModeClicked()`

- `Void _TryTriggerTutorial()`

- `Void _TryRaiseAvgSignal()`

- `GameObject TutorialOnly_GetChallengeModeEntryBtnGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2HomeView : DataBinder`1, IHotfixable
{
	private const String SANDBOX_V2_ENTRY_AVG_TRIGGER; // 0x0
	private SandboxV2HomeGameEntryView _gameEntryView; // 0x20
	private SandboxV2HomeMonthEntryView _monthEntryView; // 0x28
	private SandboxV2HomeShopEntryView _shopEntryView; // 0x30
	private SandboxV2HomeChallengeEntryView _challengeEntryView; // 0x38
	private UIAnimationLocation[] _enterAnims; // 0x40
	private UIAnimationLocation[] _loopAnims; // 0x48
	private UICommonPageEffectHolder[] _effectHolders; // 0x50
	private Canvas[] _canvases; // 0x58
	private DisplayTweenConfig _topCanvasDisplayConfig; // 0x60
	private UICommonTrackPoint _trackPointArchive; // 0x68
	private SandboxV2HomeExploreModeView _exploreModeView; // 0x70
	private SandboxV2HomeChallengeModeView _challengeModeView; // 0x78
	private UIAnimationLocation _challengeViewShowAnim; // 0x80
	private Action <onEnterGameAction>k__BackingField; // 0x90
	private Action <onEnterMonthAction>k__BackingField; // 0x98
	private Action <onEnterArchiveAction>k__BackingField; // 0xa0
	private Action <onEnterShopAction>k__BackingField; // 0xa8
	private Action <onOpenMedalGroupAction>k__BackingField; // 0xb0
	private Action <onOpenGuideAction>k__BackingField; // 0xb8
	private Action`1 <onToggleChallengeAction>k__BackingField; // 0xc0
	private Action <onEnterChallengeAction>k__BackingField; // 0xc8
	private Action <onSettleChallengeAction>k__BackingField; // 0xd0
	private Action <onOpenChallengeRewardDialogAction>k__BackingField; // 0xd8
	private Action <onExploreModeClickAction>k__BackingField; // 0xe0
	private UIStateFinder m_stateFinder; // 0xe8
	private UIPageFinder m_pageFinder; // 0xf8
	private UITwoStepAnimation m_animPlayer; // 0x108
	private Coroutine m_showEffectCoroutine; // 0x110
	private TrackPointViewProperty m_trackPointArchive; // 0x118
	private Boolean m_hasInited; // 0x120
	private String m_topicId; // 0x128
	private UISwitchTween m_challengeViewShowTween; // 0x130
	private Int32 m_cachedInitSeq; // 0x138
	private SandboxV2HomeModel m_cachedViewModel; // 0x140
	private static DelegateBridge __Hotfix0_get_onEnterGameAction; // 0x0
	private static DelegateBridge __Hotfix0_set_onEnterGameAction; // 0x8
	private static DelegateBridge __Hotfix0_get_onEnterMonthAction; // 0x10
	private static DelegateBridge __Hotfix0_set_onEnterMonthAction; // 0x18
	private static DelegateBridge __Hotfix0_get_onEnterArchiveAction; // 0x20
	private static DelegateBridge __Hotfix0_set_onEnterArchiveAction; // 0x28
	private static DelegateBridge __Hotfix0_get_onEnterShopAction; // 0x30
	private static DelegateBridge __Hotfix0_set_onEnterShopAction; // 0x38
	private static DelegateBridge __Hotfix0_get_onOpenMedalGroupAction; // 0x40
	private static DelegateBridge __Hotfix0_set_onOpenMedalGroupAction; // 0x48
	private static DelegateBridge __Hotfix0_get_onOpenGuideAction; // 0x50
	private static DelegateBridge __Hotfix0_set_onOpenGuideAction; // 0x58
	private static DelegateBridge __Hotfix0_get_onToggleChallengeAction; // 0x60
	private static DelegateBridge __Hotfix0_set_onToggleChallengeAction; // 0x68
	private static DelegateBridge __Hotfix0_get_onEnterChallengeAction; // 0x70
	private static DelegateBridge __Hotfix0_set_onEnterChallengeAction; // 0x78
	private static DelegateBridge __Hotfix0_get_onSettleChallengeAction; // 0x80
	private static DelegateBridge __Hotfix0_set_onSettleChallengeAction; // 0x88
	private static DelegateBridge __Hotfix0_get_onOpenChallengeRewardDialogAction; // 0x90
	private static DelegateBridge __Hotfix0_set_onOpenChallengeRewardDialogAction; // 0x98
	private static DelegateBridge __Hotfix0_get_onExploreModeClickAction; // 0xa0
	private static DelegateBridge __Hotfix0_set_onExploreModeClickAction; // 0xa8
	private static DelegateBridge __Hotfix0_get_needBindCanvas; // 0xb0
	private static DelegateBridge __Hotfix0_get_needBindEffectHolders; // 0xb8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0xc0
	private static DelegateBridge __Hotfix0_StartShowEffect; // 0xc8
	private static DelegateBridge __Hotfix0_GetDisplayTweenConfig; // 0xd0
	private static DelegateBridge __Hotfix0_SetEffectEnable; // 0xd8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0xe0
	private static DelegateBridge __Hotfix0__ShowEffectCoroutine; // 0xe8
	private static DelegateBridge __Hotfix0__TryToTriggerAvg; // 0xf0
	private static DelegateBridge __Hotfix0_EventOnEnterGame; // 0xf8
	private static DelegateBridge __Hotfix0_EventOnEnterMonth; // 0x100
	private static DelegateBridge __Hotfix0_EventOnEnterArchive; // 0x108
	private static DelegateBridge __Hotfix0_EventOnEnterShop; // 0x110
	private static DelegateBridge __Hotfix0_EventOnOpenMedalGroup; // 0x118
	private static DelegateBridge __Hotfix0_EventOnOpenGuide; // 0x120
	private static DelegateBridge __Hotfix0_EventOnOpenChallenge; // 0x128
	private static DelegateBridge __Hotfix0_EventOnCloseChallenge; // 0x130
	private static DelegateBridge __Hotfix0_EventOnEnterChallenge; // 0x138
	private static DelegateBridge __Hotfix0_EventOnSettleChallenge; // 0x140
	private static DelegateBridge __Hotfix0_EventOnOpenChallengeRewardDialog; // 0x148
	private static DelegateBridge __Hotfix0_EventOnExploreModeClicked; // 0x150
	private static DelegateBridge __Hotfix0__TryTriggerTutorial; // 0x158
	private static DelegateBridge __Hotfix0__TryRaiseAvgSignal; // 0x160
	private static DelegateBridge __Hotfix0_TutorialOnly_GetChallengeModeEntryBtnGo; // 0x168
	private static DelegateBridge _c__Hotfix0_ctor; // 0x170

	private Action onEnterGameAction { get; set; }
	private Action onEnterMonthAction { get; set; }
	private Action onEnterArchiveAction { get; set; }
	private Action onEnterShopAction { get; set; }
	private Action onOpenMedalGroupAction { get; set; }
	private Action onOpenGuideAction { get; set; }
	private Action`1 onToggleChallengeAction { get; set; }
	private Action onEnterChallengeAction { get; set; }
	private Action onSettleChallengeAction { get; set; }
	private Action onOpenChallengeRewardDialogAction { get; set; }
	private Action onExploreModeClickAction { get; set; }
	public Canvas[] needBindCanvas { get; }
	public UICommonPageEffectHolder[] needBindEffectHolders { get; }

	// RVA: 0x25d3f28 VA: 0x7594bebf28
	private Action get_onEnterGameAction() { }
	// RVA: 0x25cdfa8 VA: 0x7594be5fa8
	public Void set_onEnterGameAction(Action value) { }
	// RVA: 0x25d3f90 VA: 0x7594bebf90
	private Action get_onEnterMonthAction() { }
	// RVA: 0x25ce1b8 VA: 0x7594be61b8
	public Void set_onEnterMonthAction(Action value) { }
	// RVA: 0x25d3ff8 VA: 0x7594bebff8
	private Action get_onEnterArchiveAction() { }
	// RVA: 0x25ce02c VA: 0x7594be602c
	public Void set_onEnterArchiveAction(Action value) { }
	// RVA: 0x25d4060 VA: 0x7594bec060
	private Action get_onEnterShopAction() { }
	// RVA: 0x25ce0b0 VA: 0x7594be60b0
	public Void set_onEnterShopAction(Action value) { }
	// RVA: 0x25d40c8 VA: 0x7594bec0c8
	private Action get_onOpenMedalGroupAction() { }
	// RVA: 0x25ce134 VA: 0x7594be6134
	public Void set_onOpenMedalGroupAction(Action value) { }
	// RVA: 0x25d4130 VA: 0x7594bec130
	private Action get_onOpenGuideAction() { }
	// RVA: 0x25ce23c VA: 0x7594be623c
	public Void set_onOpenGuideAction(Action value) { }
	// RVA: 0x25d4198 VA: 0x7594bec198
	private Action`1 get_onToggleChallengeAction() { }
	// RVA: 0x25ce2c0 VA: 0x7594be62c0
	public Void set_onToggleChallengeAction(Action`1 value) { }
	// RVA: 0x25d4200 VA: 0x7594bec200
	private Action get_onEnterChallengeAction() { }
	// RVA: 0x25ce344 VA: 0x7594be6344
	public Void set_onEnterChallengeAction(Action value) { }
	// RVA: 0x25d4268 VA: 0x7594bec268
	private Action get_onSettleChallengeAction() { }
	// RVA: 0x25ce3c8 VA: 0x7594be63c8
	public Void set_onSettleChallengeAction(Action value) { }
	// RVA: 0x25d42d0 VA: 0x7594bec2d0
	private Action get_onOpenChallengeRewardDialogAction() { }
	// RVA: 0x25ce44c VA: 0x7594be644c
	public Void set_onOpenChallengeRewardDialogAction(Action value) { }
	// RVA: 0x25d4338 VA: 0x7594bec338
	private Action get_onExploreModeClickAction() { }
	// RVA: 0x25ce4d0 VA: 0x7594be64d0
	public Void set_onExploreModeClickAction(Action value) { }
	// RVA: 0x25cd448 VA: 0x7594be5448
	public Canvas[] get_needBindCanvas() { }
	// RVA: 0x25cd56c VA: 0x7594be556c
	public UICommonPageEffectHolder[] get_needBindEffectHolders() { }
	// RVA: 0x25d43a0 VA: 0x7594bec3a0
	public override Void OnValueChanged(SandboxV2HomeModelProperty property) { }
	// RVA: 0x25cd7d8 VA: 0x7594be57d8
	public Coroutine StartShowEffect(Boolean fastMode, Boolean backFromBattle) { }
	// RVA: 0x25cdc64 VA: 0x7594be5c64
	public DisplayTweenConfig GetDisplayTweenConfig(Boolean fastMode) { }
	// RVA: 0x25cd984 VA: 0x7594be5984
	public Void SetEffectEnable(Boolean isEnable) { }
	// RVA: 0x25d45f0 VA: 0x7594bec5f0
	private Void _InitIfNot() { }
	// RVA: 0x25d4708 VA: 0x7594bec708
	private IEnumerator _ShowEffectCoroutine(Boolean fastMode, Boolean backFromBattle) { }
	// RVA: 0x25d47e0 VA: 0x7594bec7e0
	private Void _TryToTriggerAvg(String topicId, Action nextStep) { }
	// RVA: 0x25d49bc VA: 0x7594bec9bc
	public Void EventOnEnterGame() { }
	// RVA: 0x25d4a58 VA: 0x7594beca58
	public Void EventOnEnterMonth() { }
	// RVA: 0x25d4af4 VA: 0x7594becaf4
	public Void EventOnEnterArchive() { }
	// RVA: 0x25d4b90 VA: 0x7594becb90
	public Void EventOnEnterShop() { }
	// RVA: 0x25d4c2c VA: 0x7594becc2c
	public Void EventOnOpenMedalGroup() { }
	// RVA: 0x25d4cc8 VA: 0x7594beccc8
	public Void EventOnOpenGuide() { }
	// RVA: 0x25d4d64 VA: 0x7594becd64
	public Void EventOnOpenChallenge() { }
	// RVA: 0x25d4e04 VA: 0x7594bece04
	public Void EventOnCloseChallenge() { }
	// RVA: 0x25d4ea4 VA: 0x7594becea4
	public Void EventOnEnterChallenge() { }
	// RVA: 0x25d4f40 VA: 0x7594becf40
	public Void EventOnSettleChallenge() { }
	// RVA: 0x25d4fdc VA: 0x7594becfdc
	public Void EventOnOpenChallengeRewardDialog() { }
	// RVA: 0x25d5078 VA: 0x7594bed078
	public Void EventOnExploreModeClicked() { }
	// RVA: 0x25d50e8 VA: 0x7594bed0e8
	private Void _TryTriggerTutorial() { }
	// RVA: 0x25d51b4 VA: 0x7594bed1b4
	private Void _TryRaiseAvgSignal() { }
	// RVA: 0x25d18e0 VA: 0x7594be98e0
	public GameObject TutorialOnly_GetChallengeModeEntryBtnGo() { }
	// RVA: 0x25d52d8 VA: 0x7594bed2d8
	public Void .ctor() { }
}
```