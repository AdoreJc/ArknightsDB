# UIUniWebView

**Namespace:** `Torappu.UI`


## Fields

- `Single _alpha`

- `GameObject _failedTarget`

- `Boolean openLinksInExternal`

- `Camera targetCamera`

- `RectTransform _rectTransform`

- `UniWebView _uniWebView`


## Properties

- `UniWebView WebView`


## Methods

- `UniWebView get_WebView()`

- `Void EnsureWidget()`

- `Void InitIfNot()`

- `Boolean OpenUrl(String, Boolean, Single)`

- `Void Close(Boolean, Single)`

- `UniWebViewEdgeInsets CalculateInsets()`

- `Void OnSafeRectUpdated(SafeRect)`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void Start()`

- `Void OnDestroy()`

- `UniWebView _CreateUniWebView()`

- `Void _MarkWebViewDestroy()`

- `Void OnLoadComplete(UniWebView, Boolean, String)`

- `Void LateUpdate()`

- `Void _EventOnReceivedKeyCode(UniWebView, Int32)`

- `Void _OnReceiveKeyCode(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIUniWebView : MonoBehaviour, IHotfixable, ISafeAreaListener
{
	private const Int32 BACK_PRESS_KEYCODE; // 0x0
	private Single _alpha; // 0x18
	private GameObject _failedTarget; // 0x20
	private Boolean openLinksInExternal; // 0x28
	public Camera targetCamera; // 0x30
	private RectTransform _rectTransform; // 0x38
	private UniWebView _uniWebView; // 0x40
	private static DelegateBridge __Hotfix0_get_WebView; // 0x0
	private static DelegateBridge __Hotfix0_EnsureWidget; // 0x8
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OpenUrl; // 0x18
	private static DelegateBridge __Hotfix0_Close; // 0x20
	private static DelegateBridge __Hotfix0_CalculateInsets; // 0x28
	private static DelegateBridge __Hotfix0_OnSafeRectUpdated; // 0x30
	private static DelegateBridge __Hotfix0_OnEnable; // 0x38
	private static DelegateBridge __Hotfix0_OnDisable; // 0x40
	private static DelegateBridge __Hotfix0_Start; // 0x48
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x50
	private static DelegateBridge __Hotfix0__CreateUniWebView; // 0x58
	private static DelegateBridge __Hotfix0__MarkWebViewDestroy; // 0x60
	private static DelegateBridge __Hotfix0_OnLoadComplete; // 0x68
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x70
	private static DelegateBridge __Hotfix0__EventOnReceivedKeyCode; // 0x78
	private static DelegateBridge __Hotfix0__OnReceiveKeyCode; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public UniWebView WebView { get; }

	// RVA: 0x22028a0 VA: 0x759481a8a0
	public UniWebView get_WebView() { }
	// RVA: 0x2202908 VA: 0x759481a908
	private Void EnsureWidget() { }
	// RVA: 0x22029e4 VA: 0x759481a9e4
	public Void InitIfNot() { }
	// RVA: 0x2203290 VA: 0x759481b290
	public Boolean OpenUrl(String url, Boolean fade, Single duration) { }
	// RVA: 0x22033c4 VA: 0x759481b3c4
	public Void Close(Boolean fade, Single duration) { }
	// RVA: 0x2202eb4 VA: 0x759481aeb4
	public UniWebViewEdgeInsets CalculateInsets() { }
	// RVA: 0x22034c0 VA: 0x759481b4c0
	public Void OnSafeRectUpdated(SafeRect safeRect) { }
	// RVA: 0x22035ac VA: 0x759481b5ac
	private Void OnEnable() { }
	// RVA: 0x220367c VA: 0x759481b67c
	private Void OnDisable() { }
	// RVA: 0x220374c VA: 0x759481b74c
	private Void Start() { }
	// RVA: 0x22037dc VA: 0x759481b7dc
	private Void OnDestroy() { }
	// RVA: 0x2202c70 VA: 0x759481ac70
	private UniWebView _CreateUniWebView() { }
	// RVA: 0x2203874 VA: 0x759481b874
	private Void _MarkWebViewDestroy() { }
	// RVA: 0x2203b48 VA: 0x759481bb48
	private Void OnLoadComplete(UniWebView webView, Boolean success, String errorMessage) { }
	// RVA: 0x2203c54 VA: 0x759481bc54
	private Void LateUpdate() { }
	// RVA: 0x2203d1c VA: 0x759481bd1c
	private Void _EventOnReceivedKeyCode(UniWebView webView, Int32 keyCode) { }
	// RVA: 0x2203da4 VA: 0x759481bda4
	private Void _OnReceiveKeyCode(Int32 keyCode) { }
	// RVA: 0x2203e5c VA: 0x759481be5c
	public Void .ctor() { }
}
```