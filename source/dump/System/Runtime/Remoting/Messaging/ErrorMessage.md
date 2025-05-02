# ErrorMessage

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `String _uri`


## Properties

- `Int32 ArgCount`

- `MethodBase MethodBase`

- `String MethodName`

- `Object MethodSignature`

- `String TypeName`

- `String Uri`

- `LogicalCallContext LogicalCallContext`


## Methods

- `Int32 get_ArgCount()`

- `MethodBase get_MethodBase()`

- `String get_MethodName()`

- `Object get_MethodSignature()`

- `String get_TypeName()`

- `String get_Uri()`

- `Object GetArg(Int32)`

- `LogicalCallContext get_LogicalCallContext()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class ErrorMessage : IMethodCallMessage, IMethodMessage, IMessage
{
	private String _uri; // 0x10

	public Int32 ArgCount { get; }
	public Object[] Args { get; }
	public MethodBase MethodBase { get; }
	public String MethodName { get; }
	public Object MethodSignature { get; }
	public virtual IDictionary Properties { get; }
	public String TypeName { get; }
	public String Uri { get; }
	public LogicalCallContext LogicalCallContext { get; }

	// RVA: 0x5f9bee0 VA: 0x75985b3ee0
	public Void .ctor() { }
	// RVA: 0x5fa69a0 VA: 0x75985be9a0
	public Int32 get_ArgCount() { }
	// RVA: 0x5fa69a8 VA: 0x75985be9a8
	public Object[] get_Args() { }
	// RVA: 0x5fa69b0 VA: 0x75985be9b0
	public MethodBase get_MethodBase() { }
	// RVA: 0x5fa69b8 VA: 0x75985be9b8
	public String get_MethodName() { }
	// RVA: 0x5fa69f8 VA: 0x75985be9f8
	public Object get_MethodSignature() { }
	// RVA: 0x5fa6a00 VA: 0x75985bea00
	public virtual IDictionary get_Properties() { }
	// RVA: 0x5fa6a08 VA: 0x75985bea08
	public String get_TypeName() { }
	// RVA: 0x5fa6a48 VA: 0x75985bea48
	public String get_Uri() { }
	// RVA: 0x5fa6a50 VA: 0x75985bea50
	public Object GetArg(Int32 arg_num) { }
	// RVA: 0x5fa6a58 VA: 0x75985bea58
	public LogicalCallContext get_LogicalCallContext() { }
}
```