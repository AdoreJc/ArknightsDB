# Act1LockMapState

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Boolean m_hasInited`

- `Act1LockZoneMapStateBean _stateBean`

- `Act1LockMapView _view`

- `Act1LockMapAdapter _mapAdapter`

- `Transform _detailViewContainer`

- `Act1LockNormalDetailView _normalViewPrefab`

- `Act1LockInterlockDetailView _interlockViewPrefab`

- `Act1LockFinalDetailView _finalViewPrefab`

- `RectTransform _topMenuContainer`

- `Act1LockNormalDetailView m_normalView`

- `Act1LockInterlockDetailView m_interlockView`

- `Act1LockFinalDetailView m_finalView`


## Methods

- `Void OnStageEventClick(String)`

- `Void CloseDetailView()`

- `Void AVGOnly_CloseDetailView()`

- `Void _OnEnemyHandBookOpen()`

- `Void _OnOpenRewardClick()`

- `Void _JumpToStageDetailView(String)`

- `Void _JumpToFinalDetailView()`

- `Void _UpdateAutoBattleStatus(String)`

- `Void _OnStartBattle()`

- `Void _OnStartPractice()`

- `Void _ToggleAutoBattle()`

- `Void _SetTopMenuActive(Boolean)`

- `Void _InitIfNot()`

- `Void _OnBackAction()`

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void _OnJumpToRewardDetailView(IStateBean)`

- `Void _OnInterlockDefendUpdate()`

- `Boolean _CheckCostBeforeStartBattle()`

- `Boolean _CheckApBeforeStartBattle(Int32)`

- `Void _LoadFromRuntime(StateRuntime)`

- `StateRuntime _SaveToRuntime()`

- `IEnumerator <>n__0()`

