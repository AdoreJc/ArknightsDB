# StateEngine

**Namespace:** `Torappu.UI`


## Fields

- `TransitionManagerAsset _transitionManagerAsset`

- `State _defaultState`

- `DefaultStateOperation _defaultStateOperation`

- `Transform _prefabContainer`

- `StateEngineImpl m_engineImpl`

- `UIDynStateHub m_dynStateHubCache`

- `Boolean m_isInited`

- `IPageProvider m_pageProvider`

- `IStateEnginePlugin m_plugin`


## Properties

- `Boolean isInited`

- `State defaultState`

- `Int32 StackCount`

- `IStateEnginePlugin internalPlugin`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void _StartStateEngine()`

- `Transform GetPrefabContainer()`

- `IEnumerator _AddInitialStateCoroutine()`

- `State _LoadAndInstDynState(DynStateID, Transform)`

- `Boolean get_isInited()`

- `State get_defaultState()`

- `Int32 get_StackCount()`

- `TransitionManagerAsset GetTransitionManagerAsset()`

- `Void InjectPage(IPageProvider)`

- `IEnumerator ResetToDefault(Boolean)`

- `Void RegisterOnStateChange(OnStateChangeListener)`

- `Void UnregisterOnStateChange(OnStateChangeListener)`

- `Void ManualResumeFrontState()`

- `Boolean AddTop(Type, StateTransOptions)`

- `Boolean AddTop(Type)`

- `Boolean AddTop(StateTransOptions)`

- `Boolean AddTop()`

- `Boolean ReplaceTop(Type, StateTransOptions, StateReplaceTransMode)`

- `Boolean ReplaceTop(Type, StateReplaceTransMode)`

- `Boolean ReplaceTop(StateTransOptions, StateReplaceTransMode)`

- `Boolean ReplaceTop(StateReplaceTransMode)`

- `Boolean RemoveTop(StateTransOptions)`

- `Boolean RemoveTop()`

- `Boolean RemoveToState(Type, StateTransOptions)`

- `Boolean RemoveToState(Type)`

- `Boolean RemoveToState(StateTransOptions)`

- `Boolean RemoveToState()`

- `State GetFrontState()`

- `Boolean IsTransitting()`

- `StateEngineRuntime SaveToCache()`

- `IEnumerator LoadFromCache(StateEngineRuntime)`

- `UIPage GetPage()`

- `IStateEnginePlugin GetPlugin()`

- `Boolean CheckIfStateRegistered()`

- `Boolean CheckIfStateRegistered(Type)`

- `Boolean CheckIsExistInStack(Type)`

- `IStateEnginePlugin get_internalPlugin()`

- `IEnumerator _PreLoadStatesCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class StateEngine : MonoBehaviour, IStateEngine, IHotfixable
{
	public const String DEFAULT_OBJECT_NAME; // 0x0
	private TransitionManagerAsset _transitionManagerAsset; // 0x18
	private State _defaultState; // 0x20
	private DefaultStateOperation _defaultStateOperation; // 0x28
	private Transform _prefabContainer; // 0x30
	private State[] _registeredStates; // 0x38
	private GameObject[] _statesFromPrefab; // 0x40
	private List`1 _statesWithParentFromPrefab; // 0x48
	private List`1 _dynStatesWithParent; // 0x50
	private StateEngineImpl m_engineImpl; // 0x58
	private List`1 m_prefabInstStates; // 0x60
	private UIDynStateHub m_dynStateHubCache; // 0x68
	private Boolean m_isInited; // 0x70
	private IPageProvider m_pageProvider; // 0x78
	private IStateEnginePlugin m_plugin; // 0x80
	private List`1 m_stateChangeListeners; // 0x88
	private State[] m_selectableStates; // 0x90
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0__StartStateEngine; // 0x10
	private static DelegateBridge __Hotfix0_GetPrefabContainer; // 0x18
	private static DelegateBridge __Hotfix0__LoadPrefabStateInsts; // 0x20
	private static DelegateBridge __Hotfix0__AddInitialStateCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__LoadAndInstDynState; // 0x30
	private static DelegateBridge __Hotfix0_get_isInited; // 0x38
	private static DelegateBridge __Hotfix0_get_defaultState; // 0x40
	private static DelegateBridge __Hotfix0_get_StackCount; // 0x48
	private static DelegateBridge __Hotfix0_GetTransitionManagerAsset; // 0x50
	private static DelegateBridge __Hotfix0_AchieveSelectableStates; // 0x58
	private static DelegateBridge __Hotfix0_InjectPage; // 0x60
	private static DelegateBridge __Hotfix0_ResetToDefault; // 0x68
	private static DelegateBridge __Hotfix0_RegisterOnStateChange; // 0x70
	private static DelegateBridge __Hotfix0_UnregisterOnStateChange; // 0x78
	private static DelegateBridge __Hotfix0_ManualResumeFrontState; // 0x80
	private static DelegateBridge __Hotfix0_AddTop; // 0x88
	private static DelegateBridge __Hotfix1_AddTop; // 0x90
	private static DelegateBridge __Hotfix2_AddTop; // 0x98
	private static DelegateBridge __Hotfix3_AddTop; // 0xa0
	private static DelegateBridge __Hotfix0_ReplaceTop; // 0xa8
	private static DelegateBridge __Hotfix1_ReplaceTop; // 0xb0
	private static DelegateBridge __Hotfix2_ReplaceTop; // 0xb8
	private static DelegateBridge __Hotfix3_ReplaceTop; // 0xc0
	private static DelegateBridge __Hotfix0_RemoveTop; // 0xc8
	private static DelegateBridge __Hotfix1_RemoveTop; // 0xd0
	private static DelegateBridge __Hotfix0_RemoveToState; // 0xd8
	private static DelegateBridge __Hotfix1_RemoveToState; // 0xe0
	private static DelegateBridge __Hotfix2_RemoveToState; // 0xe8
	private static DelegateBridge __Hotfix3_RemoveToState; // 0xf0
	private static DelegateBridge __Hotfix0_GetFrontState; // 0xf8
	private static DelegateBridge __Hotfix0_IsTransitting; // 0x100
	private static DelegateBridge __Hotfix0_SaveToCache; // 0x108
	private static DelegateBridge __Hotfix0_LoadFromCache; // 0x110
	private static DelegateBridge __Hotfix0_GetPage; // 0x118
	private static DelegateBridge __Hotfix0_GetPlugin; // 0x120
	private static DelegateBridge __Hotfix0_CheckIfStateRegistered; // 0x128
	private static DelegateBridge __Hotfix1_CheckIfStateRegistered; // 0x130
	private static DelegateBridge __Hotfix0_CheckIsExistInStack; // 0x138
	private static DelegateBridge __Hotfix0_get_internalPlugin; // 0x140
	private static DelegateBridge __Hotfix0__PreLoadStatesCoroutine; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150

	public Boolean isInited { get; }
	public State defaultState { get; }
	public Int32 StackCount { get; }
	protected IStateEnginePlugin internalPlugin { get; }

	// RVA: 0x21627dc VA: 0x759477a7dc
	private Void Start() { }
	// RVA: 0x2162f30 VA: 0x759477af30
	private Void OnDestroy() { }
	// RVA: 0x2162944 VA: 0x759477a944
	private Void _StartStateEngine() { }
	// RVA: 0x21636a4 VA: 0x759477b6a4
	private Transform GetPrefabContainer() { }
	// RVA: 0x216375c VA: 0x759477b75c
	private List`1 _LoadPrefabStateInsts() { }
	// RVA: 0x21635f8 VA: 0x759477b5f8
	private IEnumerator _AddInitialStateCoroutine() { }
	// RVA: 0x2163c7c VA: 0x759477bc7c
	private State _LoadAndInstDynState(DynStateID state, Transform parent) { }
	// RVA: 0x21641b4 VA: 0x759477c1b4
	public Boolean get_isInited() { }
	// RVA: 0x216421c VA: 0x759477c21c
	public State get_defaultState() { }
	// RVA: 0x2164284 VA: 0x759477c284
	public Int32 get_StackCount() { }
	// RVA: 0x21642f4 VA: 0x759477c2f4
	public TransitionManagerAsset GetTransitionManagerAsset() { }
	// RVA: 0x2163030 VA: 0x759477b030
	public State[] AchieveSelectableStates() { }
	// RVA: 0x216435c VA: 0x759477c35c
	public Void InjectPage(IPageProvider parentPage) { }
	// RVA: 0x21643e0 VA: 0x759477c3e0
	public IEnumerator ResetToDefault(Boolean force) { }
	// RVA: 0x21644d0 VA: 0x759477c4d0
	public Void RegisterOnStateChange(OnStateChangeListener listener) { }
	// RVA: 0x216460c VA: 0x759477c60c
	public Void UnregisterOnStateChange(OnStateChangeListener listener) { }
	// RVA: 0x21646ac VA: 0x759477c6ac
	public Void ManualResumeFrontState() { }
	// RVA: 0x2164848 VA: 0x759477c848
	public Boolean AddTop(Type state, StateTransOptions config) { }
	// RVA: 0x21648dc VA: 0x759477c8dc
	public Boolean AddTop(Type state) { }
	// RVA: 0x VA: 0x0
	public Boolean AddTop(StateTransOptions config) { }
	// RVA: 0x VA: 0x0
	public Boolean AddTop() { }
	// RVA: 0x2164964 VA: 0x759477c964
	public Boolean ReplaceTop(Type state, StateTransOptions config, StateReplaceTransMode replaceTransMode) { }
	// RVA: 0x2164a10 VA: 0x759477ca10
	public Boolean ReplaceTop(Type state, StateReplaceTransMode replaceTransMode) { }
	// RVA: 0x VA: 0x0
	public Boolean ReplaceTop(StateTransOptions config, StateReplaceTransMode replaceTransMode) { }
	// RVA: 0x VA: 0x0
	public Boolean ReplaceTop(StateReplaceTransMode replaceTransMode) { }
	// RVA: 0x2164aa4 VA: 0x759477caa4
	public Boolean RemoveTop(StateTransOptions config) { }
	// RVA: 0x2164b2c VA: 0x759477cb2c
	public Boolean RemoveTop() { }
	// RVA: 0x2164b9c VA: 0x759477cb9c
	public Boolean RemoveToState(Type state, StateTransOptions config) { }
	// RVA: 0x2164c30 VA: 0x759477cc30
	public Boolean RemoveToState(Type state) { }
	// RVA: 0x VA: 0x0
	public Boolean RemoveToState(StateTransOptions config) { }
	// RVA: 0x VA: 0x0
	public Boolean RemoveToState() { }
	// RVA: 0x21647d8 VA: 0x759477c7d8
	public State GetFrontState() { }
	// RVA: 0x2164cb8 VA: 0x759477ccb8
	public Boolean IsTransitting() { }
	// RVA: 0x2164d28 VA: 0x759477cd28
	public StateEngineRuntime SaveToCache() { }
	// RVA: 0x2164d98 VA: 0x759477cd98
	public IEnumerator LoadFromCache(StateEngineRuntime runtime) { }
	// RVA: 0x21640d0 VA: 0x759477c0d0
	public UIPage GetPage() { }
	// RVA: 0x2164e20 VA: 0x759477ce20
	public IStateEnginePlugin GetPlugin() { }
	// RVA: 0x VA: 0x0
	public Boolean CheckIfStateRegistered() { }
	// RVA: 0x2164e88 VA: 0x759477ce88
	public Boolean CheckIfStateRegistered(Type stateType) { }
	// RVA: 0x2164f10 VA: 0x759477cf10
	public Boolean CheckIsExistInStack(Type stateType) { }
	// RVA: 0x2163534 VA: 0x759477b534
	protected IStateEnginePlugin get_internalPlugin() { }
	// RVA: 0x2164fc8 VA: 0x759477cfc8
	private IEnumerator _PreLoadStatesCoroutine() { }
	// RVA: 0x216509c VA: 0x759477d09c
	public Void .ctor() { }
}
```