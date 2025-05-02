# CallbackFromWebSceneManager

**Namespace:** ` `


## Fields

- `Text result`

- `UniWebView _webView`

- `String _fileName`


## Methods

- `Void LoadFromFile()`

- `Void OnReceivedMessage(UniWebView, UniWebViewMessage)`

- `UniWebView CreateWebView()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class CallbackFromWebSceneManager : MonoBehaviour
{
	public Text result; // 0x18
	private UniWebView _webView; // 0x20
	private String _fileName; // 0x28


	// RVA: 0x645ef28 VA: 0x7598a76f28
	public Void LoadFromFile() { }
	// RVA: 0x645f394 VA: 0x7598a77394
	private Void OnReceivedMessage(UniWebView webView, UniWebViewMessage message) { }
	// RVA: 0x645f0c4 VA: 0x7598a770c4
	private UniWebView CreateWebView() { }
	// RVA: 0x645f74c VA: 0x7598a7774c
	public Void .ctor() { }
}
```