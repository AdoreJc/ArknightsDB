# SDKPopupWebView

**Namespace:** `HGSDK.UI`


## Fields

- `UIUniWebView _webView`

- `Single _fadeTime`

- `Tween m_tween`

- `Action m_onClosed`

- `CanvasGroup m_canvasGroup`


## Properties

- `CanvasGroup canvasGroup`

- `Boolean isFade`


## Methods

- `CanvasGroup get_canvasGroup()`

- `Boolean get_isFade()`

- `Void SetCamera(Camera)`

- `Void Start()`

- `Void OpenUrl(String, Action)`

- `Void CloseMe()`

- `Void _ClearAll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKPopupWebView : MonoBehaviour
{
	private UIUniWebView _webView; // 0x18
	private Single _fadeTime; // 0x20
	private Tween m_tween; // 0x28
	private Action m_onClosed; // 0x30
	private CanvasGroup m_canvasGroup; // 0x38

	protected CanvasGroup canvasGroup { get; }
	private Boolean isFade { get; }

	// RVA: 0x37526d8 VA: 0x7595d6a6d8
	protected CanvasGroup get_canvasGroup() { }
	// RVA: 0x3752780 VA: 0x7595d6a780
	private Boolean get_isFade() { }
	// RVA: 0x37527e8 VA: 0x7595d6a7e8
	public Void SetCamera(Camera camera) { }
	// RVA: 0x3752804 VA: 0x7595d6a804
	private Void Start() { }
	// RVA: 0x37528c8 VA: 0x7595d6a8c8
	public Void OpenUrl(String url, Action onClosed) { }
	// RVA: 0x37529c8 VA: 0x7595d6a9c8
	public Void CloseMe() { }
	// RVA: 0x375297c VA: 0x7595d6a97c
	private Void _ClearAll() { }
	// RVA: 0x3752b38 VA: 0x7595d6ab38
	public Void .ctor() { }
}
```