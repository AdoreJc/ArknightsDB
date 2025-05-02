# UICharacterSelectState

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `CharSelectStateBean _stateBean`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `GameObject _btnClear`

- `UIAnimationLocation _fadeInAnim`

- `CharSelectCardChangeListener _cardChangeListener`

- `CharSelectAttrController _attrController`

- `CharSelectCardGroup _cardGroup`

- `CharSelectCardListAdapter _cardListAdapter`

- `UICharacterSortFilterPanelBinder _sortFilterPanelBinder`

- `UICharacterSortTypeGroupBinder _sortGroupBinder`

- `UICharacterStarMarkTopItemBinder _starMarkTopSortBinder`

- `GameObject _predefineCharTipsPanel`

- `UIAnimationLocation _fliterAnimLoc`

- `ViewBusiness m_viewBusiness`

- `AVGApplySortFilterCommandExecutor m_applySortFilterCmdExecutor`

- `AnimationSwitchTween m_filterSwitchAnim`


## Properties

- `IPlugin plugin`


## Methods

- `IPlugin get_plugin()`

- `Void Awake()`

- `Void EventOnCardSelect(Int32)`

- `Void EventOnSkillSelect(String)`

- `Void EventOnBranchSelect(String)`

- `Void ShowCharacterInfo()`

- `Void EventOnSortTypeGroupClick(CharacterSortType)`

- `Void EventOnSortFilterBtnClick()`

- `Void EventOnStarMarkTopToggle()`

- `Void EventOnClearSquadBtnClick()`

- `Void EventOnCancelBtnClick()`

- `Void EventOnAttrTabClick(CharAttrTabType)`

- `Void EventOnFilter(CharacterFilterViewModel)`

- `Void EventOnShowFilterBar()`

- `Void EventOnSort(CharacterSortType)`

- `Void _OnSortPanelSwitch(Boolean)`

- `Void _RefreshPanelSwitch()`

- `AnimationSwitchTween _EnsureSortPanelSwithAnim()`

- `Void _TryUpdateFilterPanelShow(Boolean)`

- `Void EventOnConfirmBtnClick()`

- `IEnumerator _TweenAnimation(UIAnimationLocation, Boolean)`

- `Void _ConfirmOutput()`

- `Void _Cancel()`

- `Void _InitViews()`

- `Void _BindCardGroup()`

- `Void _BindSortPanel()`

- `Void _PassDataToFilterState(UICharacterSortFilterStateBean)`

- `Void _ReceiveDataFromFilterState(UICharacterSortFilterStateBean)`

- `Void <Awake>b__26_0(GameObject)`

- `Void <Awake>b__26_1()`

- `Void <RegisterFromDataListener>b__31_0(IStateBean)`

