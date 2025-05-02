# GlobalInitializerAndUpdater

**Namespace:** `Torappu`


## Fields

- `Boolean m_isInited`


## Methods

- `Boolean IsInited()`

- `Void Update()`

- `Void OnApplicationQuit()`

- `Void _DoInitInAwake()`

- `IEnumerator DoReloadAllMainAssets(Options)`

- `IEnumerator WaitForSceneResReady(String)`

- `Void _InitAPPDefaultCulture()`

- `Coroutine _StartCorotuine(IEnumerator)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GlobalInitializerAndUpdater : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private static readonly String[] ASYNC_LOADING_SCENES; // 0x0
	private Boolean m_isInited; // 0x18
	private List`1 m_actionsWhenInited; // 0x20
	private static DelegateBridge __Hotfix0_IsInited; // 0x8
	private static DelegateBridge __Hotfix0_WaitForInitCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_InvokeWhenInitReadyBeforeWaitingCoroutines; // 0x18
	private static DelegateBridge __Hotfix0_Awake; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge __Hotfix0_OnApplicationQuit; // 0x30
	private static DelegateBridge __Hotfix0__DoInitInAwake; // 0x38
	private static DelegateBridge __Hotfix0__SetInstanceToBaseAssemblies; // 0x40
	private static DelegateBridge __Hotfix0__RegisterGlobalListeners; // 0x48
	private static DelegateBridge __Hotfix0__SetGraphicTierByPlatform; // 0x50
	private static DelegateBridge __Hotfix0__LoadInitialAssetsImpl; // 0x58
	private static DelegateBridge __Hotfix0_ReloadInitialAssets; // 0x60
	private static DelegateBridge __Hotfix0_DoReloadAllMainAssets; // 0x68
	private static DelegateBridge __Hotfix0_WaitForSceneResReady; // 0x70
	private static DelegateBridge __Hotfix0_ForceUnloadAllAssetsEvenUsed; // 0x78
	private static DelegateBridge __Hotfix0__InitAPPDefaultCulture; // 0x80
	private static DelegateBridge __Hotfix0__StartCorotuine; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x2f341ac VA: 0x759554c1ac
	public Boolean IsInited() { }
	// RVA: 0x2f34224 VA: 0x759554c224
	public static IEnumerator WaitForInitCoroutine(Action nextStep) { }
	// RVA: 0x2f34308 VA: 0x759554c308
	public static Void InvokeWhenInitReadyBeforeWaitingCoroutines(Action action) { }
	// RVA: 0x2f34490 VA: 0x759554c490
	protected override Void Awake() { }
	// RVA: 0x2f354c8 VA: 0x759554d4c8
	private Void Update() { }
	// RVA: 0x2f35584 VA: 0x759554d584
	private Void OnApplicationQuit() { }
	// RVA: 0x2f34fd8 VA: 0x759554cfd8
	private Void _DoInitInAwake() { }
	// RVA: 0x2f34de4 VA: 0x759554cde4
	private static Void _SetInstanceToBaseAssemblies(GlobalInitializerAndUpdater inst) { }
	// RVA: 0x2f35670 VA: 0x759554d670
	private static Void _RegisterGlobalListeners() { }
	// RVA: 0x2f356fc VA: 0x759554d6fc
	private static Void _SetGraphicTierByPlatform() { }
	// RVA: 0x2f35794 VA: 0x759554d794
	private static Void _LoadInitialAssetsImpl(Boolean isInitLoad) { }
	// RVA: 0x2f35bd8 VA: 0x759554dbd8
	public static Void ReloadInitialAssets() { }
	// RVA: 0x2f32284 VA: 0x759554a284
	public IEnumerator DoReloadAllMainAssets(Options options) { }
	// RVA: 0x2f3370c VA: 0x759554b70c
	public IEnumerator WaitForSceneResReady(String targetScene) { }
	// RVA: 0x2f35ca8 VA: 0x759554dca8
	public static IEnumerator ForceUnloadAllAssetsEvenUsed() { }
	// RVA: 0x2f34794 VA: 0x759554c794
	private Void _InitAPPDefaultCulture() { }
	// RVA: 0x2f35d74 VA: 0x759554dd74
	private Coroutine _StartCorotuine(IEnumerator coroutine) { }
	// RVA: 0x2f35e08 VA: 0x759554de08
	public Void .ctor() { }
	// RVA: 0x2f35efc VA: 0x759554defc
	private static Void .cctor() { }
}
```