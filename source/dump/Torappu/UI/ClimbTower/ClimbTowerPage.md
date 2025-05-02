# ClimbTowerPage

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `GameObject _effectPanel`

- `Boolean m_routeToEnding`


## Methods

- `String GetTowerId()`

- `Boolean IsFromBattle()`

- `Boolean IsEntryStateInFront()`

- `IEnumerator _RouteToProperState()`

- `IEnumerator _JumpToTowerEntry()`

- `IEnumerator _JumpToInitGodProcess(Boolean)`

- `IEnumerator _JumpToInitBuffProcess()`

- `IEnumerator _JumpToSquadCreateProcess()`

- `IEnumerator _JumpToLayerProcess()`

- `IEnumerator _JumpToEndingProcess()`

- `IEnumerator <>n__0()`

- `IEnumerator <>n__1(Boolean)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerPage : StateEnginePage
{
	private GameObject _effectPanel; // 0xe8
	private Boolean m_routeToEnding; // 0xf0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x8
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x10
	private static DelegateBridge __Hotfix0_GetTowerId; // 0x18
	private static DelegateBridge __Hotfix0_IsFromBattle; // 0x20
	private static DelegateBridge __Hotfix0_IsEntryStateInFront; // 0x28
	private static DelegateBridge __Hotfix0__RouteToProperState; // 0x30
	private static DelegateBridge __Hotfix0__JumpToTowerEntry; // 0x38
	private static DelegateBridge __Hotfix0__JumpToInitGodProcess; // 0x40
	private static DelegateBridge __Hotfix0__JumpToInitBuffProcess; // 0x48
	private static DelegateBridge __Hotfix0__JumpToSquadCreateProcess; // 0x50
	private static DelegateBridge __Hotfix0__JumpToLayerProcess; // 0x58
	private static DelegateBridge __Hotfix0__JumpToEndingProcess; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2c705b4 VA: 0x75952885b4
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2c7064c VA: 0x759528864c
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2c70720 VA: 0x7595288720
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x2c61090 VA: 0x7595279090
	public String GetTowerId() { }
	// RVA: 0x2c70810 VA: 0x7595288810
	public Boolean IsFromBattle() { }
	// RVA: 0x2c613a4 VA: 0x75952793a4
	public Boolean IsEntryStateInFront() { }
	// RVA: 0x2c708a4 VA: 0x75952888a4
	private IEnumerator _RouteToProperState() { }
	// RVA: 0x2c70978 VA: 0x7595288978
	private IEnumerator _JumpToTowerEntry() { }
	// RVA: 0x2c70a24 VA: 0x7595288a24
	private IEnumerator _JumpToInitGodProcess(Boolean isHard) { }
	// RVA: 0x2c70aec VA: 0x7595288aec
	private IEnumerator _JumpToInitBuffProcess() { }
	// RVA: 0x2c70b98 VA: 0x7595288b98
	private IEnumerator _JumpToSquadCreateProcess() { }
	// RVA: 0x2c70c44 VA: 0x7595288c44
	private IEnumerator _JumpToLayerProcess() { }
	// RVA: 0x2c70cf0 VA: 0x7595288cf0
	private IEnumerator _JumpToEndingProcess() { }
	// RVA: 0x2c70d9c VA: 0x7595288d9c
	public Void .ctor() { }
	// RVA: 0x2c70e0c VA: 0x7595288e0c
	private IEnumerator <>n__0() { }
	// RVA: 0x2c70e14 VA: 0x7595288e14
	private IEnumerator <>n__1(Boolean isFromStack) { }
	// RVA: 0x2c70e20 VA: 0x7595288e20
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2c70e28 VA: 0x7595288e28
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x2c70e30 VA: 0x7595288e30
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
}
```