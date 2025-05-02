# Act13sideDailyMissionSearchState

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Act13sideDailyMissionSearchView _view`

- `RectTransform _backBtnRt`

- `Boolean m_hasInited`

- `Boolean m_needShowRefreshAnim`

- `Act13sideDailyMissionSearchStateBean m_stateBean`


## Methods

- `Void _RaiseTutorialSignal()`

- `Void _JumpToPoolState(IStateBean)`

- `Void _InitIfNot()`

- `Void _OnOrgSelected(String)`

- `Void _OnMatSelected(ItemBundle)`

- `Void _SendBtnSearchRequest()`

- `Void OnBtnRandomOrg()`

- `Void OnBtnRandomMat()`

- `Void OnBtnSearch()`

- `Void <_SendBtnSearchRequest>b__14_0(Act13SideDailyMissionSearchResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionSearchState : PopupFloatState
{
	private Act13sideDailyMissionSearchView _view; // 0x70
	private RectTransform _backBtnRt; // 0x78
	private Boolean m_hasInited; // 0x80
	private Boolean m_needShowRefreshAnim; // 0x81
	private Act13sideDailyMissionSearchStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__RaiseTutorialSignal; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__JumpToPoolState; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnOrgSelected; // 0x38
	private static DelegateBridge __Hotfix0__OnMatSelected; // 0x40
	private static DelegateBridge __Hotfix0__SendBtnSearchRequest; // 0x48
	private static DelegateBridge __Hotfix0_OnBtnRandomOrg; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnRandomMat; // 0x58
	private static DelegateBridge __Hotfix0_OnBtnSearch; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x342b858 VA: 0x7595a43858
	public override IStateBean GetCacheBean() { }
	// RVA: 0x342b8c0 VA: 0x7595a438c0
	protected override Void OnEnter() { }
	// RVA: 0x342bb40 VA: 0x7595a43b40
	protected override Void OnResume() { }
	// RVA: 0x342bbb4 VA: 0x7595a43bb4
	private Void _RaiseTutorialSignal() { }
	// RVA: 0x342bc18 VA: 0x7595a43c18
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x342bd90 VA: 0x7595a43d90
	private Void _JumpToPoolState(IStateBean stateBean) { }
	// RVA: 0x342b968 VA: 0x7595a43968
	private Void _InitIfNot() { }
	// RVA: 0x342be9c VA: 0x7595a43e9c
	private Void _OnOrgSelected(String orgId) { }
	// RVA: 0x342bf98 VA: 0x7595a43f98
	private Void _OnMatSelected(ItemBundle itemBundle) { }
	// RVA: 0x342c0a4 VA: 0x7595a440a4
	private Void _SendBtnSearchRequest() { }
	// RVA: 0x342c380 VA: 0x7595a44380
	public Void OnBtnRandomOrg() { }
	// RVA: 0x342c408 VA: 0x7595a44408
	public Void OnBtnRandomMat() { }
	// RVA: 0x342c474 VA: 0x7595a44474
	public Void OnBtnSearch() { }
	// RVA: 0x342c744 VA: 0x7595a44744
	public Void .ctor() { }
	// RVA: 0x342c7f0 VA: 0x7595a447f0
	private Void <_SendBtnSearchRequest>b__14_0(Act13SideDailyMissionSearchResponse response) { }
	// RVA: 0x342c808 VA: 0x7595a44808
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x342c810 VA: 0x7595a44810
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x342c818 VA: 0x7595a44818
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```