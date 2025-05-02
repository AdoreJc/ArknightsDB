# ConfigHandler

**Namespace:** ` `


## Fields

- `WebHttpResult <serviceHandler>k__BackingField`

- `ConfigStatus <status>k__BackingField`

- `FetchConfigResult <result>k__BackingField`


## Properties

- `WebHttpResult serviceHandler`

- `ConfigStatus status`

- `FetchConfigResult result`


## Methods

- `Void BindServiceHandler(WebHttpResult)`

- `WebHttpResult get_serviceHandler()`

- `Void set_serviceHandler(WebHttpResult)`

- `Void set_onSuc(Action`2)`

- `Void set_onError(Action`1)`

- `Void set_onClientOutOfDate(Action`1)`

- `ConfigStatus get_status()`

- `Void set_status(ConfigStatus)`

- `FetchConfigResult get_result()`

- `Void set_result(FetchConfigResult)`

- `Void InvokeSuc(Content, Config)`

- `Void InvokeError(String)`

- `Void InvokeClientOutOfDate(Content)`

- `Void Cancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ConfigHandler
{
	private WebHttpResult <serviceHandler>k__BackingField; // 0x10
	private Action`2 <onSuc>k__BackingField; // 0x18
	private Action`1 <onError>k__BackingField; // 0x20
	private Action`1 <onClientOutOfDate>k__BackingField; // 0x28
	private ConfigStatus <status>k__BackingField; // 0x30
	private FetchConfigResult <result>k__BackingField; // 0x38

	public WebHttpResult serviceHandler { get; set; }
	private Action`2 onSuc { get; set; }
	private Action`1 onError { get; set; }
	private Action`1 onClientOutOfDate { get; set; }
	public ConfigStatus status { get; set; }
	public FetchConfigResult result { get; set; }

	// RVA: 0x3586c20 VA: 0x7595b9ec20
	public Void BindServiceHandler(WebHttpResult serviceHandler) { }
	// RVA: 0x3587170 VA: 0x7595b9f170
	public WebHttpResult get_serviceHandler() { }
	// RVA: 0x3587178 VA: 0x7595b9f178
	private Void set_serviceHandler(WebHttpResult value) { }
	// RVA: 0x3587180 VA: 0x7595b9f180
	private Action`2 get_onSuc() { }
	// RVA: 0x3587188 VA: 0x7595b9f188
	public Void set_onSuc(Action`2 value) { }
	// RVA: 0x3587190 VA: 0x7595b9f190
	private Action`1 get_onError() { }
	// RVA: 0x3587198 VA: 0x7595b9f198
	public Void set_onError(Action`1 value) { }
	// RVA: 0x35871a0 VA: 0x7595b9f1a0
	private Action`1 get_onClientOutOfDate() { }
	// RVA: 0x35871a8 VA: 0x7595b9f1a8
	public Void set_onClientOutOfDate(Action`1 value) { }
	// RVA: 0x35871b0 VA: 0x7595b9f1b0
	public ConfigStatus get_status() { }
	// RVA: 0x35871b8 VA: 0x7595b9f1b8
	private Void set_status(ConfigStatus value) { }
	// RVA: 0x35871c0 VA: 0x7595b9f1c0
	public FetchConfigResult get_result() { }
	// RVA: 0x35871d4 VA: 0x7595b9f1d4
	private Void set_result(FetchConfigResult value) { }
	// RVA: 0x35871f4 VA: 0x7595b9f1f4
	public Void InvokeSuc(Content content, Config config) { }
	// RVA: 0x35872b0 VA: 0x7595b9f2b0
	public Void InvokeError(String error) { }
	// RVA: 0x3587350 VA: 0x7595b9f350
	public Void InvokeClientOutOfDate(Content content) { }
	// RVA: 0x35873ec VA: 0x7595b9f3ec
	public Void Cancel() { }
	// RVA: 0x3586a60 VA: 0x7595b9ea60
	public Void .ctor() { }
}
```