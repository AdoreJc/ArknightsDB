# MethodResponse

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `String _methodName`

- `String _uri`

- `String _typeName`

- `MethodBase _methodBase`

- `Object _returnValue`

- `Exception _exception`

- `ArgInfo _inArgInfo`

- `IMethodCallMessage _callMsg`

- `LogicalCallContext _callContext`

- `Identity _targetIdentity`

- `IDictionary ExternalProperties`

- `IDictionary InternalProperties`


## Properties

- `Int32 ArgCount`

- `Exception Exception`

- `LogicalCallContext LogicalCallContext`

- `MethodBase MethodBase`

- `String MethodName`

- `Object MethodSignature`

- `Object ReturnValue`

- `String TypeName`

- `String Uri`


## Methods

- `Int32 get_ArgCount()`

- `Exception get_Exception()`

- `LogicalCallContext get_LogicalCallContext()`

- `MethodBase get_MethodBase()`

- `String get_MethodName()`

- `Object get_MethodSignature()`

- `Object get_ReturnValue()`

- `String get_TypeName()`

- `String get_Uri()`

- `Void set_Uri(String)`

- `Object GetArg(Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
public class MethodResponse : IMethodReturnMessage, IMethodMessage, IMessage, ISerializable, IInternalMessage
{
	private String _methodName; // 0x10
	private String _uri; // 0x18
	private String _typeName; // 0x20
	private MethodBase _methodBase; // 0x28
	private Object _returnValue; // 0x30
	private Exception _exception; // 0x38
	private Type[] _methodSignature; // 0x40
	private ArgInfo _inArgInfo; // 0x48
	private Object[] _args; // 0x50
	private Object[] _outArgs; // 0x58
	private IMethodCallMessage _callMsg; // 0x60
	private LogicalCallContext _callContext; // 0x68
	private Identity _targetIdentity; // 0x70
	protected IDictionary ExternalProperties; // 0x78
	protected IDictionary InternalProperties; // 0x80

	public Int32 ArgCount { get; }
	public Object[] Args { get; }
	public Exception Exception { get; }
	public LogicalCallContext LogicalCallContext { get; }
	public MethodBase MethodBase { get; }
	public String MethodName { get; }
	public Object MethodSignature { get; }
	public Object[] OutArgs { get; }
	public virtual IDictionary Properties { get; }
	public Object ReturnValue { get; }
	public String TypeName { get; }
	public String Uri { get; set; }
	private String System.Runtime.Remoting.Messaging.IInternalMessage.Uri { get; set; }
	private Identity System.Runtime.Remoting.Messaging.IInternalMessage.TargetIdentity { get; set; }

	// RVA: 0x5f9ad78 VA: 0x75985b2d78
	internal Void .ctor(Exception e, IMethodCallMessage msg) { }
	// RVA: 0x5f91c44 VA: 0x75985a9c44
	internal Void .ctor(Object returnValue, Object[] outArgs, LogicalCallContext callCtx, IMethodCallMessage msg) { }
	// RVA: 0x5f9c554 VA: 0x75985b4554
	internal Void .ctor(IMethodCallMessage msg, CADMethodReturnMessage retmsg) { }
	// RVA: 0x5fa6690 VA: 0x75985be690
	internal Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fa9508 VA: 0x75985c1508
	internal Void InitMethodProperty(String key, Object value) { }
	// RVA: 0x5fa99c0 VA: 0x75985c19c0
	public Int32 get_ArgCount() { }
	// RVA: 0x5fa99d8 VA: 0x75985c19d8
	public Object[] get_Args() { }
	// RVA: 0x5fa99e0 VA: 0x75985c19e0
	public Exception get_Exception() { }
	// RVA: 0x5fa99e8 VA: 0x75985c19e8
	public LogicalCallContext get_LogicalCallContext() { }
	// RVA: 0x5fa9a60 VA: 0x75985c1a60
	public MethodBase get_MethodBase() { }
	// RVA: 0x5fa9b84 VA: 0x75985c1b84
	public String get_MethodName() { }
	// RVA: 0x5fa9d1c VA: 0x75985c1d1c
	public Object get_MethodSignature() { }
	// RVA: 0x5fa9e3c VA: 0x75985c1e3c
	public Object[] get_OutArgs() { }
	// RVA: 0x5fa6720 VA: 0x75985be720
	public virtual IDictionary get_Properties() { }
	// RVA: 0x5faa01c VA: 0x75985c201c
	public Object get_ReturnValue() { }
	// RVA: 0x5fa9c50 VA: 0x75985c1c50
	public String get_TypeName() { }
	// RVA: 0x5faa024 VA: 0x75985c2024
	public String get_Uri() { }
	// RVA: 0x5faa0f0 VA: 0x75985c20f0
	public Void set_Uri(String value) { }
	// RVA: 0x5faa0f8 VA: 0x75985c20f8
	private String System.Runtime.Remoting.Messaging.IInternalMessage.get_Uri() { }
	// RVA: 0x5faa0fc VA: 0x75985c20fc
	private Void System.Runtime.Remoting.Messaging.IInternalMessage.set_Uri(String value) { }
	// RVA: 0x5faa104 VA: 0x75985c2104
	public Object GetArg(Int32 argNum) { }
	// RVA: 0x5faa138 VA: 0x75985c2138
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5faa5e8 VA: 0x75985c25e8
	private Identity System.Runtime.Remoting.Messaging.IInternalMessage.get_TargetIdentity() { }
	// RVA: 0x5faa5f0 VA: 0x75985c25f0
	private Void System.Runtime.Remoting.Messaging.IInternalMessage.set_TargetIdentity(Identity value) { }
}
```