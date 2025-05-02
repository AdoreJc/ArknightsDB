# EventSource

**Namespace:** `BestHTTP.ServerSentEvents`


## Fields

- `Uri <Uri>k__BackingField`

- `States _state`

- `TimeSpan <ReconnectionTime>k__BackingField`

- `String <LastEventId>k__BackingField`

- `HTTPRequest <InternalRequest>k__BackingField`

- `OnGeneralEventDelegate OnOpen`

- `OnMessageDelegate OnMessage`

- `OnErrorDelegate OnError`

- `OnRetryDelegate OnRetry`

- `OnGeneralEventDelegate OnClosed`

- `OnStateChangedDelegate OnStateChanged`

- `Byte RetryCount`

- `DateTime RetryCalled`


## Properties

- `Uri Uri`

- `States State`

- `TimeSpan ReconnectionTime`

- `String LastEventId`

- `HTTPRequest InternalRequest`


## Methods

- `Uri get_Uri()`

- `Void set_Uri(Uri)`

- `States get_State()`

- `Void set_State(States)`

- `TimeSpan get_ReconnectionTime()`

- `Void set_ReconnectionTime(TimeSpan)`

- `String get_LastEventId()`

- `Void set_LastEventId(String)`

- `HTTPRequest get_InternalRequest()`

- `Void set_InternalRequest(HTTPRequest)`

- `Void add_OnOpen(OnGeneralEventDelegate)`

- `Void remove_OnOpen(OnGeneralEventDelegate)`

- `Void add_OnMessage(OnMessageDelegate)`

- `Void remove_OnMessage(OnMessageDelegate)`

- `Void add_OnError(OnErrorDelegate)`

- `Void remove_OnError(OnErrorDelegate)`

- `Void add_OnRetry(OnRetryDelegate)`

- `Void remove_OnRetry(OnRetryDelegate)`

- `Void add_OnClosed(OnGeneralEventDelegate)`

- `Void remove_OnClosed(OnGeneralEventDelegate)`

- `Void add_OnStateChanged(OnStateChangedDelegate)`

- `Void remove_OnStateChanged(OnStateChangedDelegate)`

- `Void Open()`

- `Void Close()`

- `Void On(String, OnEventDelegate)`

- `Void Off(String)`

- `Void CallOnError(String, String)`

- `Boolean CallOnRetry()`

- `Void SetClosed(String)`

- `Void Retry()`

- `Void OnUpgraded(HTTPRequest, HTTPResponse)`

- `Void OnRequestFinished(HTTPRequest, HTTPResponse)`

