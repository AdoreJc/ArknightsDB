# SandboxV2HomeController

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2HomeView _homeView`

- `Boolean m_isInited`

- `String m_topicId`

- `SandboxV2HomeModelProperty m_prop`

- `Int32 m_challengeRewardDialogInst`

- `Coroutine m_tutorialCoroutine`

- `UIPageFinder m_pageFinder`


## Methods

- `Void OnDestroy()`

- `Void _InitIfNot()`

- `Boolean _CheckIsInChallenge()`

- `Boolean _IsHomeStateStable()`

- `Void _Refresh(Boolean)`

- `Void _EventEnterGame()`

- `Void _OpenDungeonPage(String, Boolean)`

- `Void _EventOnEnterArchive()`

- `Void _EventOnOpenShopPage()`

- `Void _EventOpenMedalGroup()`

- `Void _EventEnterMonth()`

- `Void _EventOnOpenGuide()`

- `Void _EventOnToggleChallenge(Boolean)`

- `Void _EventOnEnterChallenge()`

- `Void _HandleEnterChallengeConfirm()`

- `Void _EventOnSettleChallenge()`

- `Void _HandleSettleChallengeConfirm()`

- `Void _EventOnOpenChallengeReward()`

- `Void _EventOnExploreModeClicked()`

- `Void _SendSwitchExploreModeService(Int32)`

- `Void _OnExploreModeServiceCallback()`

- `Void _HandleChallengeRewardDialogCallback(ValueBundle)`

- `Void _HandleFirstGuideGiveUpConfirm(String)`

- `Void _HandleSecondGuideGiveUpConfirm(String)`

- `Void _ShowFirstGuideGiveUpConfirmDialog(Action, Action)`

- `Void _ShowSecondGuideGiveUpConfirmDialog(Action, Action)`

- `Void _TutorialOnly_TryTriggerTutorial()`

- `IEnumerator _TryTriggerTutorial()`

- `Void _StopTutorialCoroutine()`

- `Void <_EventOnEnterChallenge>b__32_0()`

- `Void <_HandleEnterChallengeConfirm>b__33_0(SandboxV2StartChallengeResponse)`

- `Void <_EventOnSettleChallenge>b__34_0()`

- `Void <_HandleSettleChallengeConfirm>b__35_0(SandboxV2ChallengeSettleResponse)`

- `Void <_SendSwitchExploreModeService>b__38_0(PlayerEmptyDeltaResponse)`

- `Void <_HandleSecondGuideGiveUpConfirm>b__42_0(SandboxV2CreateGameResponse)`

- `Void <>xLuaBaseProxy_OnResume(Boolean)`

- `Boolean <>xLuaBaseProxy_OnPageBackPressBtnClick()`

- `Void <>xLuaBaseProxy_HandleCompDialogCallback(Int32, ValueBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2HomeController : SandboxPermHomeControllerBase
{
	private SandboxV2HomeView _homeView; // 0x30
	private Boolean m_isInited; // 0x38
	private String m_topicId; // 0x40
	private SandboxV2HomeModelProperty m_prop; // 0x48
	private Int32 m_challengeRewardDialogInst; // 0x50
	private Coroutine m_tutorialCoroutine; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_GetTopicId; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_GetNeedBindCanvas; // 0x20
	private static DelegateBridge __Hotfix0_GetNeedBindEffectHolders; // 0x28
	private static DelegateBridge __Hotfix0_GetMedalGroupId; // 0x30
	private static DelegateBridge __Hotfix0_PageOnlyStartShowEffects; // 0x38
	private static DelegateBridge __Hotfix0_PageOnlyDisposeEffects; // 0x40
	private static DelegateBridge __Hotfix0_CheckIfUseFastEnter; // 0x48
	private static DelegateBridge __Hotfix0_GetDisplayTweenConfig; // 0x50
	private static DelegateBridge __Hotfix0_OnPageBackPressBtnClick; // 0x58
	private static DelegateBridge __Hotfix0_HandleCompDialogCallback; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x68
	private static DelegateBridge __Hotfix0__CheckIsInChallenge; // 0x70
	private static DelegateBridge __Hotfix0__IsHomeStateStable; // 0x78
	private static DelegateBridge __Hotfix0__Refresh; // 0x80
	private static DelegateBridge __Hotfix0__EventEnterGame; // 0x88
	private static DelegateBridge __Hotfix0__OpenDungeonPage; // 0x90
	private static DelegateBridge __Hotfix0__EventOnEnterArchive; // 0x98
	private static DelegateBridge __Hotfix0__EventOnOpenShopPage; // 0xa0
	private static DelegateBridge __Hotfix0__EventOpenMedalGroup; // 0xa8
	private static DelegateBridge __Hotfix0__EventEnterMonth; // 0xb0
	private static DelegateBridge __Hotfix0__EventOnOpenGuide; // 0xb8
	private static DelegateBridge __Hotfix0__EventOnToggleChallenge; // 0xc0
	private static DelegateBridge __Hotfix0__EventOnEnterChallenge; // 0xc8
	private static DelegateBridge __Hotfix0__HandleEnterChallengeConfirm; // 0xd0
	private static DelegateBridge __Hotfix0__EventOnSettleChallenge; // 0xd8
	private static DelegateBridge __Hotfix0__HandleSettleChallengeConfirm; // 0xe0
	private static DelegateBridge __Hotfix0__EventOnOpenChallengeReward; // 0xe8
	private static DelegateBridge __Hotfix0__EventOnExploreModeClicked; // 0xf0
	private static DelegateBridge __Hotfix0__SendSwitchExploreModeService; // 0xf8
	private static DelegateBridge __Hotfix0__OnExploreModeServiceCallback; // 0x100
	private static DelegateBridge __Hotfix0__HandleChallengeRewardDialogCallback; // 0x108
	private static DelegateBridge __Hotfix0__HandleFirstGuideGiveUpConfirm; // 0x110
	private static DelegateBridge __Hotfix0__HandleSecondGuideGiveUpConfirm; // 0x118
	private static DelegateBridge __Hotfix0__ShowFirstGuideGiveUpConfirmDialog; // 0x120
	private static DelegateBridge __Hotfix0__ShowSecondGuideGiveUpConfirmDialog; // 0x128
	private static DelegateBridge __Hotfix0__TutorialOnly_TryTriggerTutorial; // 0x130
	private static DelegateBridge __Hotfix0__TryTriggerTutorial; // 0x138
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x140
	private static DelegateBridge _c__Hotfix0_ctor; // 0x148


	// RVA: 0x25cca80 VA: 0x7594be4a80
	public override Void Init(String topicId) { }
	// RVA: 0x25ccf4c VA: 0x7594be4f4c
	public override String GetTopicId() { }
	// RVA: 0x25ccfb4 VA: 0x7594be4fb4
	public override Void OnResume(Boolean isResumedFromStack) { }
	// RVA: 0x25cd27c VA: 0x7594be527c
	private Void OnDestroy() { }
	// RVA: 0x25cd38c VA: 0x7594be538c
	public override Canvas[] GetNeedBindCanvas() { }
	// RVA: 0x25cd4b0 VA: 0x7594be54b0
	public override UICommonPageEffectHolder[] GetNeedBindEffectHolders() { }
	// RVA: 0x25cd5d4 VA: 0x7594be55d4
	public override String GetMedalGroupId() { }
	// RVA: 0x25cd6ec VA: 0x7594be56ec
	public override Coroutine PageOnlyStartShowEffects(Boolean fastMode, Boolean backFromBattle) { }
	// RVA: 0x25cd8c0 VA: 0x7594be58c0
	public override Void PageOnlyDisposeEffects() { }
	// RVA: 0x25cdabc VA: 0x7594be5abc
	public override Boolean CheckIfUseFastEnter() { }
	// RVA: 0x25cdb68 VA: 0x7594be5b68
	public override DisplayTweenConfig GetDisplayTweenConfig(Boolean fastMode) { }
	// RVA: 0x25cdd10 VA: 0x7594be5d10
	public override Boolean OnPageBackPressBtnClick() { }
	// RVA: 0x25cde84 VA: 0x7594be5e84
	public override Void HandleCompDialogCallback(Int32 instId, ValueBundle output) { }
	// RVA: 0x25ccb18 VA: 0x7594be4b18
	private Void _InitIfNot() { }
	// RVA: 0x25ce5c0 VA: 0x7594be65c0
	private Boolean _CheckIsInChallenge() { }
	// RVA: 0x25ce66c VA: 0x7594be666c
	private Boolean _IsHomeStateStable() { }
	// RVA: 0x25cd068 VA: 0x7594be5068
	private Void _Refresh(Boolean isInit) { }
	// RVA: 0x25ceb1c VA: 0x7594be6b1c
	private Void _EventEnterGame() { }
	// RVA: 0x25cef34 VA: 0x7594be6f34
	private Void _OpenDungeonPage(String topic, Boolean isMonth) { }
	// RVA: 0x25cf078 VA: 0x7594be7078
	private Void _EventOnEnterArchive() { }
	// RVA: 0x25cf19c VA: 0x7594be719c
	private Void _EventOnOpenShopPage() { }
	// RVA: 0x25cf38c VA: 0x7594be738c
	private Void _EventOpenMedalGroup() { }
	// RVA: 0x25cf470 VA: 0x7594be7470
	private Void _EventEnterMonth() { }
	// RVA: 0x25cf4f8 VA: 0x7594be74f8
	private Void _EventOnOpenGuide() { }
	// RVA: 0x25cf5ac VA: 0x7594be75ac
	private Void _EventOnToggleChallenge(Boolean selected) { }
	// RVA: 0x25cf764 VA: 0x7594be7764
	private Void _EventOnEnterChallenge() { }
	// RVA: 0x25cfa68 VA: 0x7594be7a68
	private Void _HandleEnterChallengeConfirm() { }
	// RVA: 0x25cfc48 VA: 0x7594be7c48
	private Void _EventOnSettleChallenge() { }
	// RVA: 0x25cfeec VA: 0x7594be7eec
	private Void _HandleSettleChallengeConfirm() { }
	// RVA: 0x25d00cc VA: 0x7594be80cc
	private Void _EventOnOpenChallengeReward() { }
	// RVA: 0x25d01bc VA: 0x7594be81bc
	private Void _EventOnExploreModeClicked() { }
	// RVA: 0x25d036c VA: 0x7594be836c
	private Void _SendSwitchExploreModeService(Int32 mode) { }
	// RVA: 0x25d0670 VA: 0x7594be8670
	private Void _OnExploreModeServiceCallback() { }
	// RVA: 0x25cdf2c VA: 0x7594be5f2c
	private Void _HandleChallengeRewardDialogCallback(ValueBundle output) { }
	// RVA: 0x25cede4 VA: 0x7594be6de4
	private Void _HandleFirstGuideGiveUpConfirm(String topicId) { }
	// RVA: 0x25d0c18 VA: 0x7594be8c18
	private Void _HandleSecondGuideGiveUpConfirm(String topicId) { }
	// RVA: 0x25d08e8 VA: 0x7594be88e8
	private Void _ShowFirstGuideGiveUpConfirmDialog(Action cancelAction, Action confirmAction) { }
	// RVA: 0x25d0e40 VA: 0x7594be8e40
	private Void _ShowSecondGuideGiveUpConfirmDialog(Action cancelAction, Action confirmAction) { }
	// RVA: 0x25cd15c VA: 0x7594be515c
	private Void _TutorialOnly_TryTriggerTutorial() { }
	// RVA: 0x25d1204 VA: 0x7594be9204
	private IEnumerator _TryTriggerTutorial() { }
	// RVA: 0x25cd2e4 VA: 0x7594be52e4
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x25d12d8 VA: 0x7594be92d8
	public Void .ctor() { }
	// RVA: 0x25d1348 VA: 0x7594be9348
	private Void <_EventOnEnterChallenge>b__32_0() { }
	// RVA: 0x25d134c VA: 0x7594be934c
	private Void <_HandleEnterChallengeConfirm>b__33_0(SandboxV2StartChallengeResponse response) { }
	// RVA: 0x25d13dc VA: 0x7594be93dc
	private Void <_EventOnSettleChallenge>b__34_0() { }
	// RVA: 0x25d13e0 VA: 0x7594be93e0
	private Void <_HandleSettleChallengeConfirm>b__35_0(SandboxV2ChallengeSettleResponse response) { }
	// RVA: 0x25d14e4 VA: 0x7594be94e4
	private Void <_SendSwitchExploreModeService>b__38_0(PlayerEmptyDeltaResponse _) { }
	// RVA: 0x25d14e8 VA: 0x7594be94e8
	private Void <_HandleSecondGuideGiveUpConfirm>b__42_0(SandboxV2CreateGameResponse response) { }
	// RVA: 0x25d1504 VA: 0x7594be9504
	private Void <>xLuaBaseProxy_OnResume(Boolean P0) { }
	// RVA: 0x25d1510 VA: 0x7594be9510
	private Boolean <>xLuaBaseProxy_OnPageBackPressBtnClick() { }
	// RVA: 0x25d1518 VA: 0x7594be9518
	private Void <>xLuaBaseProxy_HandleCompDialogCallback(Int32 P0, ValueBundle P1) { }
}
```