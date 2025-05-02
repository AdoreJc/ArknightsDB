# ResourceOptions

**Namespace:** `Torappu.Resource`


## Fields

- `Mode _mode`

- `String _resourcePath`

- `String _staticResPath`

- `String _abPath`

- `String _gameDataPath`

- `Boolean _restoreAssetBundleNames`

- `Boolean _cachedAssetsInResourceManager`

- `Boolean _deleteResourceIndexAfterPacking`


## Properties

- `String resourcePath`

- `String staticResPath`

- `String abPath`

- `Boolean cacheAssetsInResourceManager`

- `Mode mode`

- `ResLanguage resLang`

- `Boolean hasResLang`


## Methods

- `String get_resourcePath()`

- `String get_staticResPath()`

- `String get_abPath()`

- `Boolean get_cacheAssetsInResourceManager()`

- `Mode get_mode()`

- `Void set_mode(Mode)`

- `ResLanguage get_resLang()`

- `Boolean get_hasResLang()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Resource
public class ResourceOptions : SingletonScriptableObject`1
{
	private Mode _mode; // 0x18
	private String _resourcePath; // 0x20
	private String _staticResPath; // 0x28
	private String _abPath; // 0x30
	private String _gameDataPath; // 0x38
	private Boolean _restoreAssetBundleNames; // 0x40
	private Boolean _cachedAssetsInResourceManager; // 0x41
	private Boolean _deleteResourceIndexAfterPacking; // 0x42

	public String resourcePath { get; }
	public String staticResPath { get; }
	public String abPath { get; }
	public Boolean cacheAssetsInResourceManager { get; }
	public Mode mode { get; set; }
	public ResLanguage resLang { get; }
	public Boolean hasResLang { get; }

	// RVA: 0x6799990 VA: 0x7598db1990
	public String get_resourcePath() { }
	// RVA: 0x6799998 VA: 0x7598db1998
	public String get_staticResPath() { }
	// RVA: 0x67999a0 VA: 0x7598db19a0
	public String get_abPath() { }
	// RVA: 0x67999a8 VA: 0x7598db19a8
	public Boolean get_cacheAssetsInResourceManager() { }
	// RVA: 0x67999b0 VA: 0x7598db19b0
	public Mode get_mode() { }
	// RVA: 0x67999b8 VA: 0x7598db19b8
	public Void set_mode(Mode value) { }
	// RVA: 0x67999c0 VA: 0x7598db19c0
	public ResLanguage get_resLang() { }
	// RVA: 0x67999c8 VA: 0x7598db19c8
	public Boolean get_hasResLang() { }
	// RVA: 0x67999d0 VA: 0x7598db19d0
	public static String GetResLangFolder(ResLanguage lang) { }
	// RVA: 0x6799a84 VA: 0x7598db1a84
	public Void .ctor() { }
}
```