# GameFlowController

**Namespace:** `Torappu`


## Fields

- `Boolean m_isTransiting`

- `SceneBundle m_sceneBundle`

- `SceneBundle m_addingSceneBundle`

- `IAddtiveBattleScene m_addtiveBattleScene`

- `Boolean m_isAdditiveUnloading`

- `LoadSceneInfoManager m_loadSceneInfoMgr`

- `Boolean m_isShowBlackLoading`

- `Boolean m_isShowSceneLoading`


## Methods

- `AsyncOperation LoadAdditiveSceneAsync(String, LoadSceneMode)`

- `Boolean _StartScene(String, Options)`

- `Boolean _StartScene(String)`

- `Void _StartSceneAnyway(String, Options)`

- `IEnumerator _TransitSceneCoroutine(String, Options)`

- `IEnumerator _LoadEmptySceneToClear(Options)`

- `IEnumerator _DoCommonClearLogic(Options)`

- `Void _OnSceneLoaded(String)`

- `IEnumerator _ShowBlackLoading()`

- `IEnumerator _HideBlackLoading()`

- `IEnumerator _ShowSceneLoading(String)`

- `IEnumerator _HideSceneLoading()`

- `IEnumerator _HideBlackAndSceneLoading()`

- `IEnumerator _PrepareLoadingsBeforeTransition()`

- `IEnumerator _LiteLoadBattleFinish(String, Options)`

- `Boolean _AddScene(String)`

- `IEnumerator _AddSceneCoroutine(String)`

- `Boolean _AddAdditiveBattleScene(IAddtiveBattleScene)`

- `IEnumerator _AddAdditiveBattleSceneCoroutine()`

- `Boolean _RemoveAdditiveBattleScene()`

- `IEnumerator _RemoveAdditiveBattleSceneCoroutine(Boolean)`

- `Void _MayOverrideNextScene(String, String, ref)`

- `Boolean _TryHookStoryScene(String, String, ref)`

- `Boolean <_AddAdditiveBattleSceneCoroutine>b__67_0()`