- `Void <RegisterToDataListener>b__32_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_DismissSelf()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class UICharacterSelectState : UIPopupState
{
	private CharSelectStateBean _stateBean; // 0x60
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x68
	private GameObject _btnClear; // 0x70
	private UIAnimationLocation _fadeInAnim; // 0x78
	private CharSelectCardChangeListener _cardChangeListener; // 0x88
	private CharSelectAttrController _attrController; // 0x90
	private CharSelectCardGroup _cardGroup; // 0x98
	private CharSelectCardListAdapter _cardListAdapter; // 0xa0
	private UICharacterSortFilterPanelBinder _sortFilterPanelBinder; // 0xa8
	private UICharacterSortTypeGroupBinder _sortGroupBinder; // 0xb0
	private CharSelectAttrTabItem[] _tabItems; // 0xb8
	private UICharacterStarMarkTopItemBinder _starMarkTopSortBinder; // 0xc0
	private GameObject _predefineCharTipsPanel; // 0xc8
	private UIAnimationLocation _fliterAnimLoc; // 0xd0
	private ViewBusiness m_viewBusiness; // 0xe0
	private AVGApplySortFilterCommandExecutor m_applySortFilterCmdExecutor; // 0xe8
	private AnimationSwitchTween m_filterSwitchAnim; // 0xf0
	private static DelegateBridge __Hotfix0_get_plugin; // 0x0
	private static DelegateBridge __Hotfix0_Awake; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x30
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x38
	private static DelegateBridge __Hotfix0_OnResume; // 0x40
	private static DelegateBridge __Hotfix0_DismissSelf; // 0x48
	private static DelegateBridge __Hotfix0_EventOnCardSelect; // 0x50
	private static DelegateBridge __Hotfix0_EventOnSkillSelect; // 0x58
	private static DelegateBridge __Hotfix0_EventOnBranchSelect; // 0x60
	private static DelegateBridge __Hotfix0_ShowCharacterInfo; // 0x68
	private static DelegateBridge __Hotfix0_EventOnSortTypeGroupClick; // 0x70
	private static DelegateBridge __Hotfix0_EventOnSortFilterBtnClick; // 0x78
	private static DelegateBridge __Hotfix0_EventOnStarMarkTopToggle; // 0x80
	private static DelegateBridge __Hotfix0_EventOnClearSquadBtnClick; // 0x88
	private static DelegateBridge __Hotfix0_EventOnCancelBtnClick; // 0x90
	private static DelegateBridge __Hotfix0_EventOnAttrTabClick; // 0x98
	private static DelegateBridge __Hotfix0_EventOnFilter; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnShowFilterBar; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnSort; // 0xb0
	private static DelegateBridge __Hotfix0__OnSortPanelSwitch; // 0xb8
	private static DelegateBridge __Hotfix0__RefreshPanelSwitch; // 0xc0
	private static DelegateBridge __Hotfix0__EnsureSortPanelSwithAnim; // 0xc8
	private static DelegateBridge __Hotfix0__TryUpdateFilterPanelShow; // 0xd0
	private static DelegateBridge __Hotfix0_EventOnConfirmBtnClick; // 0xd8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0xe0
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0xe8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0xf0
	private static DelegateBridge __Hotfix0_HideImmediately; // 0xf8
	private static DelegateBridge __Hotfix0__TweenAnimation; // 0x100
	private static DelegateBridge __Hotfix0__ConfirmOutput; // 0x108
	private static DelegateBridge __Hotfix0__Cancel; // 0x110
	private static DelegateBridge __Hotfix0__InitViews; // 0x118
	private static DelegateBridge __Hotfix0__BindCardGroup; // 0x120
	private static DelegateBridge __Hotfix0__BindSortPanel; // 0x128
	private static DelegateBridge __Hotfix0__PassDataToFilterState; // 0x130
	private static DelegateBridge __Hotfix0__ReceiveDataFromFilterState; // 0x138
	private static DelegateBridge _c__Hotfix0_ctor; // 0x140

	protected IPlugin plugin { get; }

	// RVA: 0x2ce8fa4 VA: 0x7595300fa4
	protected IPlugin get_plugin() { }
	// RVA: 0x2ce9018 VA: 0x7595301018
	private Void Awake() { }
	// RVA: 0x2ce90dc VA: 0x75953010dc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ce9144 VA: 0x7595301144
	protected override Void OnEnter() { }
	// RVA: 0x2ce96c8 VA: 0x75953016c8
	protected override Void OnExit() { }
	// RVA: 0x2ce9790 VA: 0x7595301790
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2ce9808 VA: 0x7595301808
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2ce9980 VA: 0x7595301980
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2ce9af8 VA: 0x7595301af8
	protected override Void OnResume() { }
	// RVA: 0x2ce9c4c VA: 0x7595301c4c
	public override Void DismissSelf() { }
	// RVA: 0x2ce9da0 VA: 0x7595301da0
	public Void EventOnCardSelect(Int32 chrInstId) { }
	// RVA: 0x2cea018 VA: 0x7595302018
	public Void EventOnSkillSelect(String skillId) { }
	// RVA: 0x2cea1b4 VA: 0x75953021b4
	public Void EventOnBranchSelect(String equipId) { }
	// RVA: 0x2cea350 VA: 0x7595302350
	public Void ShowCharacterInfo() { }
	// RVA: 0x2cea4e4 VA: 0x75953024e4
	public Void EventOnSortTypeGroupClick(CharacterSortType sortType) { }
	// RVA: 0x2cea590 VA: 0x7595302590
	public Void EventOnSortFilterBtnClick() { }
	// RVA: 0x2cea6ac VA: 0x75953026ac
	public Void EventOnStarMarkTopToggle() { }
	// RVA: 0x2cea73c VA: 0x759530273c
	public Void EventOnClearSquadBtnClick() { }
	// RVA: 0x2cea7cc VA: 0x75953027cc
	public Void EventOnCancelBtnClick() { }
	// RVA: 0x2cea9ac VA: 0x75953029ac
	public Void EventOnAttrTabClick(CharAttrTabType tabType) { }
	// RVA: 0x2ceaa88 VA: 0x7595302a88
	public Void EventOnFilter(CharacterFilterViewModel filterModel) { }
	// RVA: 0x2ceac34 VA: 0x7595302c34
	public Void EventOnShowFilterBar() { }
	// RVA: 0x2ceaca0 VA: 0x7595302ca0
	public Void EventOnSort(CharacterSortType sortType) { }
	// RVA: 0x2ceab84 VA: 0x7595302b84
	private Void _OnSortPanelSwitch(Boolean isShow) { }
	// RVA: 0x2ce9b98 VA: 0x7595301b98
	private Void _RefreshPanelSwitch() { }
	// RVA: 0x2ceadf0 VA: 0x7595302df0
	private AnimationSwitchTween _EnsureSortPanelSwithAnim() { }
	// RVA: 0x2cead4c VA: 0x7595302d4c
	private Void _TryUpdateFilterPanelShow(Boolean isFilterPanelShow) { }
	// RVA: 0x2ceaed8 VA: 0x7595302ed8
	public Void EventOnConfirmBtnClick() { }
	// RVA: 0x2ceb0cc VA: 0x75953030cc
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2ceb21c VA: 0x759530321c
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2ceb340 VA: 0x7595303340
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2ceb490 VA: 0x7595303490
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2ceb5b4 VA: 0x75953035b4
	private IEnumerator _TweenAnimation(UIAnimationLocation anim, Boolean isInverse) { }
	// RVA: 0x2ceb044 VA: 0x7595303044
	private Void _ConfirmOutput() { }
	// RVA: 0x2cea938 VA: 0x7595302938
	private Void _Cancel() { }
	// RVA: 0x2ce93d4 VA: 0x75953013d4
	private Void _InitViews() { }
	// RVA: 0x2ceb6ac VA: 0x75953036ac
	private Void _BindCardGroup() { }
	// RVA: 0x2ceb864 VA: 0x7595303864
	private Void _BindSortPanel() { }
	// RVA: 0x2ceb970 VA: 0x7595303970
	private Void _PassDataToFilterState(UICharacterSortFilterStateBean sortFilterBean) { }
	// RVA: 0x2ceba60 VA: 0x7595303a60
	private Void _ReceiveDataFromFilterState(UICharacterSortFilterStateBean sortFilterBean) { }
	// RVA: 0x2cebb04 VA: 0x7595303b04
	public Void .ctor() { }
	// RVA: 0x2cebb74 VA: 0x7595303b74
	private Void <Awake>b__26_0(GameObject instObj) { }
	// RVA: 0x2cebc2c VA: 0x7595303c2c
	private Void <Awake>b__26_1() { }
	// RVA: 0x2cebc3c VA: 0x7595303c3c
	private Void <RegisterFromDataListener>b__31_0(IStateBean stateBean) { }
	// RVA: 0x2cebcbc VA: 0x7595303cbc
	private Void <RegisterToDataListener>b__32_0(IStateBean stateBean) { }
	// RVA: 0x2cebd3c VA: 0x7595303d3c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2cebd44 VA: 0x7595303d44
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2cebd4c VA: 0x7595303d4c
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2cebd54 VA: 0x7595303d54
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x2cebd5c VA: 0x7595303d5c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2cebd64 VA: 0x7595303d64
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2cebd6c VA: 0x7595303d6c
	private Void <>xLuaBaseProxy_DismissSelf() { }
}
```