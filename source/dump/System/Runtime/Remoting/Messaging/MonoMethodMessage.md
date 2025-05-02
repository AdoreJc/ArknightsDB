# MonoMethodMessage

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `RuntimeMethodInfo method`

- `LogicalCallContext ctx`

- `Object rval`

- `Exception exc`

- `AsyncResult asyncResult`

- `CallType call_type`

- `String uri`

- `MCMDictionary properties`

- `Identity identity`


## Properties

- `IDictionary Properties`

- `Int32 ArgCount`

- `LogicalCallContext LogicalCallContext`

- `MethodBase MethodBase`

- `String MethodName`

- `Object MethodSignature`

- `String TypeName`

- `String Uri`

- `Exception Exception`

- `Int32 OutArgCount`

- `Object ReturnValue`

- `AsyncResult AsyncResult`


## Methods

- `IDictionary get_Properties()`

- `Int32 get_ArgCount()`

- `LogicalCallContext get_LogicalCallContext()`

- `Void set_LogicalCallContext(LogicalCallContext)`

- `MethodBase get_MethodBase()`

- `String get_MethodName()`

- `Object get_MethodSignature()`

- `String get_TypeName()`

- `String get_Uri()`

- `Void set_Uri(String)`

- `Object GetArg(Int32)`

- `Exception get_Exception()`

- `Int32 get_OutArgCount()`

- `Object get_ReturnValue()`

- `AsyncResult get_AsyncResult()`

- `Boolean NeedsOutProcessing(out)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class MonoMethodMessage : IMethodCallMessage, IMethodMessage, IMessage, IMethodReturnMessage, IInternalMessage
{
	private RuntimeMethodInfo method; // 0x10
	private Object[] args; // 0x18
	private String[] names; // 0x20
	private Byte[] arg_types; // 0x28
	public LogicalCallContext ctx; // 0x30
	public Object rval; // 0x38
	public Exception exc; // 0x40
	private AsyncResult asyncResult; // 0x48
	private CallType call_type; // 0x50
	private String uri; // 0x58
	private MCMDictionary properties; // 0x60
	private Identity identity; // 0x68
	private Type[] methodSignature; // 0x70

	public IDictionary Properties { get; }
	public Int32 ArgCount { get; }
	public Object[] Args { get; }
	public LogicalCallContext LogicalCallContext { get; set; }
	public MethodBase MethodBase { get; }
	public String MethodName { get; }
	public Object MethodSignature { get; }
	public String TypeName { get; }
	public String Uri { get; set; }
	public Exception Exception { get; }
	public Int32 OutArgCount { get; }
	public Object[] OutArgs { get; }
	public Object ReturnValue { get; }
	private Identity System.Runtime.Remoting.Messaging.IInternalMessage.TargetIdentity { get; set; }
	public AsyncResult AsyncResult { get; }
	internal CallType CallType { get; }

	// RVA: 0x5faa97c VA: 0x75985c297c
	internal Void InitMessage(RuntimeMethodInfo method, Object[] out_args) { }
	// RVA: 0x5faac48 VA: 0x75985c2c48
	public Void .ctor(MethodBase method, Object[] out_args) { }
	// RVA: 0x5f8e820 VA: 0x75985a6820
	internal Void .ctor(MethodInfo minfo, Object[] in_args, Object[] out_args) { }
	// RVA: 0x5faad18 VA: 0x75985c2d18
	private static MethodInfo GetMethodInfo(Type type, String methodName) { }
	// RVA: 0x5faadcc VA: 0x75985c2dcc
	public Void .ctor(Type type, String methodName, Object[] in_args) { }
	// RVA: 0x5faae04 VA: 0x75985c2e04
	public IDictionary get_Properties() { }
	// RVA: 0x5faae80 VA: 0x75985c2e80
	public Int32 get_ArgCount() { }
	// RVA: 0x5faaeb8 VA: 0x75985c2eb8
	public Object[] get_Args() { }
	// RVA: 0x5faaec0 VA: 0x75985c2ec0
	public LogicalCallContext get_LogicalCallContext() { }
	// RVA: 0x5faaec8 VA: 0x75985c2ec8
	public Void set_LogicalCallContext(LogicalCallContext value) { }
	// RVA: 0x5faaed0 VA: 0x75985c2ed0
	public MethodBase get_MethodBase() { }
	// RVA: 0x5faaed8 VA: 0x75985c2ed8
	public String get_MethodName() { }
	// RVA: 0x5faaf58 VA: 0x75985c2f58
	public Object get_MethodSignature() { }
	// RVA: 0x5fab08c VA: 0x75985c308c
	public String get_TypeName() { }
	// RVA: 0x5fab120 VA: 0x75985c3120
	public String get_Uri() { }
	// RVA: 0x5fab128 VA: 0x75985c3128
	public Void set_Uri(String value) { }
	// RVA: 0x5f90c08 VA: 0x75985a8c08
	public Object GetArg(Int32 arg_num) { }
	// RVA: 0x5fab130 VA: 0x75985c3130
	public Exception get_Exception() { }
	// RVA: 0x5fab138 VA: 0x75985c3138
	public Int32 get_OutArgCount() { }
	// RVA: 0x5fab1a4 VA: 0x75985c31a4
	public Object[] get_OutArgs() { }
	// RVA: 0x5fab2e0 VA: 0x75985c32e0
	public Object get_ReturnValue() { }
	// RVA: 0x5fab2e8 VA: 0x75985c32e8
	private Identity System.Runtime.Remoting.Messaging.IInternalMessage.get_TargetIdentity() { }
	// RVA: 0x5fab2f0 VA: 0x75985c32f0
	private Void System.Runtime.Remoting.Messaging.IInternalMessage.set_TargetIdentity(Identity value) { }
	// RVA: 0x5fab2f8 VA: 0x75985c32f8
	public AsyncResult get_AsyncResult() { }
	// RVA: 0x5f8f8fc VA: 0x75985a78fc
	internal CallType get_CallType() { }
	// RVA: 0x5f90b78 VA: 0x75985a8b78
	public Boolean NeedsOutProcessing(out Int32 outCount) { }
}
```