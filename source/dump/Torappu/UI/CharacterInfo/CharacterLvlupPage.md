# CharacterLvlupPage

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _panelEffect`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `IEnumerator _RouteToProperState()`

- `Void OnExitFromLevelMaxState()`

- `IEnumerator <>n__0()`

- `IEnumerator <>n__1(Boolean)`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupPage : StateEnginePage
{
	private GameObject _panelEffect; // 0xe8
	private Boolean m_isInited; // 0xf0
	private static DelegateBridge __Hotfix0_OnStart; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x10
	private static DelegateBridge __Hotfix0__RouteToProperState; // 0x18
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x20
	private static DelegateBridge __Hotfix0_OnExitFromLevelMaxState; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2d3d4a4 VA: 0x75953554a4
	protected override Void OnStart() { }
	// RVA: 0x2d3d518 VA: 0x7595355518
	private Void _InitIfNot() { }
	// RVA: 0x2d3d628 VA: 0x7595355628
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2d3d6fc VA: 0x75953556fc
	private IEnumerator _RouteToProperState() { }
	// RVA: 0x2d3d7d0 VA: 0x75953557d0
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x2d3d8c0 VA: 0x75953558c0
	public Void OnExitFromLevelMaxState() { }
	// RVA: 0x2d3dab4 VA: 0x7595355ab4
	public Void .ctor() { }
	// RVA: 0x2d3db24 VA: 0x7595355b24
	private IEnumerator <>n__0() { }
	// RVA: 0x2d3db2c VA: 0x7595355b2c
	private IEnumerator <>n__1(Boolean isIntoStack) { }
	// RVA: 0x2d3db38 VA: 0x7595355b38
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x2d3db40 VA: 0x7595355b40
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x2d3db48 VA: 0x7595355b48
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```