# MedalPage

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalStateAnimationHolder _animationHolder`

- `PrefabInstHolder _topMenuHolder`

- `MedalListStateBean _listStateBean`

- `MedalShowTypeFilterView _showTypeFilter`

- `MedalHideExpireSwitch _hideExpireSwitchPrefab`

- `ReentrantFloatRef m_globalBlackMask`

- `OnStateChangeListener m_stateChangeListener`


## Methods

- `Void _ReturnPage()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _OnRouteToState(Type)`

- `Void _UpdateListTopBarStatus(Boolean, Boolean)`

- `Void OnChangeStateClick()`

- `IEnumerator _JumpToMedalGroupPage()`

- `IEnumerator _JumpToMedalBarListGroupPage(String)`

- `IEnumerator _JumpToMedalListItem(String)`

- `Void JumpToMedalBarListGroup(String)`

- `Void JumpToMedalListItem(String)`

- `IEnumerator _ResetToBarList(String)`

- `IEnumerator _ResetToMedalList(String)`

- `IEnumerator _JumpToMedalGroupPage(String)`

- `Void JumpToMedalGroupList(String)`

- `IEnumerator _ResetToGroupList(String)`

- `Void _OnShowTypeFilterClicked(MedalBarListShowType)`

- `Void _OnHideExpiredToggleClicked()`

- `Void ChangeMedalShowTypeAndRefreshViews(MedalBarListShowType, Boolean)`

- `Void _ApplyMedalShowType(ListFilter)`

- `Void _CloseDetailViewsIfNeeded()`

- `Void _OnListFilterChanged()`

- `IEnumerator _ShowGlobalBlackLoading()`

- `Void _ReleaseGlobalBlackLoading()`

- `Void <_OnInitTopMenu>b__12_0()`

- `Void <OnStateEngineReady>b__15_0(Type, Type, Additions)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Void <>xLuaBaseProxy_OnStateEngineReady(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalPage : StateEnginePage
{
	private MedalStateAnimationHolder _animationHolder; // 0xe8
	private PrefabInstHolder _topMenuHolder; // 0xf0
	private MedalListStateBean _listStateBean; // 0xf8
	private MedalShowTypeFilterView _showTypeFilter; // 0x100
	private List`1 _hideExpireSwitchHolders; // 0x108
	private MedalHideExpireSwitch _hideExpireSwitchPrefab; // 0x110
	private List`1 m_hideExpireSwitches; // 0x118
	private ReentrantFloatRef m_globalBlackMask; // 0x120
	private OnStateChangeListener m_stateChangeListener; // 0x128
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0__ReturnPage; // 0x10
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x18
	private static DelegateBridge __Hotfix0_OnAnimationStateSetStatic; // 0x20
	private static DelegateBridge __Hotfix0_OnStateEngineReady; // 0x28
	private static DelegateBridge __Hotfix0__OnRouteToState; // 0x30
	private static DelegateBridge __Hotfix0__UpdateListTopBarStatus; // 0x38
	private static DelegateBridge __Hotfix0_OnChangeStateClick; // 0x40
	private static DelegateBridge __Hotfix0__JumpToMedalGroupPage; // 0x48
	private static DelegateBridge __Hotfix0__JumpToMedalBarListGroupPage; // 0x50
	private static DelegateBridge __Hotfix0__JumpToMedalListItem; // 0x58
	private static DelegateBridge __Hotfix0_JumpToMedalBarListGroup; // 0x60
	private static DelegateBridge __Hotfix0_JumpToMedalListItem; // 0x68
	private static DelegateBridge __Hotfix0__ResetToBarList; // 0x70
	private static DelegateBridge __Hotfix0__ResetToMedalList; // 0x78
	private static DelegateBridge __Hotfix1__JumpToMedalGroupPage; // 0x80
	private static DelegateBridge __Hotfix0_JumpToMedalGroupList; // 0x88
	private static DelegateBridge __Hotfix0__ResetToGroupList; // 0x90
	private static DelegateBridge __Hotfix0__OnShowTypeFilterClicked; // 0x98
	private static DelegateBridge __Hotfix0__OnHideExpiredToggleClicked; // 0xa0
	private static DelegateBridge __Hotfix0_ChangeMedalShowTypeAndRefreshViews; // 0xa8
	private static DelegateBridge __Hotfix0__ApplyMedalShowType; // 0xb0
	private static DelegateBridge __Hotfix0__CloseDetailViewsIfNeeded; // 0xb8
	private static DelegateBridge __Hotfix0__OnListFilterChanged; // 0xc0
	private static DelegateBridge __Hotfix0__ShowGlobalBlackLoading; // 0xc8
	private static DelegateBridge __Hotfix0__ReleaseGlobalBlackLoading; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8


	// RVA: 0x2791500 VA: 0x7594da9500
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2791864 VA: 0x7594da9864
	protected override Void OnDestroy() { }
	// RVA: 0x2791954 VA: 0x7594da9954
	private Void _ReturnPage() { }
	// RVA: 0x2791de4 VA: 0x7594da9de4
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x2791f2c VA: 0x7594da9f2c
	public static Void OnAnimationStateSetStatic(State state, Boolean active, Boolean isList) { }
	// RVA: 0x2792104 VA: 0x7594daa104
	protected override Void OnStateEngineReady(Boolean isFromStack) { }
	// RVA: 0x27922cc VA: 0x7594daa2cc
	private Void _OnRouteToState(Type stateType) { }
	// RVA: 0x2792050 VA: 0x7594daa050
	private Void _UpdateListTopBarStatus(Boolean enableTopBar, Boolean isBarList) { }
	// RVA: 0x27926e8 VA: 0x7594daa6e8
	public Void OnChangeStateClick() { }
	// RVA: 0x2792864 VA: 0x7594daa864
	private IEnumerator _JumpToMedalGroupPage() { }
	// RVA: 0x2792928 VA: 0x7594daa928
	private IEnumerator _JumpToMedalBarListGroupPage(String groupId) { }
	// RVA: 0x2792a20 VA: 0x7594daaa20
	private IEnumerator _JumpToMedalListItem(String medalId) { }
	// RVA: 0x2792b18 VA: 0x7594daab18
	public Void JumpToMedalBarListGroup(String groupId) { }
	// RVA: 0x2792c78 VA: 0x7594daac78
	public Void JumpToMedalListItem(String medalId) { }
	// RVA: 0x2792ba8 VA: 0x7594daaba8
	private IEnumerator _ResetToBarList(String groupId) { }
	// RVA: 0x2792d08 VA: 0x7594daad08
	private IEnumerator _ResetToMedalList(String medalId) { }
	// RVA: 0x2792e28 VA: 0x7594daae28
	private IEnumerator _JumpToMedalGroupPage(String groupId) { }
	// RVA: 0x2792f20 VA: 0x7594daaf20
	public Void JumpToMedalGroupList(String groupId) { }
	// RVA: 0x2792fb0 VA: 0x7594daafb0
	private IEnumerator _ResetToGroupList(String groupId) { }
	// RVA: 0x27930a8 VA: 0x7594dab0a8
	private Void _OnShowTypeFilterClicked(MedalBarListShowType showType) { }
	// RVA: 0x2793288 VA: 0x7594dab288
	private Void _OnHideExpiredToggleClicked() { }
	// RVA: 0x279332c VA: 0x7594dab32c
	public Void ChangeMedalShowTypeAndRefreshViews(MedalBarListShowType showType, Boolean addFilterVersion) { }
	// RVA: 0x2793150 VA: 0x7594dab150
	private Void _ApplyMedalShowType(ListFilter filter) { }
	// RVA: 0x27933e0 VA: 0x7594dab3e0
	private Void _CloseDetailViewsIfNeeded() { }
	// RVA: 0x27934c8 VA: 0x7594dab4c8
	private Void _OnListFilterChanged() { }
	// RVA: 0x27936f0 VA: 0x7594dab6f0
	private IEnumerator _ShowGlobalBlackLoading() { }
	// RVA: 0x27918d8 VA: 0x7594da98d8
	private Void _ReleaseGlobalBlackLoading() { }
	// RVA: 0x27937c4 VA: 0x7594dab7c4
	public Void .ctor() { }
	// RVA: 0x2793888 VA: 0x7594dab888
	private Void <_OnInitTopMenu>b__12_0() { }
	// RVA: 0x279388c VA: 0x7594dab88c
	private Void <OnStateEngineReady>b__15_0(Type from, Type to, Additions add) { }
	// RVA: 0x2793894 VA: 0x7594dab894
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x279389c VA: 0x7594dab89c
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x27938a4 VA: 0x7594dab8a4
	private Void <>xLuaBaseProxy_OnStateEngineReady(Boolean P0) { }
}
```