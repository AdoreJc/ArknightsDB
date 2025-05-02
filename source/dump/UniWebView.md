# UniWebView

**Namespace:** ` `


## Fields

- `LoadCompleteDelegate OnLoadComplete`

- `LoadBeginDelegate OnLoadBegin`

- `ReceivedMessageDelegate OnReceivedMessage`

- `EvalJavaScriptFinishedDelegate OnEvalJavaScriptFinished`

- `WebViewShouldCloseDelegate OnWebViewShouldClose`

- `ReceivedKeyCodeDelegate OnReceivedKeyCode`

- `InsetsForScreenOreitationDelegate InsetsForScreenOreitation`

- `UniWebViewEdgeInsets _insets`

- `String url`

- `Boolean loadOnStart`

- `Boolean autoShowWhenLoadComplete`

- `Boolean _backButtonEnable`

- `Boolean _bouncesEnable`

- `Boolean _zoomEnable`

- `String _currentGUID`

- `Int32 _lastScreenHeight`

- `Boolean _immersiveMode`

- `Action _showTransitionAction`

- `Action _hideTransitionAction`

- `Boolean toolBarShow`


## Properties

- `UniWebViewEdgeInsets insets`

- `String currentUrl`

- `Boolean backButtonEnable`

- `Boolean bouncesEnable`

- `Boolean zoomEnable`

- `String userAgent`

- `Single alpha`

- `Boolean openLinksInExternalBrowser`

- `Boolean immersiveMode`


## Methods

- `Void add_OnLoadComplete(LoadCompleteDelegate)`

- `Void remove_OnLoadComplete(LoadCompleteDelegate)`

- `Void add_OnLoadBegin(LoadBeginDelegate)`

- `Void remove_OnLoadBegin(LoadBeginDelegate)`

- `Void add_OnReceivedMessage(ReceivedMessageDelegate)`

- `Void remove_OnReceivedMessage(ReceivedMessageDelegate)`

- `Void add_OnEvalJavaScriptFinished(EvalJavaScriptFinishedDelegate)`

- `Void remove_OnEvalJavaScriptFinished(EvalJavaScriptFinishedDelegate)`

- `Void add_OnWebViewShouldClose(WebViewShouldCloseDelegate)`

- `Void remove_OnWebViewShouldClose(WebViewShouldCloseDelegate)`

- `Void add_OnReceivedKeyCode(ReceivedKeyCodeDelegate)`

- `Void remove_OnReceivedKeyCode(ReceivedKeyCodeDelegate)`

- `Void add_InsetsForScreenOreitation(InsetsForScreenOreitationDelegate)`

- `Void remove_InsetsForScreenOreitation(InsetsForScreenOreitationDelegate)`

- `UniWebViewEdgeInsets get_insets()`

- `Void set_insets(UniWebViewEdgeInsets)`

- `Void ForceUpdateInsetsInternal(UniWebViewEdgeInsets)`

- `String get_currentUrl()`

- `Boolean get_backButtonEnable()`

- `Void set_backButtonEnable(Boolean)`

- `Boolean get_bouncesEnable()`

- `Void set_bouncesEnable(Boolean)`

- `Boolean get_zoomEnable()`

- `Void set_zoomEnable(Boolean)`

- `String get_userAgent()`

- `Single get_alpha()`

- `Void set_alpha(Single)`

- `Boolean get_openLinksInExternalBrowser()`

- `Void set_openLinksInExternalBrowser(Boolean)`

- `Boolean get_immersiveMode()`

- `Void set_immersiveMode(Boolean)`

- `Void Load()`

- `Void Load(String)`

- `Void LoadHTMLString(String, String)`

- `Void Reload()`

- `Void Stop()`

- `Void Show(Boolean, UniWebViewTransitionEdge, Single, Action)`

- `Void Hide(Boolean, UniWebViewTransitionEdge, Single, Action)`

- `Void EvaluatingJavaScript(String)`

- `Void AddJavaScript(String)`

- `Void CleanCache()`

- `Void CleanCookie(String)`

- `Void SetTransparentBackground(Boolean)`

- `Void SetBackgroundColor(Color)`

- `Void ShowToolBar(Boolean)`

- `Void HideToolBar(Boolean)`

- `Void SetShowSpinnerWhenLoading(Boolean)`

- `Void SetSpinnerLabelText(String)`

- `Void SetUseWideViewPort(Boolean)`

- `Void LoadWithOverviewMode(Boolean)`

- `Boolean CanGoBack()`

- `Boolean CanGoForward()`

- `Void GoBack()`

- `Void GoForward()`

- `Void AddPermissionRequestTrustSite(String)`

