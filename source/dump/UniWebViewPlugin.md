# UniWebViewPlugin

**Namespace:** ` `


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class UniWebViewPlugin
{
	private static AndroidJavaClass webView; // 0x0


	// RVA: 0x6466348 VA: 0x7598a7e348
	public static Void Init(String name, Int32 top, Int32 left, Int32 bottom, Int32 right) { }
	// RVA: 0x646065c VA: 0x7598a7865c
	public static Void ChangeInsets(String name, Int32 top, Int32 left, Int32 bottom, Int32 right) { }
	// RVA: 0x6461d4c VA: 0x7598a79d4c
	public static Void Load(String name, String url) { }
	// RVA: 0x6461e9c VA: 0x7598a79e9c
	public static Void LoadHTMLString(String name, String htmlString, String baseUrl) { }
	// RVA: 0x646209c VA: 0x7598a7a09c
	public static Void Reload(String name) { }
	// RVA: 0x6462220 VA: 0x7598a7a220
	public static Void Stop(String name) { }
	// RVA: 0x6462820 VA: 0x7598a7a820
	public static Void EvaluatingJavaScript(String name, String javaScript) { }
	// RVA: 0x64629cc VA: 0x7598a7a9cc
	public static Void AddJavaScript(String name, String javaScript) { }
	// RVA: 0x6462390 VA: 0x7598a7a390
	public static Void Show(String name, Boolean fade, Int32 direction, Single duration) { }
	// RVA: 0x64625d8 VA: 0x7598a7a5d8
	public static Void Hide(String name, Boolean fade, Int32 direction, Single duration) { }
	// RVA: 0x6462bf0 VA: 0x7598a7abf0
	public static Void CleanCache(String name) { }
	// RVA: 0x6462d7c VA: 0x7598a7ad7c
	public static Void CleanCookie(String name, String key) { }
	// RVA: 0x64630e4 VA: 0x7598a7b0e4
	public static String GetCookie(String url, String key) { }
	// RVA: 0x6462f30 VA: 0x7598a7af30
	public static Void SetCookie(String url, String cookie) { }
	// RVA: 0x6466760 VA: 0x7598a7e760
	public static Void Destroy(String name) { }
	// RVA: 0x64637e8 VA: 0x7598a7b7e8
	public static Void SetSpinnerShowWhenLoading(String name, Boolean show) { }
	// RVA: 0x64639e0 VA: 0x7598a7b9e0
	public static Void SetSpinnerText(String name, String text) { }
	// RVA: 0x64632e0 VA: 0x7598a7b2e0
	public static Void TransparentBackground(String name, Boolean transparent) { }
	// RVA: 0x6463500 VA: 0x7598a7b500
	public static Void SetBackgroundColor(String name, Single r, Single g, Single b, Single a) { }
	// RVA: 0x6463f98 VA: 0x7598a7bf98
	public static Boolean CanGoBack(String name) { }
	// RVA: 0x6464134 VA: 0x7598a7c134
	public static Boolean CanGoForward(String name) { }
	// RVA: 0x64642d0 VA: 0x7598a7c2d0
	public static Void GoBack(String name) { }
	// RVA: 0x6464454 VA: 0x7598a7c454
	public static Void GoForward(String name) { }
	// RVA: 0x646093c VA: 0x7598a7893c
	public static String GetCurrentUrl(String name) { }
	// RVA: 0x6460b20 VA: 0x7598a78b20
	public static Void SetBackButtonEnable(String name, Boolean enable) { }
	// RVA: 0x6460d44 VA: 0x7598a78d44
	public static Void SetBounces(String name, Boolean enable) { }
	// RVA: 0x6460f68 VA: 0x7598a78f68
	public static Void SetZoomEnable(String name, Boolean enable) { }
	// RVA: 0x6464980 VA: 0x7598a7c980
	public static Void AddUrlScheme(String name, String scheme) { }
	// RVA: 0x6464b50 VA: 0x7598a7cb50
	public static Void RemoveUrlScheme(String name, String scheme) { }
	// RVA: 0x6463bb0 VA: 0x7598a7bbb0
	public static Void SetUseWideViewPort(String name, Boolean use) { }
	// RVA: 0x6463da8 VA: 0x7598a7bda8
	public static Void LoadWithOverviewMode(String name, Boolean overview) { }
	// RVA: 0x6461c34 VA: 0x7598a79c34
	public static Void SetUserAgent(String userAgent) { }
	// RVA: 0x6461158 VA: 0x7598a79158
	public static String GetUserAgent(String name) { }
	// RVA: 0x6461308 VA: 0x7598a79308
	public static Single GetAlpha(String name) { }
	// RVA: 0x64614c4 VA: 0x7598a794c4
	public static Void SetAlpha(String name, Single alpha) { }
	// RVA: 0x6461a68 VA: 0x7598a79a68
	public static Void SetImmersiveModeEnabled(String name, Boolean enabled) { }
	// RVA: 0x64645e0 VA: 0x7598a7c5e0
	public static Void AddPermissionRequestTrustSite(String name, String url) { }
	// RVA: 0x6464d30 VA: 0x7598a7cd30
	public static Void SetHeaderField(String name, String key, String value) { }
	// RVA: 0x6464f38 VA: 0x7598a7cf38
	public static Void SetVerticalScrollBarShow(String name, Boolean show) { }
	// RVA: 0x6465130 VA: 0x7598a7d130
	public static Void SetHorizontalScrollBarShow(String name, Boolean show) { }
	// RVA: 0x64616b8 VA: 0x7598a796b8
	public static Boolean GetOpenLinksInExternalBrowser(String name) { }
	// RVA: 0x646185c VA: 0x7598a7985c
	public static Void SetOpenLinksInExternalBrowser(String name, Boolean value) { }
	// RVA: 0x64654f8 VA: 0x7598a7d4f8
	public static Void SetWebContentsDebuggingEnabled(Boolean enabled) { }
	// RVA: 0x6465328 VA: 0x7598a7d328
	public static Void SetAllowAutoPlay(String name, Boolean value) { }
	// RVA: 0x64647b0 VA: 0x7598a7c7b0
	public static Void AddCertTrustedHost(String name, String host) { }
	// RVA: 0x646568c VA: 0x7598a7d68c
	public static Void SetAllowThirdPartyCookies(Boolean allowed) { }
	// RVA: 0x6467a10 VA: 0x7598a7fa10
	public Void .ctor() { }
	// RVA: 0x6467a18 VA: 0x7598a7fa18
	private static Void .cctor() { }
}
```