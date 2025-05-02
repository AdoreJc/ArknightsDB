# ClimbTowerMenu

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerTacticalBuffMenuObject _menuTacticalBuff`

- `CanvasGroup _canvasBuff`

- `ClimbTowerTrapMenuObject _menuTrap`

- `ClimbTowerSquadMenuObject _menuSquad`

- `ClimbTowerProfessionMenuObject _menuProfession`

- `GameObject _pnlPlaceHolder`

- `ClimbTowerButtonHolderMenuObject _menuButtonHolder`

- `CanvasGroup _alphaHandler`

- `RectTransform _posHandler`

- `String m_towerId`

- `ClimbTowerMenuViewModel m_viewModel`

- `ClimbTowerControllerBridge m_bindControllerBridge`

- `StateEngine m_bindStateEngine`

- `ClimbTowerMenuAdapter m_topAdapter`

- `Type m_topStateType`

- `ShowSwitchTween m_switchTween`

- `Boolean m_lastShowStatus`

- `StateTransitionParam m_currTransParam`

- `UIBlocker m_menuUIBlocker`


## Properties

- `Boolean canClick`

- `ClimbTowerControllerBridge bindControllerBridge`

- `StateEngine bindStateEngine`

- `ClimbTowerTrapMenuObject menuTrap`

- `ClimbTowerSquadMenuObject menuSquad`


## Methods

- `Boolean get_canClick()`

- `ClimbTowerControllerBridge get_bindControllerBridge()`

- `StateEngine get_bindStateEngine()`

- `ClimbTowerTrapMenuObject get_menuTrap()`

- `ClimbTowerSquadMenuObject get_menuSquad()`

- `Void RegisterMenuAdapter(Type, ClimbTowerMenuAdapter)`

- `ClimbTowerMenuAdapter _GetStateMenuAdapter(Type)`

- `Void _Render()`

- `Void _OnPlayerDataChanged(Object)`

- `Void _RefreshView(Boolean)`

- `Void _OnBeforeStateTransition(Object)`

- `Void _OnStateChanged(Object, Boolean)`

- `Void _SetShowStatus(Boolean, TweenType, Boolean)`

- `Void Init(ClimbTowerControllerBridge)`

- `IEnumerator EnsureBottomMenu()`

- `Void ClearTacticalBuffWindow()`

- `Void OnTacticalBuffWindowShowStatusUpdated(Boolean)`

- `Void OnDestroy()`

- `Void <Init>b__42_0(Object)`

- `Void <Init>b__42_1(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerMenu : MonoBehaviour, IHotfixable
{
	private ClimbTowerTacticalBuffMenuObject _menuTacticalBuff; // 0x18
	private CanvasGroup _canvasBuff; // 0x20
	private ClimbTowerTrapMenuObject _menuTrap; // 0x28
	private ClimbTowerSquadMenuObject _menuSquad; // 0x30
	private ClimbTowerProfessionMenuObject _menuProfession; // 0x38
	private GameObject _pnlPlaceHolder; // 0x40
	private ClimbTowerButtonHolderMenuObject _menuButtonHolder; // 0x48
	private List`1 _menuObjects; // 0x50
	private CanvasGroup _alphaHandler; // 0x58
	private RectTransform _posHandler; // 0x60
	private String m_towerId; // 0x68
	private ClimbTowerMenuViewModel m_viewModel; // 0x70
	private ClimbTowerControllerBridge m_bindControllerBridge; // 0x78
	private StateEngine m_bindStateEngine; // 0x80
	private ClimbTowerMenuAdapter m_topAdapter; // 0x88
	private Type m_topStateType; // 0x90
	private ShowSwitchTween m_switchTween; // 0x98
	private Boolean m_lastShowStatus; // 0xa0
	private StateTransitionParam m_currTransParam; // 0xa8
	private Dictionary`2 m_adapters; // 0xb0
	private UIBlocker m_menuUIBlocker; // 0xb8
	private static DelegateBridge __Hotfix0_get_canClick; // 0x0
	private static DelegateBridge __Hotfix0_get_bindControllerBridge; // 0x8
	private static DelegateBridge __Hotfix0_get_bindStateEngine; // 0x10
	private static DelegateBridge __Hotfix0_get_menuTrap; // 0x18
	private static DelegateBridge __Hotfix0_get_menuSquad; // 0x20
	private static DelegateBridge __Hotfix0_RegisterMenuAdapter; // 0x28
	private static DelegateBridge __Hotfix0__GetStateMenuAdapter; // 0x30
	private static DelegateBridge __Hotfix0__Render; // 0x38
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x40
	private static DelegateBridge __Hotfix0__RefreshView; // 0x48
	private static DelegateBridge __Hotfix0__OnBeforeStateTransition; // 0x50
	private static DelegateBridge __Hotfix0__OnStateChanged; // 0x58
	private static DelegateBridge __Hotfix0__SetShowStatus; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x68
	private static DelegateBridge __Hotfix0_EnsureBottomMenu; // 0x70
	private static DelegateBridge __Hotfix0_ClearTacticalBuffWindow; // 0x78
	private static DelegateBridge __Hotfix0_OnTacticalBuffWindowShowStatusUpdated; // 0x80
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public Boolean canClick { get; }
	public ClimbTowerControllerBridge bindControllerBridge { get; }
	public StateEngine bindStateEngine { get; }
	public ClimbTowerTrapMenuObject menuTrap { get; }
	public ClimbTowerSquadMenuObject menuSquad { get; }

	// RVA: 0x2c7f42c VA: 0x759529742c
	public Boolean get_canClick() { }
	// RVA: 0x2c81854 VA: 0x7595299854
	public ClimbTowerControllerBridge get_bindControllerBridge() { }
	// RVA: 0x2c818bc VA: 0x75952998bc
	public StateEngine get_bindStateEngine() { }
	// RVA: 0x2c81924 VA: 0x7595299924
	public ClimbTowerTrapMenuObject get_menuTrap() { }
	// RVA: 0x2c8198c VA: 0x759529998c
	public ClimbTowerSquadMenuObject get_menuSquad() { }
	// RVA: 0x2c819f4 VA: 0x75952999f4
	public Void RegisterMenuAdapter(Type stateType, ClimbTowerMenuAdapter adapter) { }
	// RVA: 0x2c81aa0 VA: 0x7595299aa0
	private ClimbTowerMenuAdapter _GetStateMenuAdapter(Type stateType) { }
	// RVA: 0x2c81b3c VA: 0x7595299b3c
	private Void _Render() { }
	// RVA: 0x2c81cc4 VA: 0x7595299cc4
	private Void _OnPlayerDataChanged(Object arg) { }
	// RVA: 0x2c81d88 VA: 0x7595299d88
	private Void _RefreshView(Boolean fastMode) { }
	// RVA: 0x2c822a8 VA: 0x759529a2a8
	private Void _OnBeforeStateTransition(Object arg) { }
	// RVA: 0x2c82404 VA: 0x759529a404
	private Void _OnStateChanged(Object arg, Boolean statePaused) { }
	// RVA: 0x2c82128 VA: 0x759529a128
	private Void _SetShowStatus(Boolean isShow, TweenType showType, Boolean fastMode) { }
	// RVA: 0x2c826a4 VA: 0x759529a6a4
	public Void Init(ClimbTowerControllerBridge bridge) { }
	// RVA: 0x VA: 0x0
	public IEnumerator EnsureBottomMenu() { }
	// RVA: 0x2c7f4c8 VA: 0x75952974c8
	public Void ClearTacticalBuffWindow() { }
	// RVA: 0x2c82c04 VA: 0x759529ac04
	public Void OnTacticalBuffWindowShowStatusUpdated(Boolean isShow) { }
	// RVA: 0x2c82cb8 VA: 0x759529acb8
	private Void OnDestroy() { }
	// RVA: 0x2c82d4c VA: 0x759529ad4c
	public Void .ctor() { }
	// RVA: 0x2c82ed0 VA: 0x759529aed0
	private Void <Init>b__42_0(Object arg) { }
	// RVA: 0x2c82ed8 VA: 0x759529aed8
	private Void <Init>b__42_1(Object arg) { }
}
```