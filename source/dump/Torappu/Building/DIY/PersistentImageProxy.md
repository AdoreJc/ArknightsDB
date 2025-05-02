# PersistentImageProxy

**Namespace:** `Torappu.Building.DIY`


## Fields

- `String m_basePath`

- `String m_cacheInfoFileName`


## Methods

- `Void _LoadCacheInfo()`

- `Void _SaveCacheInfo()`

- `String _StringifyDIYPreset(IDIYPreset)`

- `CacheInfo _GetCacheInfo(IDIYPreset, Boolean)`

- `Boolean _DIYPresetStringMatch(IDIYPreset, String)`

- `Void Setup(String)`

- `String _GetNextFileName()`

- `Texture2D TryFetchLocalTexture(IDIYPreset)`

- `IEnumerator QueryImage(IDIYPreset, String, Action`1, Action, Single)`

- `Int32 GetLocalCacheFileStorageCost()`

- `Void ClearCache(IDIYPresetProvider)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class PersistentImageProxy
{
	private const String CACHE_MAP_FILE_NAME; // 0x0
	private Dictionary`2 m_imageCache; // 0x10
	private String m_basePath; // 0x18
	private List`1 m_cacheInfoList; // 0x20
	private String m_cacheInfoFileName; // 0x28


	// RVA: 0x37dbc24 VA: 0x7595df3c24
	private Void _LoadCacheInfo() { }
	// RVA: 0x37dc040 VA: 0x7595df4040
	private Void _SaveCacheInfo() { }
	// RVA: 0x37dc390 VA: 0x7595df4390
	public String _StringifyDIYPreset(IDIYPreset preset) { }
	// RVA: 0x37dcc44 VA: 0x7595df4c44
	private Func`2 _GetStringReadFunc(String str) { }
	// RVA: 0x37dcd14 VA: 0x7595df4d14
	private CacheInfo _GetCacheInfo(IDIYPreset preset, Boolean needCreate) { }
	// RVA: 0x37dcee8 VA: 0x7595df4ee8
	public Boolean _DIYPresetStringMatch(IDIYPreset preset, String str) { }
	// RVA: 0x37dd750 VA: 0x7595df5750
	public Void Setup(String basePath) { }
	// RVA: 0x37dd964 VA: 0x7595df5964
	private String _GetNextFileName() { }
	// RVA: 0x37ddabc VA: 0x7595df5abc
	public Texture2D TryFetchLocalTexture(IDIYPreset preset) { }
	// RVA: 0x37dddb4 VA: 0x7595df5db4
	public IEnumerator QueryImage(IDIYPreset preset, String url, Action`1 successHandler, Action failureHandler, Single timeOut) { }
	// RVA: 0x37ddec0 VA: 0x7595df5ec0
	public Int32 GetLocalCacheFileStorageCost() { }
	// RVA: 0x37ddfa8 VA: 0x7595df5fa8
	public Void ClearCache(IDIYPresetProvider provider) { }
	// RVA: 0x37de630 VA: 0x7595df6630
	public Void .ctor() { }
}
```