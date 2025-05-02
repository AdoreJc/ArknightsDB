# BuildingStationSelectState

**Namespace:** `Torappu.Building.UI`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `BuildingStationSelectCharList _charList`

- `BuildingStationSelectRoomInfoView _roomInfo`

- `BuildingStationSelectCharInfoView _charInfo`

- `BuildingStationSelectSortBar _sortBar`

- `BuildingStationSelectBuffList _buffList`

- `BuildingStationSelectContentController _contentController`

- `GameObject _btnClear`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _exitAnim`

- `BuildingStationSelectMaskPlugin _stationSelectionPluginPrefab`

- `BuildingStationCharacterSortFilterPanelBinder _sortFilterPanelBinder`

- `UIAnimationLocation _filterAnimLoc`

- `GameObject _panelLockSelectInfo`

- `TwoStateToggle _confirmBtnStateToggle`

- `StationSelectStateBean m_stateBean`

- `AnimationSwitchTween m_filterSwitchAnim`

- `IntHashSet m_cachedConfirmPreQueueHash`


## Properties

- `IPlugin plugin`


## Methods

- `Void Start()`

- `Void EventOnShowFilterBar()`

- `Void EventOnFilter(CharacterFilterViewModel)`

- `Void EventOnConfirmClicked()`

- `Void EventOnClearClicked()`

- `IPlugin get_plugin()`

- `Void _TryUpdateFilterPanelShow(Boolean)`

- `AnimationSwitchTween _EnsureSortPanelSwitchAnim()`

- `Void _OnSortPanelSwitch(Boolean)`

- `Void _BindSortFilter()`

- `Void _RefreshPanelSwitch()`

- `Void _DefaultEventOnConfirmClicked()`

- `SelectDormLockCharResult _CheckWillDormLockCharMove(BuildingModel, RoomSlotModel, List`1)`

- `Void _OnJumpToSelectConfirmState(StationSelectConfirmStateBean)`

- `Void _OnJumpBackFromSelectConfirmState(StationSelectConfirmStateBean)`

- `Void _OnCharClicked(StationCharViewModel)`

- `SelectResultModel _GenSelectedCharForRequest()`

- `Void _OnSortItemClicked(CharSortType)`

- `Void _OnFilterShowHideClicked(Boolean)`

- `Void _OnFilterItemClicked(CharStationFilterType)`

- `IEnumerator _TweenAnimation(UIAnimationLocation)`

- `StationCharViewModel GetCharSelectMutuallyExclusiveInfo(Int32, StationSelectStateBean)`

- `StationCharViewModel GetCharSelectMutuallyExclusiveInfo(Int32, StationSelectStateBean, StationCharGroupViewModel)`

- `Boolean CheckIfCharValid(Int32)`

- `Void <Start>b__26_0(GameObject)`

- `Void <Start>b__26_1()`

- `Void <RegisterToDataListener>b__28_0(IStateBean)`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingStationSelectState : UIPopupState, IBuildingSelectController
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x60
	private BuildingStationSelectCharList _charList; // 0x68
	private BuildingStationSelectRoomInfoView _roomInfo; // 0x70
	private BuildingStationSelectCharInfoView _charInfo; // 0x78
	private BuildingStationSelectSortBar _sortBar; // 0x80
	private BuildingStationSelectBuffList _buffList; // 0x88
	private BuildingStationSelectContentController _contentController; // 0x90
	private GameObject _btnClear; // 0x98
	private UIAnimationLocation _enterAnim; // 0xa0
	private UIAnimationLocation _exitAnim; // 0xb0
	private BuildingStationSelectMaskPlugin _stationSelectionPluginPrefab; // 0xc0
	private BuildingStationCharacterSortFilterPanelBinder _sortFilterPanelBinder; // 0xc8
	private UIAnimationLocation _filterAnimLoc; // 0xd0
	private GameObject _panelLockSelectInfo; // 0xe0
	private TwoStateToggle _confirmBtnStateToggle; // 0xe8
	private StationSelectStateBean m_stateBean; // 0xf0
	private AnimationSwitchTween m_filterSwitchAnim; // 0xf8
	private List`1 m_tempListForExclusiveInstIds; // 0x100
	private IntHashSet m_cachedConfirmPreQueueHash; // 0x108
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge __Hotfix0_EventOnShowFilterBar; // 0x30
	private static DelegateBridge __Hotfix0_EventOnFilter; // 0x38
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x40
	private static DelegateBridge __Hotfix0_EventOnClearClicked; // 0x48
	private static DelegateBridge __Hotfix0_get_plugin; // 0x50
	private static DelegateBridge __Hotfix0__TryUpdateFilterPanelShow; // 0x58
	private static DelegateBridge __Hotfix0__EnsureSortPanelSwitchAnim; // 0x60
	private static DelegateBridge __Hotfix0__OnSortPanelSwitch; // 0x68
	private static DelegateBridge __Hotfix0__BindSortFilter; // 0x70
	private static DelegateBridge __Hotfix0__RefreshPanelSwitch; // 0x78
	private static DelegateBridge __Hotfix0__DefaultEventOnConfirmClicked; // 0x80
	private static DelegateBridge __Hotfix0__CheckWillDormLockCharMove; // 0x88
	private static DelegateBridge __Hotfix0__OnJumpToSelectConfirmState; // 0x90
	private static DelegateBridge __Hotfix0__OnJumpBackFromSelectConfirmState; // 0x98
	private static DelegateBridge __Hotfix0__OnCharClicked; // 0xa0
	private static DelegateBridge __Hotfix0__GenSelectedCharForRequest; // 0xa8
	private static DelegateBridge __Hotfix0__OnSortItemClicked; // 0xb0
	private static DelegateBridge __Hotfix0__OnFilterShowHideClicked; // 0xb8
	private static DelegateBridge __Hotfix0__OnFilterItemClicked; // 0xc0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0xc8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0xd0
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0xd8
	private static DelegateBridge __Hotfix0_HideImmediately; // 0xe0
	private static DelegateBridge __Hotfix0__TweenAnimation; // 0xe8
	private static DelegateBridge __Hotfix0_GetCharSelectMutuallyExclusiveInfo; // 0xf0
	private static DelegateBridge __Hotfix1_GetCharSelectMutuallyExclusiveInfo; // 0xf8
	private static DelegateBridge __Hotfix0_GetTempListForExclusiveInstIds; // 0x100
	private static DelegateBridge __Hotfix0_CheckIfCharValid; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110

	protected IPlugin plugin { get; }

	// RVA: 0x3d571d8 VA: 0x759636f1d8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d57240 VA: 0x759636f240
	private Void Start() { }
	// RVA: 0x3d57304 VA: 0x759636f304
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x3d5737c VA: 0x759636f37c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3d574f4 VA: 0x759636f4f4
	protected override Void OnEnter() { }
	// RVA: 0x3d57bb4 VA: 0x759636fbb4
	protected override Void OnResume() { }
	// RVA: 0x3d57c28 VA: 0x759636fc28
	public Void EventOnShowFilterBar() { }
	// RVA: 0x3d57d44 VA: 0x759636fd44
	public Void EventOnFilter(CharacterFilterViewModel filterModel) { }
	// RVA: 0x3d57e3c VA: 0x759636fe3c
	public Void EventOnConfirmClicked() { }
	// RVA: 0x3d5839c VA: 0x759637039c
	public Void EventOnClearClicked() { }
	// RVA: 0x3d57980 VA: 0x759636f980
	protected IPlugin get_plugin() { }
	// RVA: 0x3d58410 VA: 0x7596370410
	private Void _TryUpdateFilterPanelShow(Boolean isFilterPanelShow) { }
	// RVA: 0x3d584b4 VA: 0x75963704b4
	private AnimationSwitchTween _EnsureSortPanelSwitchAnim() { }
	// RVA: 0x3d57c94 VA: 0x759636fc94
	private Void _OnSortPanelSwitch(Boolean isShow) { }
	// RVA: 0x3d579f4 VA: 0x759636f9f4
	private Void _BindSortFilter() { }
	// RVA: 0x3d57b00 VA: 0x759636fb00
	private Void _RefreshPanelSwitch() { }
	// RVA: 0x3d57f9c VA: 0x759636ff9c
	private Void _DefaultEventOnConfirmClicked() { }
	// RVA: 0x3d58738 VA: 0x7596370738
	private SelectDormLockCharResult _CheckWillDormLockCharMove(BuildingModel buildingModel, RoomSlotModel slotModel, List`1 selectedChars) { }
	// RVA: 0x3d58aac VA: 0x7596370aac
	private Void _OnJumpToSelectConfirmState(StationSelectConfirmStateBean selectConfirmBean) { }
	// RVA: 0x3d58e78 VA: 0x7596370e78
	private Void _OnJumpBackFromSelectConfirmState(StationSelectConfirmStateBean selectConfirmBean) { }
	// RVA: 0x3d58f24 VA: 0x7596370f24
	private Void _OnCharClicked(StationCharViewModel clickedChar) { }
	// RVA: 0x3d585a4 VA: 0x75963705a4
	private SelectResultModel _GenSelectedCharForRequest() { }
	// RVA: 0x3d590a0 VA: 0x75963710a0
	private Void _OnSortItemClicked(CharSortType sortType) { }
	// RVA: 0x3d5912c VA: 0x759637112c
	private Void _OnFilterShowHideClicked(Boolean isShow) { }
	// RVA: 0x3d591b8 VA: 0x75963711b8
	private Void _OnFilterItemClicked(CharStationFilterType stationFilterType) { }
	// RVA: 0x3d59244 VA: 0x7596371244
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x3d593bc VA: 0x75963713bc
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x3d59534 VA: 0x7596371534
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x3d59658 VA: 0x7596371658
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x3d5977c VA: 0x759637177c
	private IEnumerator _TweenAnimation(UIAnimationLocation anim) { }
	// RVA: 0x3d59880 VA: 0x7596371880
	public StationCharViewModel GetCharSelectMutuallyExclusiveInfo(Int32 instId, StationSelectStateBean stationSelectBean) { }
	// RVA: 0x3d5992c VA: 0x759637192c
	public StationCharViewModel GetCharSelectMutuallyExclusiveInfo(Int32 instId, StationSelectStateBean selectStateBean, StationCharGroupViewModel groupViewModel) { }
	// RVA: 0x3d59ca4 VA: 0x7596371ca4
	public List`1 GetTempListForExclusiveInstIds() { }
	// RVA: 0x3d59d0c VA: 0x7596371d0c
	public Boolean CheckIfCharValid(Int32 instId) { }
	// RVA: 0x3d59f98 VA: 0x7596371f98
	public Void .ctor() { }
	// RVA: 0x3d5a0d4 VA: 0x75963720d4
	private Void <Start>b__26_0(GameObject obj) { }
	// RVA: 0x3d5a198 VA: 0x7596372198
	private Void <Start>b__26_1() { }
	// RVA: 0x3d5a1b8 VA: 0x75963721b8
	private Void <RegisterToDataListener>b__28_0(IStateBean stateBean) { }
	// RVA: 0x3d5a238 VA: 0x7596372238
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x3d5a240 VA: 0x7596372240
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3d5a248 VA: 0x7596372248
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d5a250 VA: 0x7596372250
	private Void <>xLuaBaseProxy_OnResume() { }
}
```