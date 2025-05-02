# CharmSquadState

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `RectTransform _topMenuContainer`

- `RectTransform _holdRoot`

- `CharmHole _holePrefab`

- `MultiStateToggleGroup _sortToggles`

- `CharmListAdapter _charmList`

- `Button _saveBtn`


## Methods

- `Void _RaiseSignalCharmRepoRouted()`

- `Void _Refresh()`

- `Void _UpdateSelectStatus(Boolean)`

- `Int32 _GetCharmIdxByType(String)`

- `Void _InitIfNot()`

- `Void _HandleSortTypeChanged(String)`

- `Int32 _Sort(CharmModel, CharmModel)`

- `Void _HandleSelectChanged(CharmCard)`

- `Void _RaiseAVGSignal()`

- `Void _RemoveSelect(Int32)`

- `Void _HandleBack()`

- `Void _DoBack()`

- `Void EventOnSave()`

- `Void EventOnClear()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmSquadState : PopupFadeState
{
	private RectTransform _topMenuContainer; // 0x70
	private RectTransform _holdRoot; // 0x78
	private CharmHole _holePrefab; // 0x80
	private MultiStateToggleGroup _sortToggles; // 0x88
	private CharmListAdapter _charmList; // 0x90
	private Button _saveBtn; // 0x98
	private const Int32 CHARM_SQUAD_HOLE_NUM; // 0x0
	private CharmHole[] m_holes; // 0xa0
	private List`1 m_charms; // 0xa8
	private List`1 m_showList; // 0xb0
	private List`1 m_seleted; // 0xb8
	private static String s_preSort; // 0x0
	private Comparison`1 m_sortFunc; // 0xc0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__RaiseSignalCharmRepoRouted; // 0x18
	private static DelegateBridge __Hotfix0__Refresh; // 0x20
	private static DelegateBridge __Hotfix0__UpdateSelectStatus; // 0x28
	private static DelegateBridge __Hotfix0__GetCharmIdxByType; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x40
	private static DelegateBridge __Hotfix0__HandleSortTypeChanged; // 0x48
	private static DelegateBridge __Hotfix0__Sort; // 0x50
	private static DelegateBridge __Hotfix0__HandleSelectChanged; // 0x58
	private static DelegateBridge __Hotfix0__RaiseAVGSignal; // 0x60
	private static DelegateBridge __Hotfix0__RemoveSelect; // 0x68
	private static DelegateBridge __Hotfix0__HandleBack; // 0x70
	private static DelegateBridge __Hotfix0__DoBack; // 0x78
	private static DelegateBridge __Hotfix0_EventOnSave; // 0x80
	private static DelegateBridge __Hotfix0_EventOnClear; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x34576f0 VA: 0x7595a6f6f0
	protected override Void OnEnter() { }
	// RVA: 0x3457ea4 VA: 0x7595a6fea4
	protected override Void OnResume() { }
	// RVA: 0x34582b4 VA: 0x7595a702b4
	private Void _RaiseSignalCharmRepoRouted() { }
	// RVA: 0x3457f0c VA: 0x7595a6ff0c
	private Void _Refresh() { }
	// RVA: 0x3458318 VA: 0x7595a70318
	private Void _UpdateSelectStatus(Boolean resort) { }
	// RVA: 0x3458568 VA: 0x7595a70568
	private Int32 _GetCharmIdxByType(String charmType) { }
	// RVA: 0x3457758 VA: 0x7595a6f758
	private Void _InitIfNot() { }
	// RVA: 0x345865c VA: 0x7595a7065c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x34586c0 VA: 0x7595a706c0
	private Void _HandleSortTypeChanged(String stateId) { }
	// RVA: 0x345876c VA: 0x7595a7076c
	private Int32 _Sort(CharmModel c1, CharmModel c2) { }
	// RVA: 0x3458840 VA: 0x7595a70840
	private Void _HandleSelectChanged(CharmCard card) { }
	// RVA: 0x3458af8 VA: 0x7595a70af8
	private Void _RaiseAVGSignal() { }
	// RVA: 0x3458b5c VA: 0x7595a70b5c
	private Void _RemoveSelect(Int32 idx) { }
	// RVA: 0x3458c78 VA: 0x7595a70c78
	private Void _HandleBack() { }
	// RVA: 0x345906c VA: 0x7595a7106c
	private Void _DoBack() { }
	// RVA: 0x3459144 VA: 0x7595a71144
	public Void EventOnSave() { }
	// RVA: 0x34594c0 VA: 0x7595a714c0
	public Void EventOnClear() { }
	// RVA: 0x34595e0 VA: 0x7595a715e0
	public Void .ctor() { }
	// RVA: 0x34596a8 VA: 0x7595a716a8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x34596b0 VA: 0x7595a716b0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```