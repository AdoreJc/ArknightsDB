# Hub

**Namespace:** `BestHTTP.SignalR.Hubs`


## Fields

- `String <Name>k__BackingField`

- `OnMethodCallDelegate OnMethodCall`

- `StringBuilder builder`


## Properties

- `String Name`


## Methods

- `String get_Name()`

- `Void set_Name(String)`

- `Void add_OnMethodCall(OnMethodCallDelegate)`

- `Void remove_OnMethodCall(OnMethodCallDelegate)`

- `Void On(String, OnMethodCallCallbackDelegate)`

- `Void Off(String)`

- `Boolean Call(String, Object[])`

- `Boolean Call(String, OnMethodResultDelegate, Object[])`

- `Boolean Call(String, OnMethodResultDelegate, OnMethodFailedDelegate, Object[])`

- `Boolean Call(String, OnMethodResultDelegate, OnMethodProgressDelegate, Object[])`

- `Boolean Call(String, OnMethodResultDelegate, OnMethodFailedDelegate, OnMethodProgressDelegate, Object[])`

- `Void MergeState(IDictionary`2)`

- `String BuildMessage(ClientMessage)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.SignalR.Hubs
public class Hub : IHub
{
	private String <Name>k__BackingField; // 0x10
	private Dictionary`2 state; // 0x18
	private OnMethodCallDelegate OnMethodCall; // 0x20
	private Dictionary`2 SentMessages; // 0x28
	private Dictionary`2 MethodTable; // 0x30
	private StringBuilder builder; // 0x38
	private Connection <BestHTTP.SignalR.Hubs.IHub.Connection>k__BackingField; // 0x40

	public String Name { get; set; }
	public Dictionary`2 State { get; }
	private Connection BestHTTP.SignalR.Hubs.IHub.Connection { get; set; }

	// RVA: 0x665c954 VA: 0x7598c74954
	public String get_Name() { }
	// RVA: 0x665c95c VA: 0x7598c7495c
	private Void set_Name(String value) { }
	// RVA: 0x665c964 VA: 0x7598c74964
	public Dictionary`2 get_State() { }
	// RVA: 0x665c9f0 VA: 0x7598c749f0
	public Void add_OnMethodCall(OnMethodCallDelegate value) { }
	// RVA: 0x665ca8c VA: 0x7598c74a8c
	public Void remove_OnMethodCall(OnMethodCallDelegate value) { }
	// RVA: 0x665cb28 VA: 0x7598c74b28
	private Connection BestHTTP.SignalR.Hubs.IHub.get_Connection() { }
	// RVA: 0x665cb30 VA: 0x7598c74b30
	private Void BestHTTP.SignalR.Hubs.IHub.set_Connection(Connection value) { }
	// RVA: 0x665cb38 VA: 0x7598c74b38
	public Void .ctor(String name) { }
	// RVA: 0x664e7f4 VA: 0x7598c667f4
	public Void .ctor(String name, Connection manager) { }
	// RVA: 0x665cb40 VA: 0x7598c74b40
	public Void On(String method, OnMethodCallCallbackDelegate callback) { }
	// RVA: 0x665cba8 VA: 0x7598c74ba8
	public Void Off(String method) { }
	// RVA: 0x665cc04 VA: 0x7598c74c04
	public Boolean Call(String method, Object[] args) { }
	// RVA: 0x665cf4c VA: 0x7598c74f4c
	public Boolean Call(String method, OnMethodResultDelegate onResult, Object[] args) { }
	// RVA: 0x665cf5c VA: 0x7598c74f5c
	public Boolean Call(String method, OnMethodResultDelegate onResult, OnMethodFailedDelegate onResultError, Object[] args) { }
	// RVA: 0x665cf68 VA: 0x7598c74f68
	public Boolean Call(String method, OnMethodResultDelegate onResult, OnMethodProgressDelegate onProgress, Object[] args) { }
	// RVA: 0x665cc18 VA: 0x7598c74c18
	public Boolean Call(String method, OnMethodResultDelegate onResult, OnMethodFailedDelegate onResultError, OnMethodProgressDelegate onProgress, Object[] args) { }
	// RVA: 0x665cf78 VA: 0x7598c74f78
	private Boolean BestHTTP.SignalR.Hubs.IHub.Call(ClientMessage msg) { }
	// RVA: 0x665d8c4 VA: 0x7598c758c4
	private Boolean BestHTTP.SignalR.Hubs.IHub.HasSentMessageId(UInt64 id) { }
	// RVA: 0x665d91c VA: 0x7598c7591c
	private Void BestHTTP.SignalR.Hubs.IHub.Close() { }
	// RVA: 0x665d96c VA: 0x7598c7596c
	private Void BestHTTP.SignalR.Hubs.IHub.OnMethod(MethodCallMessage msg) { }
	// RVA: 0x665e1ac VA: 0x7598c761ac
	private Void BestHTTP.SignalR.Hubs.IHub.OnMessage(IServerMessage msg) { }
	// RVA: 0x665de08 VA: 0x7598c75e08
	private Void MergeState(IDictionary`2 state) { }
	// RVA: 0x665d1ec VA: 0x7598c751ec
	private String BuildMessage(ClientMessage msg) { }
}
```