- `Void OnMessageReceived(EventSourceResponse, Message)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.ServerSentEvents
public class EventSource : IHeartbeat
{
	private Uri <Uri>k__BackingField; // 0x10
	private States _state; // 0x18
	private TimeSpan <ReconnectionTime>k__BackingField; // 0x20
	private String <LastEventId>k__BackingField; // 0x28
	private HTTPRequest <InternalRequest>k__BackingField; // 0x30
	private OnGeneralEventDelegate OnOpen; // 0x38
	private OnMessageDelegate OnMessage; // 0x40
	private OnErrorDelegate OnError; // 0x48
	private OnRetryDelegate OnRetry; // 0x50
	private OnGeneralEventDelegate OnClosed; // 0x58
	private OnStateChangedDelegate OnStateChanged; // 0x60
	private Dictionary`2 EventTable; // 0x68
	private Byte RetryCount; // 0x70
	private DateTime RetryCalled; // 0x78

	public Uri Uri { get; set; }
	public States State { get; set; }
	public TimeSpan ReconnectionTime { get; set; }
	public String LastEventId { get; set; }
	public HTTPRequest InternalRequest { get; set; }

	// RVA: 0x6613e40 VA: 0x7598c2be40
	public Uri get_Uri() { }
	// RVA: 0x6613e48 VA: 0x7598c2be48
	private Void set_Uri(Uri value) { }
	// RVA: 0x6613e50 VA: 0x7598c2be50
	public States get_State() { }
	// RVA: 0x6613e58 VA: 0x7598c2be58
	private Void set_State(States value) { }
	// RVA: 0x6613fe0 VA: 0x7598c2bfe0
	public TimeSpan get_ReconnectionTime() { }
	// RVA: 0x6613fe8 VA: 0x7598c2bfe8
	public Void set_ReconnectionTime(TimeSpan value) { }
	// RVA: 0x6613ff0 VA: 0x7598c2bff0
	public String get_LastEventId() { }
	// RVA: 0x6613ff8 VA: 0x7598c2bff8
	private Void set_LastEventId(String value) { }
	// RVA: 0x6614000 VA: 0x7598c2c000
	public HTTPRequest get_InternalRequest() { }
	// RVA: 0x6614008 VA: 0x7598c2c008
	private Void set_InternalRequest(HTTPRequest value) { }
	// RVA: 0x6614010 VA: 0x7598c2c010
	public Void add_OnOpen(OnGeneralEventDelegate value) { }
	// RVA: 0x66140ac VA: 0x7598c2c0ac
	public Void remove_OnOpen(OnGeneralEventDelegate value) { }
	// RVA: 0x6614148 VA: 0x7598c2c148
	public Void add_OnMessage(OnMessageDelegate value) { }
	// RVA: 0x66141e4 VA: 0x7598c2c1e4
	public Void remove_OnMessage(OnMessageDelegate value) { }
	// RVA: 0x6614280 VA: 0x7598c2c280
	public Void add_OnError(OnErrorDelegate value) { }
	// RVA: 0x661431c VA: 0x7598c2c31c
	public Void remove_OnError(OnErrorDelegate value) { }
	// RVA: 0x66143b8 VA: 0x7598c2c3b8
	public Void add_OnRetry(OnRetryDelegate value) { }
	// RVA: 0x6614454 VA: 0x7598c2c454
	public Void remove_OnRetry(OnRetryDelegate value) { }
	// RVA: 0x66144f0 VA: 0x7598c2c4f0
	public Void add_OnClosed(OnGeneralEventDelegate value) { }
	// RVA: 0x661458c VA: 0x7598c2c58c
	public Void remove_OnClosed(OnGeneralEventDelegate value) { }
	// RVA: 0x6614628 VA: 0x7598c2c628
	public Void add_OnStateChanged(OnStateChangedDelegate value) { }
	// RVA: 0x66146c4 VA: 0x7598c2c6c4
	public Void remove_OnStateChanged(OnStateChangedDelegate value) { }
	// RVA: 0x6614760 VA: 0x7598c2c760
	public Void .ctor(Uri uri) { }
	// RVA: 0x66149b4 VA: 0x7598c2c9b4
	public Void Open() { }
	// RVA: 0x6614a64 VA: 0x7598c2ca64
	public Void Close() { }
	// RVA: 0x6614ab0 VA: 0x7598c2cab0
	public Void On(String eventName, OnEventDelegate action) { }
	// RVA: 0x6614b70 VA: 0x7598c2cb70
	public Void Off(String eventName) { }
	// RVA: 0x6614bd4 VA: 0x7598c2cbd4
	private Void CallOnError(String error, String msg) { }
	// RVA: 0x6614d68 VA: 0x7598c2cd68
	private Boolean CallOnRetry() { }
	// RVA: 0x6614ee0 VA: 0x7598c2cee0
	private Void SetClosed(String msg) { }
	// RVA: 0x6615078 VA: 0x7598c2d078
	private Void Retry() { }
	// RVA: 0x6615164 VA: 0x7598c2d164
	private Void OnUpgraded(HTTPRequest originalRequest, HTTPResponse response) { }
	// RVA: 0x66154c0 VA: 0x7598c2d4c0
	private Void OnRequestFinished(HTTPRequest req, HTTPResponse resp) { }
	// RVA: 0x6615800 VA: 0x7598c2d800
	private Void OnMessageReceived(EventSourceResponse resp, Message message) { }
	// RVA: 0x6615bb8 VA: 0x7598c2dbb8
	private Void BestHTTP.Extensions.IHeartbeat.OnHeartbeatUpdate(TimeSpan dif) { }
}
```