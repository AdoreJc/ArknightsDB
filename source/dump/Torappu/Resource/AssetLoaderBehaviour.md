# AssetLoaderBehaviour

**Namespace:** `Torappu.Resource`


## Fields

- `Boolean m_cached`

- `AbstractAssetLoader m_assetLoader`


## Properties

- `AbstractAssetLoader internalLoader`


## Methods

- `AbstractAssetLoader get_internalLoader()`

- `T Load(String)`

- `Object Load(String)`

- `AsyncResource LoadAsync(String)`

- `AsyncResource LoadAsync(String)`

- `Void LoadAsync(String, Action`2)`

- `Void LoadAsync(String, Action`2)`

- `Boolean TryLoad(String, out)`

- `Boolean TryLoad(String, out)`

- `Void Unload(Object)`

- `Void ClearAll()`

- `Void Awake()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource
public class AssetLoaderBehaviour : MonoBehaviour
{
	private Boolean m_cached; // 0x18
	private AbstractAssetLoader m_assetLoader; // 0x20

	public AbstractAssetLoader internalLoader { get; }

	// RVA: 0x37414f4 VA: 0x7595d594f4
	public AbstractAssetLoader get_internalLoader() { }
	// RVA: 0x VA: 0x0
	public T Load(String path) { }
	// RVA: 0x37414fc VA: 0x7595d594fc
	public Object Load(String path) { }
	// RVA: 0x VA: 0x0
	public T[] LoadAll(String path) { }
	// RVA: 0x3741518 VA: 0x7595d59518
	public Object[] LoadAll(String path) { }
	// RVA: 0x VA: 0x0
	public AsyncResource LoadAsync(String path) { }
	// RVA: 0x3741534 VA: 0x7595d59534
	public AsyncResource LoadAsync(String path) { }
	// RVA: 0x VA: 0x0
	public Void LoadAsync(String path, Action`2 cb) { }
	// RVA: 0x3741550 VA: 0x7595d59550
	public Void LoadAsync(String path, Action`2 cb) { }
	// RVA: 0x VA: 0x0
	public Boolean TryLoad(String path, out T obj) { }
	// RVA: 0x374156c VA: 0x7595d5956c
	public Boolean TryLoad(String path, out Object obj) { }
	// RVA: 0x3741588 VA: 0x7595d59588
	public Void Unload(Object asset) { }
	// RVA: 0x37415a4 VA: 0x7595d595a4
	public Void ClearAll() { }
	// RVA: 0x37415bc VA: 0x7595d595bc
	private Void Awake() { }
	// RVA: 0x374165c VA: 0x7595d5965c
	private Void OnDestroy() { }
	// RVA: 0x3741674 VA: 0x7595d59674
	public Void .ctor() { }
}
```