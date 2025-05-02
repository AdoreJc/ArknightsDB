# PageAssetPool

**Namespace:** `Torappu.UI`


## Fields

- `Int32 _poolMaxSize`

- `UIPageAssetGroup m_assetGroup`


## Properties

- `Int32 poolMaxSize`

- `Int32 poolCapacity`


## Methods

- `Int32 get_poolMaxSize()`

- `Int32 get_poolCapacity()`

- `AssetType LoadAsset(String)`

- `Void RecordInstPrefab(GameObject, String)`

- `Void MarkAssetReused(String)`

- `Void _AdjustStorage()`

- `Void _ClearAll()`

- `AssetType _LoadAsset(String)`

- `Void _UnloadAsset(AssetType)`

- `Int32 PageOnlyAssetGroupId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class PageAssetPool`1 : PageSingleComponent
{
	private Int32 _poolMaxSize; // 0x0
	private LinkedList`1 m_assetCache; // 0x0
	private UIPageAssetGroup m_assetGroup; // 0x0
	private List`1 m_instRes; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePoolSizeLimit; // 0x0
	private static DelegateBridge __Hotfix0_get_poolMaxSize; // 0x0
	private static DelegateBridge __Hotfix0_get_poolCapacity; // 0x0
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x0
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x0
	private static DelegateBridge __Hotfix0_RecordInstPrefab; // 0x0
	private static DelegateBridge __Hotfix0_MarkAssetReused; // 0x0
	private static DelegateBridge __Hotfix0__AdjustStorage; // 0x0
	private static DelegateBridge __Hotfix0__ClearAll; // 0x0
	private static DelegateBridge __Hotfix0__LoadAsset; // 0x0
	private static DelegateBridge __Hotfix0__UnloadAsset; // 0x0
	private static DelegateBridge __Hotfix0_PageOnlyAssetGroupId; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0

	protected virtual Boolean enablePoolSizeLimit { get; }
	protected Int32 poolMaxSize { get; }
	protected Int32 poolCapacity { get; }

	// RVA: 0x VA: 0x0
	protected virtual Boolean get_enablePoolSizeLimit() { }
	// RVA: 0x VA: 0x0
	protected Int32 get_poolMaxSize() { }
	// RVA: 0x VA: 0x0
	protected Int32 get_poolCapacity() { }
	// RVA: 0x VA: 0x0
	protected override Void OnRecycle() { }
	// RVA: 0x VA: 0x0
	protected override Void OnDestroy() { }
	// RVA: 0x VA: 0x0
	protected AssetType LoadAsset(String path) { }
	// RVA: 0x VA: 0x0
	protected Void RecordInstPrefab(GameObject obj, String path) { }
	// RVA: 0x VA: 0x0
	protected Void MarkAssetReused(String path) { }
	// RVA: 0x VA: 0x0
	private Void _AdjustStorage() { }
	// RVA: 0x VA: 0x0
	private Void _ClearAll() { }
	// RVA: 0x VA: 0x0
	private AssetType _LoadAsset(String path) { }
	// RVA: 0x VA: 0x0
	private Void _UnloadAsset(AssetType target) { }
	// RVA: 0x VA: 0x0
	public Int32 PageOnlyAssetGroupId() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```