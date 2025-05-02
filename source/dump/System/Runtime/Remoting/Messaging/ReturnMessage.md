# ReturnMessage

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `LogicalCallContext _callCtx`

- `Object _returnValue`

- `String _uri`

- `Exception _exception`

- `MethodBase _methodBase`

- `String _methodName`

- `String _typeName`

- `MethodReturnDictionary _properties`

- `Identity _targetIdentity`

- `ArgInfo _inArgInfo`


## Properties

- `Int32 ArgCount`

- `LogicalCallContext LogicalCallContext`

- `MethodBase MethodBase`

- `String MethodName`

- `Object MethodSignature`

- `String TypeName`

- `String Uri`

- `Exception Exception`


## Methods

- `Int32 get_ArgCount()`

- `LogicalCallContext get_LogicalCallContext()`

- `MethodBase get_MethodBase()`

- `String get_MethodName()`

- `Object get_MethodSignature()`

- `String get_TypeName()`

- `String get_Uri()`

- `Void set_Uri(String)`

- `Object GetArg(Int32)`

- `Exception get_Exception()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
public class ReturnMessage : IMethodReturnMessage, IMethodMessage, IMessage, IInternalMessage
{
	private Object[] _outArgs; // 0x10
	private Object[] _args; // 0x18
	private LogicalCallContext _callCtx; // 0x20
	private Object _returnValue; // 0x28
	private String _uri; // 0x30
	private Exception _exception; // 0x38
	private MethodBase _methodBase; // 0x40
	private String _methodName; // 0x48
	private Type[] _methodSignature; // 0x50
	private String _typeName; // 0x58
	private MethodReturnDictionary _properties; // 0x60
	private Identity _targetIdentity; // 0x68
	private ArgInfo _inArgInfo; // 0x70

	public Int32 ArgCount { get; }
	public Object[] Args { get; }
	public LogicalCallContext LogicalCallContext { get; }
	public MethodBase MethodBase { get; }
	public String MethodName { get; }
	public Object MethodSignature { get; }
	public virtual IDictionary Properties { get; }
	public String TypeName { get; }
	public String Uri { get; set; }
	private String System.Runtime.Remoting.Messaging.IInternalMessage.Uri { get; set; }
	public Exception Exception { get; }
	public Object[] OutArgs { get; }
	public virtual Object ReturnValue { get; }
	private Identity System.Runtime.Remoting.Messaging.IInternalMessage.TargetIdentity { get; set; }

	// RVA: 0x5f8fd40 VA: 0x75985a7d40
	public Void .ctor(Object ret, Object[] outArgs, Int32 outArgsCount, LogicalCallContext callCtx, IMethodCallMessage mcm) { }
	// RVA: 0x5f8fbcc VA: 0x75985a7bcc
	public Void .ctor(Exception e, IMethodCallMessage mcm) { }
	// RVA: 0x5fab89c VA: 0x75985c389c
	public Int32 get_ArgCount() { }
	// RVA: 0x5fab8b8 VA: 0x75985c38b8
	public Object[] get_Args() { }
	// RVA: 0x5fab8c0 VA: 0x75985c38c0
	public LogicalCallContext get_LogicalCallContext() { }
	// RVA: 0x5fab938 VA: 0x75985c3938
	public MethodBase get_MethodBase() { }
	// RVA: 0x5fab940 VA: 0x75985c3940
	public String get_MethodName() { }
	// RVA: 0x5fab9a4 VA: 0x75985c39a4
	public Object get_MethodSignature() { }
	// RVA: 0x5fabaec VA: 0x75985c3aec
	public virtual IDictionary get_Properties() { }
	// RVA: 0x5fabb68 VA: 0x75985c3b68
	public String get_TypeName() { }
	// RVA: 0x5fabbe0 VA: 0x75985c3be0
	public String get_Uri() { }
	// RVA: 0x5fabbe8 VA: 0x75985c3be8
	public Void set_Uri(String value) { }
	// RVA: 0x5fabbf0 VA: 0x75985c3bf0
	private String System.Runtime.Remoting.Messaging.IInternalMessage.get_Uri() { }
	// RVA: 0x5fabbf8 VA: 0x75985c3bf8
	private Void System.Runtime.Remoting.Messaging.IInternalMessage.set_Uri(String value) { }
	// RVA: 0x5fabc00 VA: 0x75985c3c00
	public Object GetArg(Int32 argNum) { }
	// RVA: 0x5fabc30 VA: 0x75985c3c30
	public Exception get_Exception() { }
	// RVA: 0x5fabc38 VA: 0x75985c3c38
	public Object[] get_OutArgs() { }
	// RVA: 0x5fabd00 VA: 0x75985c3d00
	public virtual Object get_ReturnValue() { }
	// RVA: 0x5fabd08 VA: 0x75985c3d08
	private Identity System.Runtime.Remoting.Messaging.IInternalMessage.get_TargetIdentity() { }
	// RVA: 0x5fabd10 VA: 0x75985c3d10
	private Void System.Runtime.Remoting.Messaging.IInternalMessage.set_TargetIdentity(Identity value) { }
}
```