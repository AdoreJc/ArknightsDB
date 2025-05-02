# GameObjectSplitFrameLoadBalancer

**Namespace:** `Torappu.Building`


## Fields

- `AbstractAssetLoader m_assetLoader`

- `Options m_loadOptions`

- `PeriodicTicker m_idleTicker`

- `Boolean m_isPaused`


## Properties

- `Boolean isPaused`

- `AbstractAssetLoader internalAssetLoader`


## Methods

- `Boolean get_isPaused()`

- `Void set_isPaused(Boolean)`

- `AbstractAssetLoader get_internalAssetLoader()`

- `Void LoadAsync(String, IDynamicAssetWrapper, Action`2)`

- `IDynamicAssetHandler LoadAsset(String, IDynamicAssetWrapper)`

- `Void UpdateFrame()`

- `Void _UpdateTasks(Heap`1)`

- `Void ClearTasks()`

- `Void ClearAll()`

- `Boolean _TryProcessOneReleaseTask()`

- `TaskStatus _TryProcessOneLoadTask()`

- `Void _PickAndProcessTask(AsyncTask)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class GameObjectSplitFrameLoadBalancer
{
	private AbstractAssetLoader m_assetLoader; // 0x10
	private Options m_loadOptions; // 0x18
	private List`1 m_cachedTasks; // 0x28
	private Heap`1 m_pendingTasks; // 0x30
	private Heap`1 m_completeTasks; // 0x38
	private PeriodicTicker m_idleTicker; // 0x40
	private Boolean m_isPaused; // 0x48

	public Boolean isPaused { get; set; }
	public AbstractAssetLoader internalAssetLoader { get; }

	// RVA: 0x37b1160 VA: 0x7595dc9160
	public Boolean get_isPaused() { }
	// RVA: 0x37b1168 VA: 0x7595dc9168
	public Void set_isPaused(Boolean value) { }
	// RVA: 0x37b11a8 VA: 0x7595dc91a8
	public AbstractAssetLoader get_internalAssetLoader() { }
	// RVA: 0x37b11b0 VA: 0x7595dc91b0
	public Void .ctor(AbstractAssetLoader assetLoader) { }
	// RVA: 0x37b1220 VA: 0x7595dc9220
	public Void .ctor(AbstractAssetLoader assetLoader, Options options) { }
	// RVA: 0x37b13a8 VA: 0x7595dc93a8
	public Void LoadAsync(String path, IDynamicAssetWrapper assetWrapper, Action`2 callback) { }
	// RVA: 0x37b1508 VA: 0x7595dc9508
	public IDynamicAssetHandler LoadAsset(String path, IDynamicAssetWrapper assetWrapper) { }
	// RVA: 0x37b1758 VA: 0x7595dc9758
	public Void UpdateFrame() { }
	// RVA: 0x37b1864 VA: 0x7595dc9864
	private Void _UpdateTasks(Heap`1 target) { }
	// RVA: 0x37b1da8 VA: 0x7595dc9da8
	public Void ClearTasks() { }
	// RVA: 0x37b1e08 VA: 0x7595dc9e08
	public Void ClearAll() { }
	// RVA: 0x37b1cb8 VA: 0x7595dc9cb8
	private Boolean _TryProcessOneReleaseTask() { }
	// RVA: 0x37b1bb4 VA: 0x7595dc9bb4
	private TaskStatus _TryProcessOneLoadTask() { }
	// RVA: 0x37b1e30 VA: 0x7595dc9e30
	private Void _PickAndProcessTask(AsyncTask task) { }
}
```