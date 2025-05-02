# DemoHub

**Namespace:** ` `


## Fields

- `Single longRunningJobProgress`

- `String longRunningJobStatus`

- `String fromArbitraryCodeResult`

- `String groupAddedResult`

- `String dynamicTaskResult`

- `String genericTaskResult`

- `String taskWithExceptionResult`

- `String genericTaskWithExceptionResult`

- `String synchronousExceptionResult`

- `String invokingHubMethodWithDynamicResult`

- `String simpleArrayResult`

- `String complexTypeResult`

- `String complexArrayResult`

- `String voidOverloadResult`

- `String intOverloadResult`

- `String readStateResult`

- `String plainTaskResult`

- `String genericTaskWithContinueWithResult`

- `GUIMessageList invokeResults`


## Methods

- `Void ReportProgress(String)`

- `Void OnLongRunningJob_Progress(Hub, ClientMessage, ProgressMessage)`

- `Void OnLongRunningJob_Done(Hub, ClientMessage, ResultMessage)`

- `Void MultipleCalls()`

- `Void DynamicTask()`

- `Void OnDynamicTask_Failed(Hub, ClientMessage, FailureMessage)`

- `Void OnDynamicTask_Done(Hub, ClientMessage, ResultMessage)`

- `Void AddToGroups()`

- `Void GetValue()`

- `Void TaskWithException()`

- `Void GenericTaskWithException()`

- `Void SynchronousException()`

- `Void PassingDynamicComplex(Object)`

- `Void SimpleArray(Int32[])`

- `Void ComplexType(Object)`

- `Void ComplexArray(Object[])`

- `Void Overload()`

- `Void OnVoidOverload_Done(Hub, ClientMessage, ResultMessage)`

- `Void Overload(Int32)`

- `Void OnIntOverload_Done(Hub, ClientMessage, ResultMessage)`

- `Void ReadStateValue()`

- `Void PlainTask()`

- `Void GenericTaskWithContinueWith()`

- `Void FromArbitraryCode(Hub, MethodCallMessage)`

- `Void GroupAdded(Hub, MethodCallMessage)`

- `Void Signal(Hub, MethodCallMessage)`

- `Void Invoke(Hub, MethodCallMessage)`

- `Void Draw()`

- `Void <GetValue>b__28_0(Hub, ClientMessage, ResultMessage)`

- `Void <TaskWithException>b__29_0(Hub, ClientMessage, FailureMessage)`

- `Void <GenericTaskWithException>b__30_0(Hub, ClientMessage, FailureMessage)`

- `Void <SynchronousException>b__31_0(Hub, ClientMessage, FailureMessage)`

- `Void <PassingDynamicComplex>b__32_0(Hub, ClientMessage, ResultMessage)`

- `Void <SimpleArray>b__33_0(Hub, ClientMessage, ResultMessage)`

- `Void <ComplexType>b__34_0(Hub, ClientMessage, ResultMessage)`

- `Void <ComplexArray>b__35_0(Hub, ClientMessage, ResultMessage)`

- `Void <ReadStateValue>b__40_0(Hub, ClientMessage, ResultMessage)`

- `Void <PlainTask>b__41_0(Hub, ClientMessage, ResultMessage)`

