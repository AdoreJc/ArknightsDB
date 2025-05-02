# CharmRepositoryState

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `RectTransform _topMenuContainer`

- `GameObject _introduce`

- `Text _ownedNumLabel`

- `Text _totalNumLabel`

- `CharmDetailView _detailView`

- `CharmSquadSimpleView _charmSquad`

- `MultiStateToggleGroup _sortToggles`

- `MultiStateToggleGroup _filterToggles`

- `CharmListAdapter _charmList`

- `GameObject _getAllFlag`

- `String _guidebookSubSignal`

- `GameObject _recycleStat`

- `Text _recycleTotalCoin`

- `Text _recycleCnt`

- `AnimationWrapper _animWrapper`

- `AnimationWrapper _leftAnim`

- `CharmFilterType m_filterType`

- `CharmModel m_selectedCharm`

- `String m_activityID`

- `Int32 m_recycleCnt`

- `Boolean m_updated`


## Methods

- `Void _UpdateView()`

- `Void _PlayRecycleBtnLoop()`

- `Void _RefreshCharmList()`

- `Void _InitIfNot()`

- `Void _CheckNewUnlock()`

- `Void _HandleSortTypeChanged(String)`

- `Void _HandleFilterTypeChanged(String)`

- `Void _HandleCharmSelectChanged(CharmCard)`

- `Void _UpdateSelectView()`

- `Void EventOnUpdateDetail()`

- `Void EventOnEnterCharmSquad()`

- `Void EventOnEnterRecycle()`

- `String _GetTheActivityOpenedMe()`

- `Void <_InitIfNot>b__34_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmRepositoryState : PopupFadeState
{
	private RectTransform _topMenuContainer; // 0x70
	private GameObject _introduce; // 0x78
	private Text _ownedNumLabel; // 0x80
	private Text _totalNumLabel; // 0x88
	private CharmDetailView _detailView; // 0x90
	private CharmSquadSimpleView _charmSquad; // 0x98
	private MultiStateToggleGroup _sortToggles; // 0xa0
	private MultiStateToggleGroup _filterToggles; // 0xa8
	private CharmListAdapter _charmList; // 0xb0
	private GameObject _getAllFlag; // 0xb8
	private String _guidebookSubSignal; // 0xc0
	private GameObject _recycleStat; // 0xc8
	private Text _recycleTotalCoin; // 0xd0
	private Text _recycleCnt; // 0xd8
	private AnimationWrapper _animWrapper; // 0xe0
	private AnimationWrapper _leftAnim; // 0xe8
	private const String ANIM_ENTRY; // 0x0
	private const String ANIM_RECYCLE_BTN_LOOP; // 0x0
	private const String ANIM_INTRO_TO_DETAIL; // 0x0
	private const String ANIM_DETAIL_TO_INTRO; // 0x0
	private const String ANIM_DETAIL_SWITCH; // 0x0
	private List`1 m_charmModels; // 0xf0
	private List`1 m_showList; // 0xf8
	private Comparison`1 m_sortFunc; // 0x100
	private CharmFilterType m_filterType; // 0x108
	private CharmModel m_selectedCharm; // 0x110
	private String m_activityID; // 0x118
	private Int32 m_recycleCnt; // 0x120
	private Boolean m_updated; // 0x124
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0__UpdateView; // 0x10
	private static DelegateBridge __Hotfix0__PlayRecycleBtnLoop; // 0x18
	private static DelegateBridge __Hotfix0__RefreshCharmList; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__CheckNewUnlock; // 0x30
	private static DelegateBridge __Hotfix0__HandleSortTypeChanged; // 0x38
	private static DelegateBridge __Hotfix0__HandleFilterTypeChanged; // 0x40
	private static DelegateBridge __Hotfix0__HandleCharmSelectChanged; // 0x48
	private static DelegateBridge __Hotfix0__UpdateSelectView; // 0x50
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x58
	private static DelegateBridge __Hotfix0_EventOnUpdateDetail; // 0x60
	private static DelegateBridge __Hotfix0_EventOnEnterCharmSquad; // 0x68
	private static DelegateBridge __Hotfix0_EventOnEnterRecycle; // 0x70
	private static DelegateBridge __Hotfix0__GetTheActivityOpenedMe; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x3454d54 VA: 0x7595a6cd54
	protected override Void OnEnter() { }
	// RVA: 0x3455488 VA: 0x7595a6d488
	protected override Void OnResume() { }
	// RVA: 0x34553d0 VA: 0x7595a6d3d0
	private Void _UpdateView() { }
	// RVA: 0x3455538 VA: 0x7595a6d538
	private Void _PlayRecycleBtnLoop() { }
	// RVA: 0x345577c VA: 0x7595a6d77c
	private Void _RefreshCharmList() { }
	// RVA: 0x3454e6c VA: 0x7595a6ce6c
	private Void _InitIfNot() { }
	// RVA: 0x3455da4 VA: 0x7595a6dda4
	private Void _CheckNewUnlock() { }
	// RVA: 0x3456474 VA: 0x7595a6e474
	private Void _HandleSortTypeChanged(String stateId) { }
	// RVA: 0x3456534 VA: 0x7595a6e534
	private Void _HandleFilterTypeChanged(String stateID) { }
	// RVA: 0x34565bc VA: 0x7595a6e5bc
	private Void _HandleCharmSelectChanged(CharmCard card) { }
	// RVA: 0x34555e4 VA: 0x7595a6d5e4
	private Void _UpdateSelectView() { }
	// RVA: 0x3456780 VA: 0x7595a6e780
	public override IStateBean GetCacheBean() { }
	// RVA: 0x34566f8 VA: 0x7595a6e6f8
	public Void EventOnUpdateDetail() { }
	// RVA: 0x34567e4 VA: 0x7595a6e7e4
	public Void EventOnEnterCharmSquad() { }
	// RVA: 0x3456864 VA: 0x7595a6e864
	public Void EventOnEnterRecycle() { }
	// RVA: 0x345609c VA: 0x7595a6e09c
	private String _GetTheActivityOpenedMe() { }
	// RVA: 0x3456970 VA: 0x7595a6e970
	public Void .ctor() { }
	// RVA: 0x34569e0 VA: 0x7595a6e9e0
	private Void <_InitIfNot>b__34_0() { }
	// RVA: 0x34569f0 VA: 0x7595a6e9f0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x34569f8 VA: 0x7595a6e9f8
	private Void <>xLuaBaseProxy_OnResume() { }
}
```