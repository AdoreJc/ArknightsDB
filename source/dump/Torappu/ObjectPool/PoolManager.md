# PoolManager

**Namespace:** `Torappu.ObjectPool`


## Fields

- `Boolean _usePoolManager`

- `Boolean _keepInNextScene`

- `Boolean _autoAddMissingPool`

- `Boolean m_keepInNextScene`

- `Option m_option`

- `IEnumerator m_unloadCoroutine`

- `AbstractAssetLoader m_assetLoader`

- `BaseAssetLoader m_baseAssetLoader`


## Properties

- `Boolean usePoolManager`

- `AbstractAssetLoader assetLoader`

- `Boolean isUnloading`


## Methods

- `Boolean get_usePoolManager()`

- `AbstractAssetLoader get_assetLoader()`

- `Boolean get_isUnloading()`

- `Void SetOption(Option)`

- `Boolean BattleOnly_RawRecycle(GameObject)`

- `Void UnloadPoolsWithKeptConfig(IList`1)`

- `Void _StopUnloadIfNecessary(Boolean)`

- `GameObjectPool _NewPool(ObjectConfig)`

- `GameObjectPool _NewPool(GameObject, Options)`

- `GameObjectPool _NewPool(String, Options)`

- `Boolean _ContainsPool(String)`

- `GameObject _AllocateInternal(String, Vector3, Quaternion, Transform)`

- `GameObject _AllocateInternal(GameObject, Vector3, Quaternion, Transform)`

- `Boolean _RecycleInternal(Component)`

- `Boolean _RecycleInternal(GameObject)`

- `Void _RecycleInternal(GameObject, Single)`

- `Void _RecycleInternal(Component, Single)`

- `IEnumerator _RecycleAsync(GameObject, Single)`

- `IEnumerator _RecycleAsync(Component, Single)`

- `String _GetNameOfPrefab(GameObject)`

- `Transform _NewPoolContainer(String)`

- `GameObject _OnNewObject(GameObject, GameObjectPool)`

- `Void _OnSceneUnloaded(Scene)`

- `IEnumerator _DoUnloadUnused(IList`1)`

- `Void _PruneAllPools()`

- `Boolean _IsPoolKeyInConfigs(IList`1, String)`

- `Void _OnSceneLoaded(Scene, LoadSceneMode)`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.ObjectPool
public class PoolManager : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private const Int32 UNLOAD_POOL_PER_FRAME; // 0x0
	private const String NON_RESOURCE_PREFIX; // 0x0
	private Boolean _usePoolManager; // 0x18
	private Boolean _keepInNextScene; // 0x19
	private Boolean _autoAddMissingPool; // 0x1a
	private ObjectConfig[] _scenePools; // 0x20
	private Boolean m_keepInNextScene; // 0x28
	private Option m_option; // 0x29
	private IEnumerator m_unloadCoroutine; // 0x30
	private AbstractAssetLoader m_assetLoader; // 0x38
	private Dictionary`2 m_pools; // 0x40
	private Dictionary`2 m_initialObjects; // 0x48
	private Dictionary`2 m_instanceIdToPoolMap; // 0x50
	private BaseAssetLoader m_baseAssetLoader; // 0x58
	private static List`1 s_unloadCache; // 0x0
	private static DelegateBridge __Hotfix0_get_instance; // 0x8
	private static DelegateBridge __Hotfix0_get_usePoolManager; // 0x10
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x18
	private static DelegateBridge __Hotfix0_get_isUnloading; // 0x20
	private static DelegateBridge __Hotfix0_SetOption; // 0x28
	private static DelegateBridge __Hotfix0_BattleOnly_RawRecycle; // 0x30
	private static DelegateBridge __Hotfix0_UnloadPoolsWithKeptConfig; // 0x38
	private static DelegateBridge __Hotfix0__StopUnloadIfNecessary; // 0x40
	private static DelegateBridge __Hotfix0__NewPool; // 0x48
	private static DelegateBridge __Hotfix1__NewPool; // 0x50
	private static DelegateBridge __Hotfix2__NewPool; // 0x58
	private static DelegateBridge __Hotfix0__ContainsPool; // 0x60
	private static DelegateBridge __Hotfix0__AllocateInternal; // 0x68
	private static DelegateBridge __Hotfix1__AllocateInternal; // 0x70
	private static DelegateBridge __Hotfix0__RecycleInternal; // 0x78
	private static DelegateBridge __Hotfix1__RecycleInternal; // 0x80
	private static DelegateBridge __Hotfix2__RecycleInternal; // 0x88
	private static DelegateBridge __Hotfix3__RecycleInternal; // 0x90
	private static DelegateBridge __Hotfix0__RecycleAsync; // 0x98
	private static DelegateBridge __Hotfix1__RecycleAsync; // 0xa0
	private static DelegateBridge __Hotfix0__WaitForFixedSeconds; // 0xa8
	private static DelegateBridge __Hotfix0__GetNameOfPrefab; // 0xb0
	private static DelegateBridge __Hotfix0__NewPoolContainer; // 0xb8
	private static DelegateBridge __Hotfix0_OnInit; // 0xc0
	private static DelegateBridge __Hotfix0_OnDuplicated; // 0xc8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xd0
	private static DelegateBridge __Hotfix0__OnNewObject; // 0xd8
	private static DelegateBridge __Hotfix0__OnSceneUnloaded; // 0xe0
	private static DelegateBridge __Hotfix0__DoUnloadUnused; // 0xe8
	private static DelegateBridge __Hotfix0__PruneAllPools; // 0xf0
	private static DelegateBridge __Hotfix0__IsPoolKeyInConfigs; // 0xf8
	private static DelegateBridge __Hotfix0__OnSceneLoaded; // 0x100
	private static DelegateBridge __Hotfix0_OnEnable; // 0x108
	private static DelegateBridge __Hotfix0_OnDisable; // 0x110
	private static DelegateBridge __Hotfix0_Start; // 0x118
	private static DelegateBridge __Hotfix0_LoadPool; // 0x120
	private static DelegateBridge __Hotfix0_LoadPools; // 0x128
	private static DelegateBridge __Hotfix1_LoadPools; // 0x130
	private static DelegateBridge __Hotfix0_ContainsPool; // 0x138
	private static DelegateBridge __Hotfix0_Allocate; // 0x140
	private static DelegateBridge __Hotfix1_Allocate; // 0x148
	private static DelegateBridge __Hotfix2_Allocate; // 0x150
	private static DelegateBridge __Hotfix3_Allocate; // 0x158
	private static DelegateBridge __Hotfix4_Allocate; // 0x160
	private static DelegateBridge __Hotfix5_Allocate; // 0x168
	private static DelegateBridge __Hotfix6_Allocate; // 0x170
	private static DelegateBridge __Hotfix7_Allocate; // 0x178
	private static DelegateBridge __Hotfix8_Allocate; // 0x180
	private static DelegateBridge __Hotfix9_Allocate; // 0x188
	private static DelegateBridge __Hotfix10_Allocate; // 0x190
	private static DelegateBridge __Hotfix11_Allocate; // 0x198
	private static DelegateBridge __Hotfix0_Recycle; // 0x1a0
	private static DelegateBridge __Hotfix1_Recycle; // 0x1a8
	private static DelegateBridge __Hotfix2_Recycle; // 0x1b0
	private static DelegateBridge __Hotfix3_Recycle; // 0x1b8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1c0

	private static PoolManager instance { get; }
	public Boolean usePoolManager { get; }
	public AbstractAssetLoader assetLoader { get; }
	public Boolean isUnloading { get; }

	// RVA: 0x3568990 VA: 0x7595b80990
	private static PoolManager get_instance() { }
	// RVA: 0x3568a2c VA: 0x7595b80a2c
	public Boolean get_usePoolManager() { }
	// RVA: 0x3568aa4 VA: 0x7595b80aa4
	public AbstractAssetLoader get_assetLoader() { }
	// RVA: 0x3568b1c VA: 0x7595b80b1c
	public Boolean get_isUnloading() { }
	// RVA: 0x3568b9c VA: 0x7595b80b9c
	public Void SetOption(Option option) { }
	// RVA: 0x3568c28 VA: 0x7595b80c28
	public Boolean BattleOnly_RawRecycle(GameObject obj) { }
	// RVA: 0x3568dd4 VA: 0x7595b80dd4
	public Void UnloadPoolsWithKeptConfig(IList`1 keptConfigs) { }
	// RVA: 0x3568e94 VA: 0x7595b80e94
	private Void _StopUnloadIfNecessary(Boolean showError) { }
	// RVA: 0x3569224 VA: 0x7595b81224
	private GameObjectPool _NewPool(ObjectConfig config) { }
	// RVA: 0x3569650 VA: 0x7595b81650
	private GameObjectPool _NewPool(GameObject prefab, Options options) { }
	// RVA: 0x356936c VA: 0x7595b8136c
	private GameObjectPool _NewPool(String name, Options options) { }
	// RVA: 0x3569b70 VA: 0x7595b81b70
	private Boolean _ContainsPool(String name) { }
	// RVA: 0x3569c20 VA: 0x7595b81c20
	private GameObject _AllocateInternal(String name, Vector3 position, Quaternion rotation, Transform parent) { }
	// RVA: 0x3569e2c VA: 0x7595b81e2c
	private GameObject _AllocateInternal(GameObject prefab, Vector3 position, Quaternion rotation, Transform parent) { }
	// RVA: 0x356a060 VA: 0x7595b82060
	private Boolean _RecycleInternal(Component comp) { }
	// RVA: 0x3568cb8 VA: 0x7595b80cb8
	private Boolean _RecycleInternal(GameObject obj) { }
	// RVA: 0x356a14c VA: 0x7595b8214c
	private Void _RecycleInternal(GameObject obj, Single delay) { }
	// RVA: 0x356a348 VA: 0x7595b82348
	private Void _RecycleInternal(Component comp, Single delay) { }
	// RVA: 0x356a250 VA: 0x7595b82250
	private IEnumerator _RecycleAsync(GameObject obj, Single delay) { }
	// RVA: 0x356a44c VA: 0x7595b8244c
	private IEnumerator _RecycleAsync(Component comp, Single delay) { }
	// RVA: 0x356a594 VA: 0x7595b82594
	private static IEnumerator _WaitForFixedSeconds(Single time) { }
	// RVA: 0x356994c VA: 0x7595b8194c
	private String _GetNameOfPrefab(GameObject prefab) { }
	// RVA: 0x3569a34 VA: 0x7595b81a34
	private Transform _NewPoolContainer(String name) { }
	// RVA: 0x356a678 VA: 0x7595b82678
	protected override Void OnInit() { }
	// RVA: 0x356a7c0 VA: 0x7595b827c0
	protected override Void OnDuplicated() { }
	// RVA: 0x356a890 VA: 0x7595b82890
	protected override Void OnDestroy() { }
	// RVA: 0x356aa20 VA: 0x7595b82a20
	private GameObject _OnNewObject(GameObject obj, GameObjectPool pool) { }
	// RVA: 0x356aaf8 VA: 0x7595b82af8
	private Void _OnSceneUnloaded(Scene scene) { }
	// RVA: 0x3568fa8 VA: 0x7595b80fa8
	private IEnumerator _DoUnloadUnused(IList`1 keptConfigs) { }
	// RVA: 0x3569088 VA: 0x7595b81088
	private Void _PruneAllPools() { }
	// RVA: 0x356ad70 VA: 0x7595b82d70
	private Boolean _IsPoolKeyInConfigs(IList`1 keptConfigs, String poolKey) { }
	// RVA: 0x356b100 VA: 0x7595b83100
	private Void _OnSceneLoaded(Scene scene, LoadSceneMode mode) { }
	// RVA: 0x356b2b0 VA: 0x7595b832b0
	private Void OnEnable() { }
	// RVA: 0x356b3cc VA: 0x7595b833cc
	private Void OnDisable() { }
	// RVA: 0x356b4e8 VA: 0x7595b834e8
	private Void Start() { }
	// RVA: 0x356b618 VA: 0x7595b83618
	public static Void LoadPool(ObjectConfig config) { }
	// RVA: 0x356b750 VA: 0x7595b83750
	public static Void LoadPools(IList`1 configs) { }
	// RVA: 0x356b994 VA: 0x7595b83994
	public static Void LoadPools(PreloadConfigAsset preloadConfig) { }
	// RVA: 0x356ba28 VA: 0x7595b83a28
	public static Boolean ContainsPool(String name) { }
	// RVA: 0x356bb38 VA: 0x7595b83b38
	public static GameObject Allocate(String name, Vector3 position, Quaternion rotation, Transform parent) { }
	// RVA: 0x356be0c VA: 0x7595b83e0c
	public static GameObject Allocate(String name, Vector3 position, Quaternion rotation) { }
	// RVA: 0x356bf1c VA: 0x7595b83f1c
	public static GameObject Allocate(String name) { }
	// RVA: 0x VA: 0x0
	public static T Allocate(String name, Vector3 position, Quaternion rotation, Transform parent) { }
	// RVA: 0x VA: 0x0
	public static T Allocate(String name, Vector3 position, Quaternion rotation) { }
	// RVA: 0x VA: 0x0
	public static T Allocate(String name) { }
	// RVA: 0x356c064 VA: 0x7595b84064
	public static GameObject Allocate(GameObject prefab, Vector3 position, Quaternion rotation, Transform parent) { }
	// RVA: 0x356c2e8 VA: 0x7595b842e8
	public static GameObject Allocate(GameObject prefab, Vector3 position, Quaternion rotation) { }
	// RVA: 0x356c3f8 VA: 0x7595b843f8
	public static GameObject Allocate(GameObject prefab) { }
	// RVA: 0x VA: 0x0
	public static T Allocate(Component comp, Vector3 position, Quaternion rotation, Transform parent) { }
	// RVA: 0x VA: 0x0
	public static T Allocate(Component comp, Vector3 position, Quaternion rotation) { }
	// RVA: 0x VA: 0x0
	public static T Allocate(Component comp) { }
	// RVA: 0x356c540 VA: 0x7595b84540
	public static Boolean Recycle(GameObject obj) { }
	// RVA: 0x356c680 VA: 0x7595b84680
	public static Void Recycle(GameObject obj, Single delay) { }
	// RVA: 0x356c7d8 VA: 0x7595b847d8
	public static Boolean Recycle(Component comp) { }
	// RVA: 0x356c92c VA: 0x7595b8492c
	public static Void Recycle(Component comp, Single delay) { }
	// RVA: 0x356cb40 VA: 0x7595b84b40
	public Void .ctor() { }
	// RVA: 0x356cdac VA: 0x7595b84dac
	private static Void .cctor() { }
}
```