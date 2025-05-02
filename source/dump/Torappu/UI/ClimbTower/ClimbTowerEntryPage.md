# ClimbTowerEntryPage

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `CanvasGroup _fadeFloatPanel`

- `Boolean m_isToClimbTowerPage`

- `Boolean m_isToTrainState`

- `UISwitchTween m_fadePanelTween`

- `String m_towerIdFromSavedInst`

- `Boolean m_backFromBattle`


## Properties

- `String towerIdOnOpen`


## Methods

- `String get_towerIdOnOpen()`

- `IEnumerator _RouteToClimbTowerList(Boolean)`

- `IEnumerator _RouteToClimbTowerPage()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `Void <>xLuaBaseProxy_OnStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryPage : StateEnginePage
{
	private const Single ANIM_TIME; // 0x0
	private CanvasGroup _fadeFloatPanel; // 0xe8
	private UICommonPageEffectHolder[] _effectHolders; // 0xf0
	private Boolean m_isToClimbTowerPage; // 0xf8
	private Boolean m_isToTrainState; // 0xf9
	private UISwitchTween m_fadePanelTween; // 0x100
	private String m_towerIdFromSavedInst; // 0x108
	private Boolean m_backFromBattle; // 0x110
	private static DelegateBridge __Hotfix0_get_towerIdOnOpen; // 0x0
	private static DelegateBridge __Hotfix0_CreateCommonTopMenu; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x18
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x20
	private static DelegateBridge __Hotfix0_OnStop; // 0x28
	private static DelegateBridge __Hotfix0__RouteToClimbTowerList; // 0x30
	private static DelegateBridge __Hotfix0__RouteToClimbTowerPage; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private String towerIdOnOpen { get; }

	// RVA: 0x2c6c04c VA: 0x759528404c
	private String get_towerIdOnOpen() { }
	// RVA: 0x2c6c0e0 VA: 0x75952840e0
	public static CommonTopMenu CreateCommonTopMenu(Transform container, Action onBackClick) { }
	// RVA: 0x2c6c258 VA: 0x7595284258
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2c6c4fc VA: 0x75952844fc
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2c6c5d0 VA: 0x75952845d0
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x2c6c6b8 VA: 0x75952846b8
	protected override Void OnStop() { }
	// RVA: 0x2c6c72c VA: 0x759528472c
	private IEnumerator _RouteToClimbTowerList(Boolean fastMode) { }
	// RVA: 0x2c6c81c VA: 0x759528481c
	private IEnumerator _RouteToClimbTowerPage() { }
	// RVA: 0x2c6c8f0 VA: 0x75952848f0
	public Void .ctor() { }
	// RVA: 0x2c6c960 VA: 0x7595284960
	private IEnumerator <>n__0() { }
	// RVA: 0x2c6c968 VA: 0x7595284968
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2c6c970 VA: 0x7595284970
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x2c6c978 VA: 0x7595284978
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x2c6c984 VA: 0x7595284984
	private Void <>xLuaBaseProxy_OnStop() { }
}
```