- `Void <GenericTaskWithContinueWith>b__42_0(Hub, ClientMessage, ResultMessage)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
internal class DemoHub : Hub
{
	private Single longRunningJobProgress; // 0x48
	private String longRunningJobStatus; // 0x50
	private String fromArbitraryCodeResult; // 0x58
	private String groupAddedResult; // 0x60
	private String dynamicTaskResult; // 0x68
	private String genericTaskResult; // 0x70
	private String taskWithExceptionResult; // 0x78
	private String genericTaskWithExceptionResult; // 0x80
	private String synchronousExceptionResult; // 0x88
	private String invokingHubMethodWithDynamicResult; // 0x90
	private String simpleArrayResult; // 0x98
	private String complexTypeResult; // 0xa0
	private String complexArrayResult; // 0xa8
	private String voidOverloadResult; // 0xb0
	private String intOverloadResult; // 0xb8
	private String readStateResult; // 0xc0
	private String plainTaskResult; // 0xc8
	private String genericTaskWithContinueWithResult; // 0xd0
	private GUIMessageList invokeResults; // 0xd8


	// RVA: 0x644e004 VA: 0x7598a66004
	public Void .ctor() { }
	// RVA: 0x644f4c4 VA: 0x7598a674c4
	public Void ReportProgress(String arg) { }
	// RVA: 0x64514e0 VA: 0x7598a694e0
	public Void OnLongRunningJob_Progress(Hub hub, ClientMessage originialMessage, ProgressMessage progress) { }
	// RVA: 0x6451570 VA: 0x7598a69570
	public Void OnLongRunningJob_Done(Hub hub, ClientMessage originalMessage, ResultMessage result) { }
	// RVA: 0x64515b0 VA: 0x7598a695b0
	public Void MultipleCalls() { }
	// RVA: 0x644ef30 VA: 0x7598a66f30
	public Void DynamicTask() { }
	// RVA: 0x6451650 VA: 0x7598a69650
	private Void OnDynamicTask_Failed(Hub hub, ClientMessage originalMessage, FailureMessage result) { }
	// RVA: 0x64516b8 VA: 0x7598a696b8
	private Void OnDynamicTask_Done(Hub hub, ClientMessage originalMessage, ResultMessage result) { }
	// RVA: 0x644eac4 VA: 0x7598a66ac4
	public Void AddToGroups() { }
	// RVA: 0x644eb64 VA: 0x7598a66b64
	public Void GetValue() { }
	// RVA: 0x644ec54 VA: 0x7598a66c54
	public Void TaskWithException() { }
	// RVA: 0x644ed48 VA: 0x7598a66d48
	public Void GenericTaskWithException() { }
	// RVA: 0x644ee3c VA: 0x7598a66e3c
	public Void SynchronousException() { }
	// RVA: 0x644f074 VA: 0x7598a67074
	public Void PassingDynamicComplex(Object person) { }
	// RVA: 0x644f188 VA: 0x7598a67188
	public Void SimpleArray(Int32[] array) { }
	// RVA: 0x644f29c VA: 0x7598a6729c
	public Void ComplexType(Object person) { }
	// RVA: 0x644f3b0 VA: 0x7598a673b0
	public Void ComplexArray(Object[] complexArray) { }
	// RVA: 0x644f630 VA: 0x7598a67630
	public Void Overload() { }
	// RVA: 0x6451720 VA: 0x7598a69720
	private Void OnVoidOverload_Done(Hub hub, ClientMessage originalMessage, ResultMessage result) { }
	// RVA: 0x6451778 VA: 0x7598a69778
	public Void Overload(Int32 number) { }
	// RVA: 0x64518c0 VA: 0x7598a698c0
	private Void OnIntOverload_Done(Hub hub, ClientMessage originalMessage, ResultMessage result) { }
	// RVA: 0x644f720 VA: 0x7598a67720
	public Void ReadStateValue() { }
	// RVA: 0x644f810 VA: 0x7598a67810
	public Void PlainTask() { }
	// RVA: 0x644f900 VA: 0x7598a67900
	public Void GenericTaskWithContinueWith() { }
	// RVA: 0x6451940 VA: 0x7598a69940
	private Void FromArbitraryCode(Hub hub, MethodCallMessage methodCall) { }
	// RVA: 0x64519d8 VA: 0x7598a699d8
	private Void GroupAdded(Hub hub, MethodCallMessage methodCall) { }
	// RVA: 0x6451a54 VA: 0x7598a69a54
	private Void Signal(Hub hub, MethodCallMessage methodCall) { }
	// RVA: 0x6451ad0 VA: 0x7598a69ad0
	private Void Invoke(Hub hub, MethodCallMessage methodCall) { }
	// RVA: 0x644fdd4 VA: 0x7598a67dd4
	public Void Draw() { }
	// RVA: 0x6451ba4 VA: 0x7598a69ba4
	private Void <GetValue>b__28_0(Hub hub, ClientMessage msg, ResultMessage result) { }
	// RVA: 0x6451c0c VA: 0x7598a69c0c
	private Void <TaskWithException>b__29_0(Hub hub, ClientMessage msg, FailureMessage error) { }
	// RVA: 0x6451c74 VA: 0x7598a69c74
	private Void <GenericTaskWithException>b__30_0(Hub hub, ClientMessage msg, FailureMessage error) { }
	// RVA: 0x6451cdc VA: 0x7598a69cdc
	private Void <SynchronousException>b__31_0(Hub hub, ClientMessage msg, FailureMessage error) { }
	// RVA: 0x6451d44 VA: 0x7598a69d44
	private Void <PassingDynamicComplex>b__32_0(Hub hub, ClientMessage msg, ResultMessage result) { }
	// RVA: 0x6451dac VA: 0x7598a69dac
	private Void <SimpleArray>b__33_0(Hub hub, ClientMessage msg, ResultMessage result) { }
	// RVA: 0x6451df8 VA: 0x7598a69df8
	private Void <ComplexType>b__34_0(Hub hub, ClientMessage msg, ResultMessage result) { }
	// RVA: 0x6451f94 VA: 0x7598a69f94
	private Void <ComplexArray>b__35_0(Hub hub, ClientMessage msg, ResultMessage result) { }
	// RVA: 0x6451fe0 VA: 0x7598a69fe0
	private Void <ReadStateValue>b__40_0(Hub hub, ClientMessage msg, ResultMessage result) { }
	// RVA: 0x6452048 VA: 0x7598a6a048
	private Void <PlainTask>b__41_0(Hub hub, ClientMessage msg, ResultMessage result) { }
	// RVA: 0x6452094 VA: 0x7598a6a094
	private Void <GenericTaskWithContinueWith>b__42_0(Hub hub, ClientMessage msg, ResultMessage result) { }
}
```