# HGUniWebviewPluginAndroid

**Namespace:** `Hypergryph.SDK`


## Fields

- `AndroidJavaClass jc`

- `AndroidJavaObject currentActivity`

- `AndroidJavaClass webviewModule`

- `AndroidJavaObject appController`


## Methods

- `Void init(String)`

- `Void startWebSupport()`

- `Void stopWebSupport()`

- `Void isNew(String)`

- `Void isNew(String, String)`

- `Void isNewByCache(String)`

- `Void loadWebview(String, String)`

- `Void loadWebview(String, String, String)`

- `Void closeWebview()`

- `Void toastInsideWebview(Int32, String)`

- `Void preloadWebview(String)`

- `Boolean checkPreloadStatus()`

- `Void loadMiniWebview(String, String, String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Hypergryph.SDK
public class HGUniWebviewPluginAndroid : IUniWebview
{
	private AndroidJavaClass jc; // 0x10
	private AndroidJavaObject currentActivity; // 0x18
	private AndroidJavaClass webviewModule; // 0x20
	private AndroidJavaObject appController; // 0x28


	// RVA: 0x66d24c4 VA: 0x7598cea4c4
	public Void .ctor() { }
	// RVA: 0x66d35dc VA: 0x7598ceb5dc
	public Void init(String env) { }
	// RVA: 0x66d35e0 VA: 0x7598ceb5e0
	public Void startWebSupport() { }
	// RVA: 0x66d374c VA: 0x7598ceb74c
	public Void stopWebSupport() { }
	// RVA: 0x66d38b8 VA: 0x7598ceb8b8
	public Void isNew(String type) { }
	// RVA: 0x66d3a7c VA: 0x7598ceba7c
	public Void isNew(String type, String urlParams) { }
	// RVA: 0x66d3c8c VA: 0x7598cebc8c
	public Void isNewByCache(String type) { }
	// RVA: 0x66d3e50 VA: 0x7598cebe50
	public Void loadWebview(String type, String userData) { }
	// RVA: 0x66d4060 VA: 0x7598cec060
	public Void loadWebview(String type, String userData, String urlParams) { }
	// RVA: 0x66d42c8 VA: 0x7598cec2c8
	public Void closeWebview() { }
	// RVA: 0x66d4434 VA: 0x7598cec434
	public Void toastInsideWebview(Int32 level, String message) { }
	// RVA: 0x66d4620 VA: 0x7598cec620
	public Void preloadWebview(String type) { }
	// RVA: 0x66d47e4 VA: 0x7598cec7e4
	public Boolean checkPreloadStatus() { }
	// RVA: 0x66d494c VA: 0x7598cec94c
	public Void loadMiniWebview(String url, String userData, String customStyle) { }
}
```