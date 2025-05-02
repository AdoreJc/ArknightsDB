# WebHttpInstruction

**Namespace:** `Torappu.Network`


## Fields

- `WebHttpResult m_handler`

- `WebHttpResponse <result>k__BackingField`


## Properties

- `WebHttpResponse result`


## Methods

- `WebHttpResponse get_result()`

- `Void set_result(WebHttpResponse)`

- `Void Dispose()`

- `Void _OnHttpResponse(WebHttpResponse)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Network
public class WebHttpInstruction : CustomYieldInstruction, IDisposable
{
	private WebHttpResult m_handler; // 0x10
	private WebHttpResponse <result>k__BackingField; // 0x18

	public WebHttpResponse result { get; set; }
	public override Boolean keepWaiting { get; }

	// RVA: 0x67b4598 VA: 0x7598dcc598
	private Void .ctor() { }
	// RVA: 0x67af208 VA: 0x7598dc7208
	public static WebHttpInstruction Create(WebHttpResult handler) { }
	// RVA: 0x67b45a0 VA: 0x7598dcc5a0
	public WebHttpResponse get_result() { }
	// RVA: 0x67b45a8 VA: 0x7598dcc5a8
	private Void set_result(WebHttpResponse value) { }
	// RVA: 0x67b45b0 VA: 0x7598dcc5b0
	public override Boolean get_keepWaiting() { }
	// RVA: 0x67b45e4 VA: 0x7598dcc5e4
	public Void Dispose() { }
	// RVA: 0x67b4620 VA: 0x7598dcc620
	private Void _OnHttpResponse(WebHttpResponse response) { }
}
```