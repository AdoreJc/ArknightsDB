# HGUniWebViewMgr

**Namespace:** `Hypergryph.SDK`


## Fields

- `Boolean m_isInited`


## Methods

- `Void Start()`

- `Void OnApplicationPause(Boolean)`

- `Void OnExtraInfo(String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Hypergryph.SDK
public class HGUniWebViewMgr : MonoBehaviour
{
	public const String CALLBACK_GO_NAME; // 0x0
	private static HGUniWebViewMgr s_instance; // 0x0
	private Boolean m_isInited; // 0x18
	private static Adapter s_adapter; // 0x8


	// RVA: 0x66d2690 VA: 0x7598cea690
	public static Void InitIfNot(Adapter adapter) { }
	// RVA: 0x66d286c VA: 0x7598cea86c
	public static Boolean IsInited() { }
	// RVA: 0x66d2914 VA: 0x7598cea914
	public static Void IsNew(String type) { }
	// RVA: 0x66d29d4 VA: 0x7598cea9d4
	public static Void IsNewByCache(String type) { }
	// RVA: 0x66d2a94 VA: 0x7598ceaa94
	public static Void LoadWebview(String type, UserData userData) { }
	// RVA: 0x66d2ba8 VA: 0x7598ceaba8
	public static Void LoadWebview(String type, UserData userData, UrlParams urlParams) { }
	// RVA: 0x66d2d08 VA: 0x7598cead08
	public static Void CloseWebview() { }
	// RVA: 0x66d2db4 VA: 0x7598ceadb4
	public static Void ToastInsideWebview(Int32 level, String message) { }
	// RVA: 0x66d2e7c VA: 0x7598ceae7c
	public static Void PreloadWebview(String type) { }
	// RVA: 0x66d2f3c VA: 0x7598ceaf3c
	public static Boolean CheckPreloadStatus() { }
	// RVA: 0x66d2fec VA: 0x7598ceafec
	public static Void LoadMiniWebview(String url, UserData userData, MiniWebCustomStyle customStyle) { }
	// RVA: 0x66d314c VA: 0x7598ceb14c
	private Void Start() { }
	// RVA: 0x66d32c0 VA: 0x7598ceb2c0
	private Void OnApplicationPause(Boolean pause) { }
	// RVA: 0x66d33bc VA: 0x7598ceb3bc
	public Void OnExtraInfo(String jsonData) { }
	// RVA: 0x66d35cc VA: 0x7598ceb5cc
	public Void .ctor() { }
}
```