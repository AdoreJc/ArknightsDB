# CrisisV2MapPage

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String m_initMapId`

- `ReentrantFloatRef m_globalBlackMask`


## Properties

- `String initMapId`


## Methods

- `String get_initMapId()`

- `IEnumerator _RouteToProperState()`

- `IEnumerator _JumpToEntryState()`

- `IEnumerator _JumpToMapState()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapPage : StateEnginePage
{
	private String m_initMapId; // 0xe8
	private ReentrantFloatRef m_globalBlackMask; // 0xf0
	private const String KEY_PARAM_BUNDLE; // 0x0
	private static DelegateBridge __Hotfix0_OnStart; // 0x0
	private static DelegateBridge __Hotfix0_LoadParamFromBundle; // 0x8
	private static DelegateBridge __Hotfix0_SceneParamToCrisisV2Map; // 0x10
	private static DelegateBridge __Hotfix0_CreateRecoverDataBundleForBattle; // 0x18
	private static DelegateBridge __Hotfix0_get_initMapId; // 0x20
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x28
	private static DelegateBridge __Hotfix0__RouteToProperState; // 0x30
	private static DelegateBridge __Hotfix0__JumpToEntryState; // 0x38
	private static DelegateBridge __Hotfix0__JumpToMapState; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String initMapId { get; }

	// RVA: 0x2bc73c8 VA: 0x75951df3c8
	protected override Void OnStart() { }
	// RVA: 0x2bc74cc VA: 0x75951df4cc
	public static Param LoadParamFromBundle(DataBundle bundle) { }
	// RVA: 0x2bc76e0 VA: 0x75951df6e0
	public static UIPageControllerParam SceneParamToCrisisV2Map(Param param) { }
	// RVA: 0x2bc7a78 VA: 0x75951dfa78
	public static DataBundle CreateRecoverDataBundleForBattle(String mapId) { }
	// RVA: 0x2bc7bec VA: 0x75951dfbec
	public String get_initMapId() { }
	// RVA: 0x2bc7c54 VA: 0x75951dfc54
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2bc7d28 VA: 0x75951dfd28
	private IEnumerator _RouteToProperState() { }
	// RVA: 0x2bc7dfc VA: 0x75951dfdfc
	private IEnumerator _JumpToEntryState() { }
	// RVA: 0x2bc7ed0 VA: 0x75951dfed0
	private IEnumerator _JumpToMapState() { }
	// RVA: 0x2bc7fa4 VA: 0x75951dffa4
	public Void .ctor() { }
	// RVA: 0x2bc8014 VA: 0x75951e0014
	private IEnumerator <>n__0() { }
	// RVA: 0x2bc801c VA: 0x75951e001c
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x2bc8024 VA: 0x75951e0024
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```