- `IEnumerator <>xLuaBaseProxy_OnPreload()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockMapState : State, IHotfixable
{
	private Boolean m_hasInited; // 0x50
	private Act1LockZoneMapStateBean _stateBean; // 0x58
	private Act1LockMapView _view; // 0x60
	private Act1LockMapAdapter _mapAdapter; // 0x68
	private Transform _detailViewContainer; // 0x70
	private Act1LockNormalDetailView _normalViewPrefab; // 0x78
	private Act1LockInterlockDetailView _interlockViewPrefab; // 0x80
	private Act1LockFinalDetailView _finalViewPrefab; // 0x88
	private RectTransform _topMenuContainer; // 0x90
	private Act1LockNormalDetailView m_normalView; // 0x98
	private Act1LockInterlockDetailView m_interlockView; // 0xa0
	private Act1LockFinalDetailView m_finalView; // 0xa8
	private StateCacheHandler`1 m_runtimeHandler; // 0xb0
	private static DelegateBridge __Hotfix0_OnPreload; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x18
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge __Hotfix0_OnStageEventClick; // 0x28
	private static DelegateBridge __Hotfix0_CloseDetailView; // 0x30
	private static DelegateBridge __Hotfix0_AVGOnly_CloseDetailView; // 0x38
	private static DelegateBridge __Hotfix0__OnEnemyHandBookOpen; // 0x40
	private static DelegateBridge __Hotfix0__OnOpenRewardClick; // 0x48
	private static DelegateBridge __Hotfix0__JumpToStageDetailView; // 0x50
	private static DelegateBridge __Hotfix0__JumpToFinalDetailView; // 0x58
	private static DelegateBridge __Hotfix0__UpdateAutoBattleStatus; // 0x60
	private static DelegateBridge __Hotfix0__OnStartBattle; // 0x68
	private static DelegateBridge __Hotfix0__OnStartPractice; // 0x70
	private static DelegateBridge __Hotfix0__ToggleAutoBattle; // 0x78
	private static DelegateBridge __Hotfix0__SetTopMenuActive; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x88
	private static DelegateBridge __Hotfix0__OnBackAction; // 0x90
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x98
	private static DelegateBridge __Hotfix0__OnJumpToRewardDetailView; // 0xa0
	private static DelegateBridge __Hotfix0__OnInterlockDefendUpdate; // 0xa8
	private static DelegateBridge __Hotfix0__CheckCostBeforeStartBattle; // 0xb0
	private static DelegateBridge __Hotfix0__CheckApBeforeStartBattle; // 0xb8
	private static DelegateBridge __Hotfix0__LoadFromRuntime; // 0xc0
	private static DelegateBridge __Hotfix0__SaveToRuntime; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x339ca04 VA: 0x75959b4a04
	protected override IEnumerator OnPreload() { }
	// RVA: 0x339cad8 VA: 0x75959b4ad8
	protected override Void OnEnter() { }
	// RVA: 0x339cb44 VA: 0x75959b4b44
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x339cd38 VA: 0x75959b4d38
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x339cebc VA: 0x75959b4ebc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x339cf24 VA: 0x75959b4f24
	public Void OnStageEventClick(String stageId) { }
	// RVA: 0x339d050 VA: 0x75959b5050
	public Void CloseDetailView() { }
	// RVA: 0x339ac40 VA: 0x75959b2c40
	public Void AVGOnly_CloseDetailView() { }
	// RVA: 0x339d2b8 VA: 0x75959b52b8
	private Void _OnEnemyHandBookOpen() { }
	// RVA: 0x339d3c0 VA: 0x75959b53c0
	private Void _OnOpenRewardClick() { }
	// RVA: 0x339cfa4 VA: 0x75959b4fa4
	private Void _JumpToStageDetailView(String stageId) { }
	// RVA: 0x339d580 VA: 0x75959b5580
	private Void _JumpToFinalDetailView() { }
	// RVA: 0x339d690 VA: 0x75959b5690
	private Void _UpdateAutoBattleStatus(String stageId) { }
	// RVA: 0x339d7f4 VA: 0x75959b57f4
	private Void _OnStartBattle() { }
	// RVA: 0x339d980 VA: 0x75959b5980
	private Void _OnStartPractice() { }
	// RVA: 0x339db00 VA: 0x75959b5b00
	private Void _ToggleAutoBattle() { }
	// RVA: 0x339dbc4 VA: 0x75959b5bc4
	private Void _SetTopMenuActive(Boolean isActive) { }
	// RVA: 0x339dc58 VA: 0x75959b5c58
	private Void _InitIfNot() { }
	// RVA: 0x339ee40 VA: 0x75959b6e40
	private Void _OnBackAction() { }
	// RVA: 0x339ef40 VA: 0x75959b6f40
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x339f54c VA: 0x75959b754c
	private Void _OnJumpToRewardDetailView(IStateBean stateBean) { }
	// RVA: 0x339f690 VA: 0x75959b7690
	private Void _OnInterlockDefendUpdate() { }
	// RVA: 0x339d8ec VA: 0x75959b58ec
	private Boolean _CheckCostBeforeStartBattle() { }
	// RVA: 0x339f7cc VA: 0x75959b77cc
	private Boolean _CheckApBeforeStartBattle(Int32 apCost) { }
	// RVA: 0x339f948 VA: 0x75959b7948
	private Void _LoadFromRuntime(StateRuntime runtime) { }
	// RVA: 0x339fa08 VA: 0x75959b7a08
	private StateRuntime _SaveToRuntime() { }
	// RVA: 0x339fad0 VA: 0x75959b7ad0
	public Void .ctor() { }
	// RVA: 0x339fb40 VA: 0x75959b7b40
	private IEnumerator <>n__0() { }
	// RVA: 0x339fb48 VA: 0x75959b7b48
	private IEnumerator <>xLuaBaseProxy_OnPreload() { }
	// RVA: 0x339fb50 VA: 0x75959b7b50
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x339fb58 VA: 0x75959b7b58
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x339fb60 VA: 0x75959b7b60
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
}
```