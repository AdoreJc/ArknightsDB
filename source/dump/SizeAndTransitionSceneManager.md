# SizeAndTransitionSceneManager

**Namespace:** ` `


## Fields

- `UniWebView _webView`

- `Boolean _webViewReady`

- `Boolean <fade>k__BackingField`

- `Int32 <transitionEdge>k__BackingField`

- `InputField top`

- `InputField left`

- `InputField bottom`

- `InputField right`

- `InputField x`

- `InputField y`

- `InputField width`

- `InputField height`


## Properties

- `Boolean fade`

- `Int32 transitionEdge`


## Methods

- `Boolean get_fade()`

- `Void set_fade(Boolean)`

- `Int32 get_transitionEdge()`

- `Void set_transitionEdge(Int32)`

- `Void Start()`

- `Void ShowClicked()`

- `Void SetInsetsClicked()`

- `UniWebView CreateWebView()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class SizeAndTransitionSceneManager : MonoBehaviour
{
	private UniWebView _webView; // 0x18
	private Boolean _webViewReady; // 0x20
	private Boolean <fade>k__BackingField; // 0x21
	private Int32 <transitionEdge>k__BackingField; // 0x24
	public InputField top; // 0x28
	public InputField left; // 0x30
	public InputField bottom; // 0x38
	public InputField right; // 0x40
	public InputField x; // 0x48
	public InputField y; // 0x50
	public InputField width; // 0x58
	public InputField height; // 0x60

	public Boolean fade { get; set; }
	public Int32 transitionEdge { get; set; }

	// RVA: 0x645e34c VA: 0x7598a7634c
	public Boolean get_fade() { }
	// RVA: 0x645e354 VA: 0x7598a76354
	public Void set_fade(Boolean value) { }
	// RVA: 0x645e360 VA: 0x7598a76360
	public Int32 get_transitionEdge() { }
	// RVA: 0x645e368 VA: 0x7598a76368
	public Void set_transitionEdge(Int32 value) { }
	// RVA: 0x645e370 VA: 0x7598a76370
	private Void Start() { }
	// RVA: 0x645e5f4 VA: 0x7598a765f4
	public Void ShowClicked() { }
	// RVA: 0x645e7a8 VA: 0x7598a767a8
	public Void SetInsetsClicked() { }
	// RVA: 0x645e3e8 VA: 0x7598a763e8
	private UniWebView CreateWebView() { }
	// RVA: 0x645eb38 VA: 0x7598a76b38
	public Void .ctor() { }
}
```