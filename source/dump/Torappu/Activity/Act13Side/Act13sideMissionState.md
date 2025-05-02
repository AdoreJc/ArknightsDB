# Act13sideMissionState

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Act13sideDailyMissionListView _dailyMissionView`

- `Act13sideNormalMissionOneView _missionOneView`

- `Act13sideMissionStateBtn _missionbtn`

- `Act13sideMissionStateBtn _dailyMissionBtn`

- `UIAnimationLocation _animDailyMission`

- `Single _animDailyMissionDelay`

- `UIAnimationLocation _animAgendaRecover`

- `GameObject _agendaAnimGo`

- `Text _textRecover`

- `Text _textAgenda`

- `Text _textAgendaMax`

- `Text _textMaxHint`

- `GameObject _maxHintGo`

- `String _guidebookSubsignal`

- `RectTransform _topMenuContainer`

- `CanvasGroup _dailyCanvas`

- `CanvasGroup _longTermCanvas`

- `CommonTopMenu m_topMenu`

- `TemplateActivityController m_cacheController`

- `Act13sideMissionStateBean m_stateBean`

- `String m_cacheGroupId`

- `Boolean m_showAgendaAnim`

- `Boolean m_showMissionRefreshAnim`

- `Boolean m_isDailyMissionAnim`

- `PrestigePromoteParam m_promoteParam`

- `Coroutine m_tutorialCoroutine`

- `Tween m_doTween`


## Methods

- `Void OnDailyMissionSelect()`

- `Void OnLongTermMissionSelect()`

- `Void SelectGroupId(String)`

- `Void _InitTopMenu()`

- `Void BindController(TemplateActivityController)`

- `Void _TriggerTutorialCoroutine()`

- `Void _StopTutorialCoroutine()`

- `IEnumerator _WaitAndTrigTutorial()`

- `Void _PlayAgendaAnimIfNeed()`

- `Void _UpdateDailyMissionProp()`

- `Void _ShowFilterRewardList(Act13SideDailyMissionCommitResponse, OrgData)`

- `Void _JumpToPrestigePromoteState()`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `Void _SendDailyFlagRecover(String, Action)`

- `Void _AddMissionPoolStateToTop(Boolean)`

- `Void OnBtnCloseAgedaAnim()`

- `Void _NavToDailyMissionPoolState()`

- `Void _NavToStage(String)`

- `Void _OnDailyMissionCommit(Int32)`

- `Void _OnDailyMissionCancelWithDialog(Int32)`

- `Void _OnDailyMissionCancel(Int32)`

- `Void <RegisterToDataListener>b__32_0(IStateBean)`

- `Void <RegisterToDataListener>b__32_1(IStateBean)`

- `Void <RegisterToDataListener>b__32_2(IStateBean)`

- `Void <OnDailyMissionSelect>b__33_1(Single)`

- `Void <OnLongTermMissionSelect>b__34_1(Single)`

- `Void <_InitTopMenu>b__36_0()`

- `Void <OnBtnCloseAgedaAnim>b__52_0()`

- `Void <_NavToDailyMissionPoolState>b__53_0()`

- `Void <_OnDailyMissionCancel>b__57_0(Act13SideDailyMissionCancelResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideMissionState : PopupFadeState, IBaseActStateHolder, IHotfixable
{
	private Act13sideDailyMissionListView _dailyMissionView; // 0x70
	private Act13sideNormalMissionOneView _missionOneView; // 0x78
	private Act13sideMissionStateBtn _missionbtn; // 0x80
	private Act13sideMissionStateBtn _dailyMissionBtn; // 0x88
	private UIAnimationLocation _animDailyMission; // 0x90
	private Single _animDailyMissionDelay; // 0xa0
	private UIAnimationLocation _animAgendaRecover; // 0xa8
	private GameObject _agendaAnimGo; // 0xb8
	private Text _textRecover; // 0xc0
	private Text _textAgenda; // 0xc8
	private Text _textAgendaMax; // 0xd0
	private Text _textMaxHint; // 0xd8
	private GameObject _maxHintGo; // 0xe0
	private String _guidebookSubsignal; // 0xe8
	private RectTransform _topMenuContainer; // 0xf0
	private CanvasGroup _dailyCanvas; // 0xf8
	private CanvasGroup _longTermCanvas; // 0x100
	private const Single ALPHA_DURATION; // 0x0
	private const String FLAG_AGENDA; // 0x0
	private const String FLAG_MISSION; // 0x0
	private CommonTopMenu m_topMenu; // 0x108
	private TemplateActivityController m_cacheController; // 0x110
	private Act13sideMissionStateBean m_stateBean; // 0x118
	private String m_cacheGroupId; // 0x120
	private Boolean m_showAgendaAnim; // 0x128
	private Boolean m_showMissionRefreshAnim; // 0x129
	private Boolean m_isDailyMissionAnim; // 0x12a
	private PrestigePromoteParam m_promoteParam; // 0x130
	private Coroutine m_tutorialCoroutine; // 0x138
	private Tween m_doTween; // 0x140
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnDailyMissionSelect; // 0x10
	private static DelegateBridge __Hotfix0_OnLongTermMissionSelect; // 0x18
	private static DelegateBridge __Hotfix0_SelectGroupId; // 0x20
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnExit; // 0x38
	private static DelegateBridge __Hotfix0_OnResume; // 0x40
	private static DelegateBridge __Hotfix0_OnPause; // 0x48
	private static DelegateBridge __Hotfix0_BindController; // 0x50
	private static DelegateBridge __Hotfix0__TriggerTutorialCoroutine; // 0x58
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x60
	private static DelegateBridge __Hotfix0__WaitAndTrigTutorial; // 0x68
	private static DelegateBridge __Hotfix0__PlayAgendaAnimIfNeed; // 0x70
	private static DelegateBridge __Hotfix0__UpdateDailyMissionProp; // 0x78
	private static DelegateBridge __Hotfix0__ShowFilterRewardList; // 0x80
	private static DelegateBridge __Hotfix0__JumpToPrestigePromoteState; // 0x88
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x90
	private static DelegateBridge __Hotfix0__SendDailyFlagRecover; // 0x98
	private static DelegateBridge __Hotfix0__AddMissionPoolStateToTop; // 0xa0
	private static DelegateBridge __Hotfix0_OnBtnCloseAgedaAnim; // 0xa8
	private static DelegateBridge __Hotfix0__NavToDailyMissionPoolState; // 0xb0
	private static DelegateBridge __Hotfix0__NavToStage; // 0xb8
	private static DelegateBridge __Hotfix0__OnDailyMissionCommit; // 0xc0
	private static DelegateBridge __Hotfix0__OnDailyMissionCancelWithDialog; // 0xc8
	private static DelegateBridge __Hotfix0__OnDailyMissionCancel; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8


	// RVA: 0x342d674 VA: 0x7595a45674
	public override IStateBean GetCacheBean() { }
	// RVA: 0x342d6dc VA: 0x7595a456dc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x342d940 VA: 0x7595a45940
	public Void OnDailyMissionSelect() { }
	// RVA: 0x342db68 VA: 0x7595a45b68
	public Void OnLongTermMissionSelect() { }
	// RVA: 0x342ddb8 VA: 0x7595a45db8
	public Void SelectGroupId(String groupId) { }
	// RVA: 0x342dee8 VA: 0x7595a45ee8
	private Void _InitTopMenu() { }
	// RVA: 0x342e014 VA: 0x7595a46014
	protected override Void OnEnter() { }
	// RVA: 0x342e418 VA: 0x7595a46418
	protected override Void OnExit() { }
	// RVA: 0x342e4b4 VA: 0x7595a464b4
	protected override Void OnResume() { }
	// RVA: 0x342e8f4 VA: 0x7595a468f4
	protected override Void OnPause() { }
	// RVA: 0x342ea20 VA: 0x7595a46a20
	public Void BindController(TemplateActivityController controller) { }
	// RVA: 0x342e540 VA: 0x7595a46540
	private Void _TriggerTutorialCoroutine() { }
	// RVA: 0x342e968 VA: 0x7595a46968
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x342ec98 VA: 0x7595a46c98
	private IEnumerator _WaitAndTrigTutorial() { }
	// RVA: 0x342e61c VA: 0x7595a4661c
	private Void _PlayAgendaAnimIfNeed() { }
	// RVA: 0x342e330 VA: 0x7595a46330
	private Void _UpdateDailyMissionProp() { }
	// RVA: 0x342ed6c VA: 0x7595a46d6c
	private Void _ShowFilterRewardList(Act13SideDailyMissionCommitResponse commitResponse, OrgData orgData) { }
	// RVA: 0x342f1d8 VA: 0x7595a471d8
	private Void _JumpToPrestigePromoteState() { }
	// RVA: 0x342f100 VA: 0x7595a47100
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onAfterItemShow) { }
	// RVA: 0x342f3b8 VA: 0x7595a473b8
	private Void _SendDailyFlagRecover(String flag, Action onComplete) { }
	// RVA: 0x342f64c VA: 0x7595a4764c
	private Void _AddMissionPoolStateToTop(Boolean showRefreshAnim) { }
	// RVA: 0x342f770 VA: 0x7595a47770
	public Void OnBtnCloseAgedaAnim() { }
	// RVA: 0x342f840 VA: 0x7595a47840
	private Void _NavToDailyMissionPoolState() { }
	// RVA: 0x342f93c VA: 0x7595a4793c
	private Void _NavToStage(String stageId) { }
	// RVA: 0x342fa20 VA: 0x7595a47a20
	private Void _OnDailyMissionCommit(Int32 boardIdx) { }
	// RVA: 0x342fd4c VA: 0x7595a47d4c
	private Void _OnDailyMissionCancelWithDialog(Int32 boardIdx) { }
	// RVA: 0x34300f8 VA: 0x7595a480f8
	private Void _OnDailyMissionCancel(Int32 boardIdx) { }
	// RVA: 0x3430334 VA: 0x7595a48334
	public Void .ctor() { }
	// RVA: 0x34303e8 VA: 0x7595a483e8
	private Void <RegisterToDataListener>b__32_0(IStateBean stateBean) { }
	// RVA: 0x3430478 VA: 0x7595a48478
	private Void <RegisterToDataListener>b__32_1(IStateBean stateBean) { }
	// RVA: 0x3430538 VA: 0x7595a48538
	private Void <RegisterToDataListener>b__32_2(IStateBean stateBean) { }
	// RVA: 0x34305c0 VA: 0x7595a485c0
	private Void <OnDailyMissionSelect>b__33_1(Single val) { }
	// RVA: 0x34305dc VA: 0x7595a485dc
	private Void <OnLongTermMissionSelect>b__34_1(Single val) { }
	// RVA: 0x34305f8 VA: 0x7595a485f8
	private Void <_InitTopMenu>b__36_0() { }
	// RVA: 0x34306a8 VA: 0x7595a486a8
	private Void <OnBtnCloseAgedaAnim>b__52_0() { }
	// RVA: 0x34306cc VA: 0x7595a486cc
	private Void <_NavToDailyMissionPoolState>b__53_0() { }
	// RVA: 0x34306d4 VA: 0x7595a486d4
	private Void <_OnDailyMissionCancel>b__57_0(Act13SideDailyMissionCancelResponse reponse) { }
	// RVA: 0x3430770 VA: 0x7595a48770
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3430778 VA: 0x7595a48778
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3430780 VA: 0x7595a48780
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x3430788 VA: 0x7595a48788
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x3430790 VA: 0x7595a48790
	private Void <>xLuaBaseProxy_OnPause() { }
}
```