- `Boolean <_RemoveAdditiveBattleSceneCoroutine>b__69_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GameFlowController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private const Single ASYNC_SCENE_LOAD_MAX_PROGRESS; // 0x0
	private const Single LOADING_MODE_MIN_WAITING_TIME; // 0x0
	private ListSet`1 m_addingScenes; // 0x18
	private Boolean m_isTransiting; // 0x20
	private SceneBundle m_sceneBundle; // 0x28
	private SceneBundle m_addingSceneBundle; // 0x40
	private IAddtiveBattleScene m_addtiveBattleScene; // 0x58
	private Boolean m_isAdditiveUnloading; // 0x60
	private LoadSceneInfoManager m_loadSceneInfoMgr; // 0x68
	private static Action`2 beforeSceneLoadingStart; // 0x0
	private static Action`2 onSceneLoaded; // 0x8
	private static Action`1 onSceneUnloaded; // 0x10
	private Boolean m_isShowBlackLoading; // 0x70
	private Boolean m_isShowSceneLoading; // 0x71
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_add_beforeSceneTransition; // 0x20
	private static DelegateBridge __Hotfix0_remove_beforeSceneTransition; // 0x28
	private static DelegateBridge __Hotfix0_add_beforeSceneLoadingStart; // 0x30
	private static DelegateBridge __Hotfix0_remove_beforeSceneLoadingStart; // 0x38
	private static DelegateBridge __Hotfix0_add_onSceneLoaded; // 0x40
	private static DelegateBridge __Hotfix0_remove_onSceneLoaded; // 0x48
	private static DelegateBridge __Hotfix0_add_onSceneUnloaded; // 0x50
	private static DelegateBridge __Hotfix0_remove_onSceneUnloaded; // 0x58
	private static DelegateBridge __Hotfix0_GetRecentLoadSceneMode; // 0x60
	private static DelegateBridge __Hotfix0_IsMainScene; // 0x68
	private static DelegateBridge __Hotfix0_get_isTransiting; // 0x70
	private static DelegateBridge __Hotfix0_StartScene; // 0x78
	private static DelegateBridge __Hotfix1_StartScene; // 0x80
	private static DelegateBridge __Hotfix0_AddScene; // 0x88
	private static DelegateBridge __Hotfix0_AddAdditiveBattleScene; // 0x90
	private static DelegateBridge __Hotfix0_RemoveAdditiveBattleScene; // 0x98
	private static DelegateBridge __Hotfix0_LoadAdditiveSceneAsync; // 0xa0
	private static DelegateBridge __Hotfix0_StartSceneAnyway; // 0xa8
	private static DelegateBridge __Hotfix1_StartSceneAnyway; // 0xb0
	private static DelegateBridge __Hotfix0_get_currentSceneBundle; // 0xb8
	private static DelegateBridge __Hotfix0_get_currentScene; // 0xc0
	private static DelegateBridge __Hotfix0_get_currentAddingSceneBundle; // 0xc8
	private static DelegateBridge __Hotfix0_get_currAddtiveBattleScene; // 0xd0
	private static DelegateBridge __Hotfix0_StartWaitForSceneLoaded; // 0xd8
	private static DelegateBridge __Hotfix0__StartScene; // 0xe0
	private static DelegateBridge __Hotfix1__StartScene; // 0xe8
	private static DelegateBridge __Hotfix0__StartSceneAnyway; // 0xf0
	private static DelegateBridge __Hotfix0__TransitSceneCoroutine; // 0xf8
	private static DelegateBridge __Hotfix0__LoadEmptySceneToClear; // 0x100
	private static DelegateBridge __Hotfix0__DoCommonClearLogic; // 0x108
	private static DelegateBridge __Hotfix0__OnSceneLoaded; // 0x110
	private static DelegateBridge __Hotfix0__ShowBlackLoading; // 0x118
	private static DelegateBridge __Hotfix0__HideBlackLoading; // 0x120
	private static DelegateBridge __Hotfix0__ShowSceneLoading; // 0x128
	private static DelegateBridge __Hotfix0__HideSceneLoading; // 0x130
	private static DelegateBridge __Hotfix0__HideBlackAndSceneLoading; // 0x138
	private static DelegateBridge __Hotfix0__PrepareLoadingsBeforeTransition; // 0x140
	private static DelegateBridge __Hotfix0__LiteLoadBattleFinish; // 0x148
	private static DelegateBridge __Hotfix0__AddScene; // 0x150
	private static DelegateBridge __Hotfix0__AddSceneCoroutine; // 0x158
	private static DelegateBridge __Hotfix0__AddAdditiveBattleScene; // 0x160
	private static DelegateBridge __Hotfix0__AddAdditiveBattleSceneCoroutine; // 0x168
	private static DelegateBridge __Hotfix0__RemoveAdditiveBattleScene; // 0x170
	private static DelegateBridge __Hotfix0__RemoveAdditiveBattleSceneCoroutine; // 0x178
	private static DelegateBridge __Hotfix0__DeletePersistentRes; // 0x180
	private static DelegateBridge __Hotfix0__DeleleAllPlayerPrefs; // 0x188
	private static DelegateBridge __Hotfix0__MayOverrideNextScene; // 0x190
	private static DelegateBridge __Hotfix0__TryHookStoryScene; // 0x198
	private static DelegateBridge __Hotfix0__LoadTargetSceneAsync; // 0x1a0
	private static DelegateBridge __Hotfix0__LoadTargetSceneAsyncFastMode; // 0x1a8
	private static DelegateBridge __Hotfix0__BeforeSceneLoadingStart; // 0x1b0
	private static DelegateBridge __Hotfix0_CheckIsInBattleScene; // 0x1b8
	private static DelegateBridge __Hotfix0_CheckIsInStoryScene; // 0x1c0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1c8

	public static Boolean isTransiting { get; }
	public static SceneBundle currentSceneBundle { get; }
	public static String currentScene { get; }
	public static SceneBundle currentAddingSceneBundle { get; }
	public static IAddtiveBattleScene currAddtiveBattleScene { get; }

	// RVA: 0x2d16af0 VA: 0x759532eaf0
	protected override Void OnInit() { }
	// RVA: 0x2d16c80 VA: 0x759532ec80
	public static Void add_beforeSceneTransition(Action`2 value) { }
	// RVA: 0x2d16d10 VA: 0x759532ed10
	public static Void remove_beforeSceneTransition(Action`2 value) { }
	// RVA: 0x2d16da0 VA: 0x759532eda0
	public static Void add_beforeSceneLoadingStart(Action`2 value) { }
	// RVA: 0x2d16e90 VA: 0x759532ee90
	public static Void remove_beforeSceneLoadingStart(Action`2 value) { }
	// RVA: 0x2d16f80 VA: 0x759532ef80
	public static Void add_onSceneLoaded(Action`2 value) { }
	// RVA: 0x2d17074 VA: 0x759532f074
	public static Void remove_onSceneLoaded(Action`2 value) { }
	// RVA: 0x2d17168 VA: 0x759532f168
	public static Void add_onSceneUnloaded(Action`1 value) { }
	// RVA: 0x2d1725c VA: 0x759532f25c
	public static Void remove_onSceneUnloaded(Action`1 value) { }
	// RVA: 0x2d17350 VA: 0x759532f350
	public static RecentLoadSceneMode GetRecentLoadSceneMode(Scene scene) { }
	// RVA: 0x2d17478 VA: 0x759532f478
	public static Boolean IsMainScene(Scene scene) { }
	// RVA: 0x2d174ec VA: 0x759532f4ec
	public static Boolean get_isTransiting() { }
	// RVA: 0x2d0b3a0 VA: 0x75953233a0
	public static Boolean StartScene(String sceneName, Options options) { }
	// RVA: 0x2d17760 VA: 0x759532f760
	public static Boolean StartScene(String sceneName) { }
	// RVA: 0x2d17890 VA: 0x759532f890
	public static Boolean AddScene(String sceneName) { }
	// RVA: 0x2d17a1c VA: 0x759532fa1c
	public static Boolean AddAdditiveBattleScene(IAddtiveBattleScene battleScene) { }
	// RVA: 0x2d17c34 VA: 0x759532fc34
	public static Boolean RemoveAdditiveBattleScene() { }
	// RVA: 0x2d17d48 VA: 0x759532fd48
	protected AsyncOperation LoadAdditiveSceneAsync(String sceneName, LoadSceneMode mode) { }
	// RVA: 0x2d17ddc VA: 0x759532fddc
	public static Void StartSceneAnyway(String sceneName) { }
	// RVA: 0x2d17f70 VA: 0x759532ff70
	public static Void StartSceneAnyway(String sceneName, Options options) { }
	// RVA: 0x2d0b13c VA: 0x759532313c
	public static SceneBundle get_currentSceneBundle() { }
	// RVA: 0x2d0acb8 VA: 0x7595322cb8
	public static String get_currentScene() { }
	// RVA: 0x2d18048 VA: 0x7595330048
	public static SceneBundle get_currentAddingSceneBundle() { }
	// RVA: 0x2d180ec VA: 0x75953300ec
	public static IAddtiveBattleScene get_currAddtiveBattleScene() { }
	// RVA: 0x2d18198 VA: 0x7595330198
	public static WaitForSceneLoaded StartWaitForSceneLoaded(String sceneName) { }
	// RVA: 0x2d175c8 VA: 0x759532f5c8
	private Boolean _StartScene(String sceneName, Options options) { }
	// RVA: 0x2d177ec VA: 0x759532f7ec
	private Boolean _StartScene(String sceneName) { }
	// RVA: 0x2d17e98 VA: 0x759532fe98
	private Void _StartSceneAnyway(String sceneName, Options options) { }
	// RVA: 0x2d183ac VA: 0x75953303ac
	private IEnumerator _TransitSceneCoroutine(String sceneName, Options options) { }
	// RVA: 0x2d184bc VA: 0x75953304bc
	private IEnumerator _LoadEmptySceneToClear(Options options) { }
	// RVA: 0x2d185b4 VA: 0x75953305b4
	private IEnumerator _DoCommonClearLogic(Options options) { }
	// RVA: 0x2d18694 VA: 0x7595330694
	private Void _OnSceneLoaded(String sceneName) { }
	// RVA: 0x2d18798 VA: 0x7595330798
	private IEnumerator _ShowBlackLoading() { }
	// RVA: 0x2d18844 VA: 0x7595330844
	private IEnumerator _HideBlackLoading() { }
	// RVA: 0x2d188f0 VA: 0x75953308f0
	private IEnumerator _ShowSceneLoading(String illustId) { }
	// RVA: 0x2d189c0 VA: 0x75953309c0
	private IEnumerator _HideSceneLoading() { }
	// RVA: 0x2d18a6c VA: 0x7595330a6c
	private IEnumerator _HideBlackAndSceneLoading() { }
	// RVA: 0x2d18b18 VA: 0x7595330b18
	private IEnumerator _PrepareLoadingsBeforeTransition() { }
	// RVA: 0x2d18bc4 VA: 0x7595330bc4
	private IEnumerator _LiteLoadBattleFinish(String sceneName, Options options) { }
	// RVA: 0x2d1791c VA: 0x759532f91c
	private Boolean _AddScene(String name) { }
	// RVA: 0x2d18cd4 VA: 0x7595330cd4
	private IEnumerator _AddSceneCoroutine(String name) { }
	// RVA: 0x2d17aa8 VA: 0x759532faa8
	private Boolean _AddAdditiveBattleScene(IAddtiveBattleScene battleScene) { }
	// RVA: 0x2d18da4 VA: 0x7595330da4
	private IEnumerator _AddAdditiveBattleSceneCoroutine() { }
	// RVA: 0x2d17cb4 VA: 0x759532fcb4
	private Boolean _RemoveAdditiveBattleScene() { }
	// RVA: 0x2d18e50 VA: 0x7595330e50
	private IEnumerator _RemoveAdditiveBattleSceneCoroutine(Boolean bySceneTrans) { }
	// RVA: 0x2d18f18 VA: 0x7595330f18
	private static Void _DeletePersistentRes() { }
	// RVA: 0x2d18ff0 VA: 0x7595330ff0
	private static Void _DeleleAllPlayerPrefs() { }
	// RVA: 0x2d182cc VA: 0x75953302cc
	private Void _MayOverrideNextScene(String fromScene, String toScene, ref Options options) { }
	// RVA: 0x2d1920c VA: 0x759533120c
	private Boolean _TryHookStoryScene(String fromScene, String toScene, ref Options options) { }
	// RVA: 0x2d195f4 VA: 0x75953315f4
	private static IEnumerator _LoadTargetSceneAsync(String sceneName, Options options) { }
	// RVA: 0x2d196c8 VA: 0x75953316c8
	private static IEnumerator _LoadTargetSceneAsyncFastMode(String sceneName, Options options, InvokeWhenUnlock activeSceneLatch) { }
	// RVA: 0x2d197b4 VA: 0x75953317b4
	private static Void _BeforeSceneLoadingStart() { }
	// RVA: 0x2d19854 VA: 0x7595331854
	public static Boolean CheckIsInBattleScene() { }
	// RVA: 0x2d198c8 VA: 0x75953318c8
	public static Boolean CheckIsInStoryScene() { }
	// RVA: 0x2d19944 VA: 0x7595331944
	public Void .ctor() { }
	// RVA: 0x2d19a64 VA: 0x7595331a64
	private Boolean <_AddAdditiveBattleSceneCoroutine>b__67_0() { }
	// RVA: 0x2d19a74 VA: 0x7595331a74
	private Boolean <_RemoveAdditiveBattleSceneCoroutine>b__69_0() { }
}
```