- `Void AddCertTrustedHost(String)`

- `Void AddUrlScheme(String)`

- `Void RemoveUrlScheme(String)`

- `Void SetHeaderField(String, String)`

- `Void SetVerticalScrollBarShow(Boolean)`

- `Void SetHorizontalScrollBarShow(Boolean)`

- `Void SetAllowAutoPlay(Boolean)`

- `Void SetAllowInlinePlay(Boolean)`

- `Boolean OrientationChanged()`

- `Void ResizeInternal()`

- `Void LoadComplete(String)`

- `Void LoadBegin(String)`

- `Void ReceivedMessage(String)`

- `Void WebViewDone(String)`

- `Void WebViewKeyDown(String)`

- `Void EvalJavaScriptFinished(String)`

- `Void AnimationFinished(String)`

- `Void ShowTransitionFinished(String)`

- `Void HideTransitionFinished(String)`

- `IEnumerator LoadFromJarPackage(String)`

- `Void Awake()`

- `Void Start()`

- `Void OnDestroy()`

- `Void RemoveAllListeners()`

- `Void Update()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class UniWebView : MonoBehaviour
{
	private LoadCompleteDelegate OnLoadComplete; // 0x18
	private LoadBeginDelegate OnLoadBegin; // 0x20
	private ReceivedMessageDelegate OnReceivedMessage; // 0x28
	private EvalJavaScriptFinishedDelegate OnEvalJavaScriptFinished; // 0x30
	private WebViewShouldCloseDelegate OnWebViewShouldClose; // 0x38
	private ReceivedKeyCodeDelegate OnReceivedKeyCode; // 0x40
	private InsetsForScreenOreitationDelegate InsetsForScreenOreitation; // 0x48
	private UniWebViewEdgeInsets _insets; // 0x50
	public String url; // 0x58
	public Boolean loadOnStart; // 0x60
	public Boolean autoShowWhenLoadComplete; // 0x61
	private Boolean _backButtonEnable; // 0x62
	private Boolean _bouncesEnable; // 0x63
	private Boolean _zoomEnable; // 0x64
	private String _currentGUID; // 0x68
	private Int32 _lastScreenHeight; // 0x70
	private Boolean _immersiveMode; // 0x74
	private Action _showTransitionAction; // 0x78
	private Action _hideTransitionAction; // 0x80
	public Boolean toolBarShow; // 0x88

	public UniWebViewEdgeInsets insets { get; set; }
	public String currentUrl { get; }
	public Boolean backButtonEnable { get; set; }
	public Boolean bouncesEnable { get; set; }
	public Boolean zoomEnable { get; set; }
	public String userAgent { get; }
	public Single alpha { get; set; }
	public Boolean openLinksInExternalBrowser { get; set; }
	public Boolean immersiveMode { get; set; }

	// RVA: 0x645db64 VA: 0x7598a75b64
	public Void add_OnLoadComplete(LoadCompleteDelegate value) { }
	// RVA: 0x645fffc VA: 0x7598a77ffc
	public Void remove_OnLoadComplete(LoadCompleteDelegate value) { }
	// RVA: 0x6460098 VA: 0x7598a78098
	public Void add_OnLoadBegin(LoadBeginDelegate value) { }
	// RVA: 0x6460134 VA: 0x7598a78134
	public Void remove_OnLoadBegin(LoadBeginDelegate value) { }
	// RVA: 0x645f2f8 VA: 0x7598a772f8
	public Void add_OnReceivedMessage(ReceivedMessageDelegate value) { }
	// RVA: 0x64601d0 VA: 0x7598a781d0
	public Void remove_OnReceivedMessage(ReceivedMessageDelegate value) { }
	// RVA: 0x645fbc4 VA: 0x7598a77bc4
	public Void add_OnEvalJavaScriptFinished(EvalJavaScriptFinishedDelegate value) { }
	// RVA: 0x646026c VA: 0x7598a7826c
	public Void remove_OnEvalJavaScriptFinished(EvalJavaScriptFinishedDelegate value) { }
	// RVA: 0x645ea9c VA: 0x7598a76a9c
	public Void add_OnWebViewShouldClose(WebViewShouldCloseDelegate value) { }
	// RVA: 0x6460308 VA: 0x7598a78308
	public Void remove_OnWebViewShouldClose(WebViewShouldCloseDelegate value) { }
	// RVA: 0x64603a4 VA: 0x7598a783a4
	public Void add_OnReceivedKeyCode(ReceivedKeyCodeDelegate value) { }
	// RVA: 0x6460440 VA: 0x7598a78440
	public Void remove_OnReceivedKeyCode(ReceivedKeyCodeDelegate value) { }
	// RVA: 0x645dd40 VA: 0x7598a75d40
	public Void add_InsetsForScreenOreitation(InsetsForScreenOreitationDelegate value) { }
	// RVA: 0x64604dc VA: 0x7598a784dc
	public Void remove_InsetsForScreenOreitation(InsetsForScreenOreitationDelegate value) { }
	// RVA: 0x6460578 VA: 0x7598a78578
	public UniWebViewEdgeInsets get_insets() { }
	// RVA: 0x645e90c VA: 0x7598a7690c
	public Void set_insets(UniWebViewEdgeInsets value) { }
	// RVA: 0x64605a8 VA: 0x7598a785a8
	private Void ForceUpdateInsetsInternal(UniWebViewEdgeInsets insets) { }
	// RVA: 0x64608c4 VA: 0x7598a788c4
	public String get_currentUrl() { }
	// RVA: 0x6460a74 VA: 0x7598a78a74
	public Boolean get_backButtonEnable() { }
	// RVA: 0x6460a7c VA: 0x7598a78a7c
	public Void set_backButtonEnable(Boolean value) { }
	// RVA: 0x6460c98 VA: 0x7598a78c98
	public Boolean get_bouncesEnable() { }
	// RVA: 0x6460ca0 VA: 0x7598a78ca0
	public Void set_bouncesEnable(Boolean value) { }
	// RVA: 0x6460ebc VA: 0x7598a78ebc
	public Boolean get_zoomEnable() { }
	// RVA: 0x6460ec4 VA: 0x7598a78ec4
	public Void set_zoomEnable(Boolean value) { }
	// RVA: 0x64610e0 VA: 0x7598a790e0
	public String get_userAgent() { }
	// RVA: 0x6461290 VA: 0x7598a79290
	public Single get_alpha() { }
	// RVA: 0x646142c VA: 0x7598a7942c
	public Void set_alpha(Single value) { }
	// RVA: 0x6461640 VA: 0x7598a79640
	public Boolean get_openLinksInExternalBrowser() { }
	// RVA: 0x64617dc VA: 0x7598a797dc
	public Void set_openLinksInExternalBrowser(Boolean value) { }
	// RVA: 0x64619d4 VA: 0x7598a799d4
	public Boolean get_immersiveMode() { }
	// RVA: 0x64619dc VA: 0x7598a799dc
	public Void set_immersiveMode(Boolean value) { }
	// RVA: 0x6461be0 VA: 0x7598a79be0
	public static Void SetUserAgent(String value) { }
	// RVA: 0x6461d40 VA: 0x7598a79d40
	public static Void ResetUserAgent() { }
	// RVA: 0x6461d48 VA: 0x7598a79d48
	public static Void SetDoneButtonText(String text) { }
	// RVA: 0x645dddc VA: 0x7598a75ddc
	public Void Load() { }
	// RVA: 0x645e5d8 VA: 0x7598a765d8
	public Void Load(String aUrl) { }
	// RVA: 0x645e2b4 VA: 0x7598a762b4
	public Void LoadHTMLString(String htmlString, String baseUrl) { }
	// RVA: 0x6462024 VA: 0x7598a7a024
	public Void Reload() { }
	// RVA: 0x64621a8 VA: 0x7598a7a1a8
	public Void Stop() { }
	// RVA: 0x645df60 VA: 0x7598a75f60
	public Void Show(Boolean fade, UniWebViewTransitionEdge direction, Single duration, Action finishAction) { }
	// RVA: 0x645ee70 VA: 0x7598a76e70
	public Void Hide(Boolean fade, UniWebViewTransitionEdge direction, Single duration, Action finishAction) { }
	// RVA: 0x645fe68 VA: 0x7598a77e68
	public Void EvaluatingJavaScript(String javaScript) { }
	// RVA: 0x645fd24 VA: 0x7598a77d24
	public Void AddJavaScript(String javaScript) { }
	// RVA: 0x6462b78 VA: 0x7598a7ab78
	public Void CleanCache() { }
	// RVA: 0x6462cfc VA: 0x7598a7acfc
	public Void CleanCookie(String key) { }
	// RVA: 0x6462ecc VA: 0x7598a7aecc
	public static Void SetCookie(String url, String cookie) { }
	// RVA: 0x6463080 VA: 0x7598a7b080
	public static String GetCookie(String url, String key) { }
	// RVA: 0x6463260 VA: 0x7598a7b260
	public Void SetTransparentBackground(Boolean transparent) { }
	// RVA: 0x6463458 VA: 0x7598a7b458
	public Void SetBackgroundColor(Color color) { }
	// RVA: 0x645e7a4 VA: 0x7598a767a4
	public Void ShowToolBar(Boolean animate) { }
	// RVA: 0x645ef24 VA: 0x7598a76f24
	public Void HideToolBar(Boolean animate) { }
	// RVA: 0x6463768 VA: 0x7598a7b768
	public Void SetShowSpinnerWhenLoading(Boolean show) { }
	// RVA: 0x6463960 VA: 0x7598a7b960
	public Void SetSpinnerLabelText(String text) { }
	// RVA: 0x6463b30 VA: 0x7598a7bb30
	public Void SetUseWideViewPort(Boolean use) { }
	// RVA: 0x6463d28 VA: 0x7598a7bd28
	public Void LoadWithOverviewMode(Boolean overview) { }
	// RVA: 0x6463f20 VA: 0x7598a7bf20
	public Boolean CanGoBack() { }
	// RVA: 0x64640bc VA: 0x7598a7c0bc
	public Boolean CanGoForward() { }
	// RVA: 0x6464258 VA: 0x7598a7c258
	public Void GoBack() { }
	// RVA: 0x64643dc VA: 0x7598a7c3dc
	public Void GoForward() { }
	// RVA: 0x6464560 VA: 0x7598a7c560
	public Void AddPermissionRequestTrustSite(String url) { }
	// RVA: 0x6464730 VA: 0x7598a7c730
	public Void AddCertTrustedHost(String host) { }
	// RVA: 0x6464900 VA: 0x7598a7c900
	public Void AddUrlScheme(String scheme) { }
	// RVA: 0x6464ad0 VA: 0x7598a7cad0
	public Void RemoveUrlScheme(String scheme) { }
	// RVA: 0x6464ca0 VA: 0x7598a7cca0
	public Void SetHeaderField(String key, String value) { }
	// RVA: 0x6464eb8 VA: 0x7598a7ceb8
	public Void SetVerticalScrollBarShow(Boolean show) { }
	// RVA: 0x64650b0 VA: 0x7598a7d0b0
	public Void SetHorizontalScrollBarShow(Boolean show) { }
	// RVA: 0x64652a8 VA: 0x7598a7d2a8
	public Void SetAllowAutoPlay(Boolean allowed) { }
	// RVA: 0x64654a0 VA: 0x7598a7d4a0
	public Void SetAllowInlinePlay(Boolean allowed) { }
	// RVA: 0x64654a4 VA: 0x7598a7d4a4
	public static Void SetWebContentsDebuggingEnabled(Boolean enabled) { }
	// RVA: 0x6465638 VA: 0x7598a7d638
	public static Void SetAllowThirdPartyCookies(Boolean allowed) { }
	// RVA: 0x64657cc VA: 0x7598a7d7cc
	private Boolean OrientationChanged() { }
	// RVA: 0x646232c VA: 0x7598a7a32c
	private Void ResizeInternal() { }
	// RVA: 0x6465800 VA: 0x7598a7d800
	private Void LoadComplete(String message) { }
	// RVA: 0x6465b44 VA: 0x7598a7db44
	private Void LoadBegin(String url) { }
	// RVA: 0x6465b6c VA: 0x7598a7db6c
	private Void ReceivedMessage(String rawMessage) { }
	// RVA: 0x6465f88 VA: 0x7598a7df88
	private Void WebViewDone(String message) { }
	// RVA: 0x6466028 VA: 0x7598a7e028
	private Void WebViewKeyDown(String message) { }
	// RVA: 0x64660bc VA: 0x7598a7e0bc
	private Void EvalJavaScriptFinished(String result) { }
	// RVA: 0x64660e4 VA: 0x7598a7e0e4
	private Void AnimationFinished(String identifier) { }
	// RVA: 0x64660e8 VA: 0x7598a7e0e8
	private Void ShowTransitionFinished(String message) { }
	// RVA: 0x6466124 VA: 0x7598a7e124
	private Void HideTransitionFinished(String message) { }
	// RVA: 0x6466160 VA: 0x7598a7e160
	private IEnumerator LoadFromJarPackage(String jarFilePath) { }
	// RVA: 0x6466218 VA: 0x7598a7e218
	private Void Awake() { }
	// RVA: 0x64665f4 VA: 0x7598a7e5f4
	private Void Start() { }
	// RVA: 0x6466604 VA: 0x7598a7e604
	private Void OnDestroy() { }
	// RVA: 0x64666e8 VA: 0x7598a7e6e8
	private Void RemoveAllListeners() { }
	// RVA: 0x646686c VA: 0x7598a7e86c
	private Void Update() { }
	// RVA: 0x64668a0 VA: 0x7598a7e8a0
	public Void .ctor() { }
}
```