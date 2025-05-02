# ServicePointScheduler

**Namespace:** `System.Net`


## Fields

- `ServicePoint <ServicePoint>k__BackingField`

- `Int32 running`

- `Int32 maxIdleTime`

- `AsyncManualResetEvent schedulerEvent`

- `ConnectionGroup defaultGroup`

- `Int32 currentConnections`

- `Int32 connectionLimit`

- `DateTime idleSince`


## Properties

- `ServicePoint ServicePoint`

- `Int32 MaxIdleTime`


## Methods

- `ServicePoint get_ServicePoint()`

- `Void set_ServicePoint(ServicePoint)`

- `Int32 get_MaxIdleTime()`

- `Void Run()`

- `Task RunScheduler()`

- `Void Cleanup()`

- `Void RunSchedulerIteration()`

- `Boolean OperationCompleted(ConnectionGroup, WebOperation)`

- `Void CloseIdleConnection(ConnectionGroup, WebConnection)`

- `Boolean SchedulerIteration(ConnectionGroup)`

- `Void RemoveOperation(WebOperation)`

- `Void RemoveIdleConnection(WebConnection)`

- `Void FinalCleanup()`

- `Void SendRequest(WebOperation, String)`

- `ConnectionGroup GetConnectionGroup(String)`

- `Void OnConnectionCreated(WebConnection)`

- `Void OnConnectionClosed(WebConnection)`

- `Task <Run>b__31_0()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class ServicePointScheduler
{
	private ServicePoint <ServicePoint>k__BackingField; // 0x10
	private Int32 running; // 0x18
	private Int32 maxIdleTime; // 0x1c
	private AsyncManualResetEvent schedulerEvent; // 0x20
	private ConnectionGroup defaultGroup; // 0x28
	private Dictionary`2 groups; // 0x30
	private LinkedList`1 operations; // 0x38
	private LinkedList`1 idleConnections; // 0x40
	private Int32 currentConnections; // 0x48
	private Int32 connectionLimit; // 0x4c
	private DateTime idleSince; // 0x50
	private static Int32 nextId; // 0x0
	public readonly Int32 ID; // 0x58

	private ServicePoint ServicePoint { get; set; }
	public Int32 MaxIdleTime { get; }

	// RVA: 0x6331e5c VA: 0x7598949e5c
	private ServicePoint get_ServicePoint() { }
	// RVA: 0x6331e64 VA: 0x7598949e64
	private Void set_ServicePoint(ServicePoint value) { }
	// RVA: 0x6331e6c VA: 0x7598949e6c
	public Int32 get_MaxIdleTime() { }
	// RVA: 0x6330a2c VA: 0x7598948a2c
	public Void .ctor(ServicePoint servicePoint, Int32 connectionLimit, Int32 maxIdleTime) { }
	// RVA: 0x6332064 VA: 0x759894a064
	public Void Run() { }
	// RVA: 0x6332364 VA: 0x759894a364
	private Task RunScheduler() { }
	// RVA: 0x6332454 VA: 0x759894a454
	private Void Cleanup() { }
	// RVA: 0x63326a8 VA: 0x759894a6a8
	private Void RunSchedulerIteration() { }
	// RVA: 0x63329d8 VA: 0x759894a9d8
	private Boolean OperationCompleted(ConnectionGroup group, WebOperation operation) { }
	// RVA: 0x6333160 VA: 0x759894b160
	private Void CloseIdleConnection(ConnectionGroup group, WebConnection connection) { }
	// RVA: 0x63328f8 VA: 0x759894a8f8
	private Boolean SchedulerIteration(ConnectionGroup group) { }
	// RVA: 0x6333288 VA: 0x759894b288
	private Void RemoveOperation(WebOperation operation) { }
	// RVA: 0x6332df8 VA: 0x759894adf8
	private Void RemoveIdleConnection(WebConnection connection) { }
	// RVA: 0x6333354 VA: 0x759894b354
	private Void FinalCleanup() { }
	// RVA: 0x6331474 VA: 0x7598949474
	public Void SendRequest(WebOperation operation, String groupName) { }
	// RVA: 0x633341c VA: 0x759894b41c
	private ConnectionGroup GetConnectionGroup(String name) { }
	// RVA: 0x633368c VA: 0x759894b68c
	private Void OnConnectionCreated(WebConnection connection) { }
	// RVA: 0x6333698 VA: 0x759894b698
	private Void OnConnectionClosed(WebConnection connection) { }
	// RVA: 0x63336b4 VA: 0x759894b6b4
	public static Task`1 WaitAsync(Task workerTask, Int32 millisecondTimeout) { }
	// RVA: 0x63337dc VA: 0x759894b7dc
	private Task <Run>b__31_0() { }
}
```