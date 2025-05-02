# Act13sideDailyMissionPoolState

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `RectTransform _backBtnRt`

- `Act13sideDailyMissionPoolView _view`

- `UIAnimationLocation _animRefresh`

- `UIAnimationLocation _animEnter`

- `Boolean m_hasInited`

- `Boolean m_missionFlag`

- `Act13sideDailyMissionPoolStateBean m_stateBean`

- `TemplateActivityController m_stageController`

- `Boolean m_isPlayAcceptAnim`


## Properties

- `TemplateActivityController actController`

- `String activityId`


## Methods

- `Void _RaiseTutorialSignal()`

- `Void _JumpToSearchState(IStateBean)`

- `Void _JumpToReplaceState(IStateBean)`

- `Void _UpdateMissionProp()`

- `Void _PlayRefreshAnimIfNeed()`

- `Void _InitIfNot()`

- `TemplateActivityController get_actController()`

- `String get_activityId()`

- `T _FetchStageController()`

- `Void _OnMissonPoolItemSelected(Int32)`

- `Void OnBtnSearchClick()`

- `Void OnBtnAcceptClick()`

- `Void OnBtnReplaceClick()`

- `Void <_PlayRefreshAnimIfNeed>b__17_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionPoolState : PopupFadeState
{
	private RectTransform _backBtnRt; // 0x70
	private Act13sideDailyMissionPoolView _view; // 0x78
	private UIAnimationLocation _animRefresh; // 0x80
	private UIAnimationLocation _animEnter; // 0x90
	private Boolean m_hasInited; // 0xa0
	private Boolean m_missionFlag; // 0xa1
	private Act13sideDailyMissionPoolStateBean m_stateBean; // 0xa8
	private TemplateActivityController m_stageController; // 0xb0
	private Boolean m_isPlayAcceptAnim; // 0xb8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__RaiseTutorialSignal; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__JumpToSearchState; // 0x28
	private static DelegateBridge __Hotfix0__JumpToReplaceState; // 0x30
	private static DelegateBridge __Hotfix0__UpdateMissionProp; // 0x38
	private static DelegateBridge __Hotfix0__PlayRefreshAnimIfNeed; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0_get_actController; // 0x50
	private static DelegateBridge __Hotfix0_get_activityId; // 0x58
	private static DelegateBridge __Hotfix0__FetchStageController; // 0x60
	private static DelegateBridge __Hotfix0__OnMissonPoolItemSelected; // 0x68
	private static DelegateBridge __Hotfix0_OnBtnSearchClick; // 0x70
	private static DelegateBridge __Hotfix0_OnBtnAcceptClick; // 0x78
	private static DelegateBridge __Hotfix0_OnBtnReplaceClick; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	protected TemplateActivityController actController { get; }
	protected String activityId { get; }

	// RVA: 0x3429640 VA: 0x7595a41640
	public override IStateBean GetCacheBean() { }
	// RVA: 0x34296a8 VA: 0x7595a416a8
	protected override Void OnEnter() { }
	// RVA: 0x3429a44 VA: 0x7595a41a44
	protected override Void OnResume() { }
	// RVA: 0x3429adc VA: 0x7595a41adc
	private Void _RaiseTutorialSignal() { }
	// RVA: 0x3429dd0 VA: 0x7595a41dd0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3429fc4 VA: 0x7595a41fc4
	private Void _JumpToSearchState(IStateBean stateBean) { }
	// RVA: 0x342a1ac VA: 0x7595a421ac
	private Void _JumpToReplaceState(IStateBean stateBean) { }
	// RVA: 0x3429968 VA: 0x7595a41968
	private Void _UpdateMissionProp() { }
	// RVA: 0x3429b40 VA: 0x7595a41b40
	private Void _PlayRefreshAnimIfNeed() { }
	// RVA: 0x34297a8 VA: 0x7595a417a8
	private Void _InitIfNot() { }
	// RVA: 0x342a304 VA: 0x7595a42304
	protected TemplateActivityController get_actController() { }
	// RVA: 0x342a0dc VA: 0x7595a420dc
	protected String get_activityId() { }
	// RVA: 0x VA: 0x0
	private T _FetchStageController() { }
	// RVA: 0x342a3dc VA: 0x7595a423dc
	private Void _OnMissonPoolItemSelected(Int32 selectedIdx) { }
	// RVA: 0x342a4ec VA: 0x7595a424ec
	public Void OnBtnSearchClick() { }
	// RVA: 0x342a5f4 VA: 0x7595a425f4
	public Void OnBtnAcceptClick() { }
	// RVA: 0x342a90c VA: 0x7595a4290c
	public Void OnBtnReplaceClick() { }
	// RVA: 0x342aa1c VA: 0x7595a42a1c
	public Void .ctor() { }
	// RVA: 0x342aac8 VA: 0x7595a42ac8
	private Void <_PlayRefreshAnimIfNeed>b__17_0() { }
	// RVA: 0x342aacc VA: 0x7595a42acc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x342aad4 VA: 0x7595a42ad4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x342aadc VA: 0x7595a42adc
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```