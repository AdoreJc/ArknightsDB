# ClimbTowerController

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `PrefabInstHolder _menuHolder`

- `StateEngine _stateEngine`

- `UICommonPageEffectHolder _effectHolder`

- `GameObject _pnlTrapOrSquadBack`

- `String m_towerId`

- `ClimbTowerMenu m_menu`

- `ClimbTowerProperty m_towerProperty`

- `ClimbTowerItemRewardProperty m_itemRewardProperty`

- `Boolean _pnlTrapOrSquadShow`

- `OnStateChangeListener m_stateEngineListener`

- `Boolean m_isTutorial`

- `Boolean <squadEditStateForceOpen>k__BackingField`


## Properties

- `String towerId`

- `ClimbTowerProperty towerProperty`

- `ClimbTowerItemRewardProperty itemRewardProperty`

- `Boolean squadEditStateForceOpen`

- `Boolean isTutorialTower`


## Methods

- `String get_towerId()`

- `ClimbTowerProperty get_towerProperty()`

- `ClimbTowerItemRewardProperty get_itemRewardProperty()`

- `Boolean get_squadEditStateForceOpen()`

- `Void set_squadEditStateForceOpen(Boolean)`

- `Boolean get_isTutorialTower()`

- `Void RegisterMenuAdapter(ClimbTowerMenuAdapter)`

- `Boolean ValidateBottomMenu()`

- `IEnumerator EnsureBottomMenu()`

- `Boolean IsEnterStateShowing()`

- `Void SaveTowerSelectModeToCache()`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void _OnMenuCreated(GameObject)`

- `Void _OnStateEnter(Type, Additions)`

- `Void _OnStateResume(Type, Boolean, Additions)`

- `Void _OnStatePause(Type, Additions)`

- `Void _OnBeforeTransition(Type, Type, Additions)`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerController : PageSingleComponent, IPlayerDataListener, IHotfixable
{
	private static readonly Type[] TRAP_AND_SQUAD_RELATED_STATES; // 0x0
	private PrefabInstHolder _menuHolder; // 0x20
	private StateEngine _stateEngine; // 0x28
	private UICommonPageEffectHolder _effectHolder; // 0x30
	private GameObject _pnlTrapOrSquadBack; // 0x38
	private String m_towerId; // 0x40
	private ClimbTowerMenu m_menu; // 0x48
	private ClimbTowerProperty m_towerProperty; // 0x50
	private ClimbTowerItemRewardProperty m_itemRewardProperty; // 0x58
	private Boolean _pnlTrapOrSquadShow; // 0x60
	private EventPool`1 m_eventPool; // 0x68
	private OnStateChangeListener m_stateEngineListener; // 0x70
	private Boolean m_isTutorial; // 0x78
	private List`1 m_predefinedCharList; // 0x80
	private Boolean <squadEditStateForceOpen>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_towerId; // 0x8
	private static DelegateBridge __Hotfix0_get_towerProperty; // 0x10
	private static DelegateBridge __Hotfix0_get_itemRewardProperty; // 0x18
	private static DelegateBridge __Hotfix0_get_squadEditStateForceOpen; // 0x20
	private static DelegateBridge __Hotfix0_set_squadEditStateForceOpen; // 0x28
	private static DelegateBridge __Hotfix0_get_isTutorialTower; // 0x30
	private static DelegateBridge __Hotfix0_get_predefinedCharList; // 0x38
	private static DelegateBridge __Hotfix0_OnCreate; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge __Hotfix0_RegisterMenuAdapter; // 0x50
	private static DelegateBridge __Hotfix0_ValidateBottomMenu; // 0x58
	private static DelegateBridge __Hotfix0_EnsureBottomMenu; // 0x60
	private static DelegateBridge __Hotfix0_IsEnterStateShowing; // 0x68
	private static DelegateBridge __Hotfix0_SaveTowerSelectModeToCache; // 0x70
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x78
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x80
	private static DelegateBridge __Hotfix0__OnMenuCreated; // 0x88
	private static DelegateBridge __Hotfix0__OnStateEnter; // 0x90
	private static DelegateBridge __Hotfix0__OnStateResume; // 0x98
	private static DelegateBridge __Hotfix0__OnStatePause; // 0xa0
	private static DelegateBridge __Hotfix0__OnBeforeTransition; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public String towerId { get; }
	public ClimbTowerProperty towerProperty { get; }
	public ClimbTowerItemRewardProperty itemRewardProperty { get; }
	public Boolean squadEditStateForceOpen { get; set; }
	public Boolean isTutorialTower { get; }
	public List`1 predefinedCharList { get; }

	// RVA: 0x2c608cc VA: 0x75952788cc
	public String get_towerId() { }
	// RVA: 0x2c60944 VA: 0x7595278944
	public ClimbTowerProperty get_towerProperty() { }
	// RVA: 0x2c609bc VA: 0x75952789bc
	public ClimbTowerItemRewardProperty get_itemRewardProperty() { }
	// RVA: 0x2c60a34 VA: 0x7595278a34
	public Boolean get_squadEditStateForceOpen() { }
	// RVA: 0x2c60aac VA: 0x7595278aac
	public Void set_squadEditStateForceOpen(Boolean value) { }
	// RVA: 0x2c60b3c VA: 0x7595278b3c
	public Boolean get_isTutorialTower() { }
	// RVA: 0x2c60bb4 VA: 0x7595278bb4
	public List`1 get_predefinedCharList() { }
	// RVA: 0x2c60c2c VA: 0x7595278c2c
	protected override Void OnCreate() { }
	// RVA: 0x2c61140 VA: 0x7595279140
	protected override Void OnDestroy() { }
	// RVA: 0x VA: 0x0
	public Void RegisterMenuAdapter(ClimbTowerMenuAdapter adapter) { }
	// RVA: 0x2c611dc VA: 0x75952791dc
	public Boolean ValidateBottomMenu() { }
	// RVA: 0x VA: 0x0
	public IEnumerator EnsureBottomMenu() { }
	// RVA: 0x2c61284 VA: 0x7595279284
	public Boolean IsEnterStateShowing() { }
	// RVA: 0x2c61470 VA: 0x7595279470
	public Void SaveTowerSelectModeToCache() { }
	// RVA: 0x2c616c4 VA: 0x75952796c4
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x2c61774 VA: 0x7595279774
	public Void OnPlayerDataChanged() { }
	// RVA: 0x2c61814 VA: 0x7595279814
	private Void _OnMenuCreated(GameObject obj) { }
	// RVA: 0x2c619a8 VA: 0x75952799a8
	private Void _OnStateEnter(Type stateType, Additions additions) { }
	// RVA: 0x2c61ad4 VA: 0x7595279ad4
	private Void _OnStateResume(Type stateType, Boolean backFromStack, Additions additions) { }
	// RVA: 0x2c61ba8 VA: 0x7595279ba8
	private Void _OnStatePause(Type stateType, Additions additions) { }
	// RVA: 0x2c61cf8 VA: 0x7595279cf8
	private Void _OnBeforeTransition(Type stateType, Type toType, Additions additions) { }
	// RVA: 0x2c61e6c VA: 0x7595279e6c
	public Void .ctor() { }
	// RVA: 0x2c61ff4 VA: 0x7595279ff4
	private static Void .cctor() { }
	// RVA: 0x2c62214 VA: 0x759527a214
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x2c6221c VA: 0x759527a21c
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```