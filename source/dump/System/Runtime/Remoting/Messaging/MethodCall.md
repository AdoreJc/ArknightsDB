# MethodCall

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `String _uri`

- `String _typeName`

- `String _methodName`

- `MethodBase _methodBase`

- `LogicalCallContext _callContext`

- `Identity _targetIdentity`

- `IDictionary ExternalProperties`

- `IDictionary InternalProperties`


## Properties

- `Int32 ArgCount`

- `LogicalCallContext LogicalCallContext`

- `MethodBase MethodBase`

- `String MethodName`

- `Object MethodSignature`

- `String TypeName`

- `String Uri`


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

- `Void ResolveMethod()`

- `Type CastTo(String, Type)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
public class MethodCall : IMethodCallMessage, IMethodMessage, IMessage, ISerializable, IInternalMessage
{
	private String _uri; // 0x10
	private String _typeName; // 0x18
	private String _methodName; // 0x20
	private Object[] _args; // 0x28
	private Type[] _methodSignature; // 0x30
	private MethodBase _methodBase; // 0x38
	private LogicalCallContext _callContext; // 0x40
	private Identity _targetIdentity; // 0x48
	private Type[] _genericArguments; // 0x50
	protected IDictionary ExternalProperties; // 0x58
	protected IDictionary InternalProperties; // 0x60

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
	private Identity System.Runtime.Remoting.Messaging.IInternalMessage.TargetIdentity { get; set; }
	private Type[] GenericArguments { get; }

	// RVA: 0x5fa428c VA: 0x75985bc28c
	internal Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fa6c80 VA: 0x75985bec80
	internal Void .ctor(CADMethodCallMessage msg) { }
	// RVA: 0x5fa4280 VA: 0x75985bc280
	internal Void .ctor() { }
	// RVA: 0x5f922c8 VA: 0x75985aa2c8
	internal Void CopyFrom(IMethodMessage call) { }
	// RVA: 0x5fa48dc VA: 0x75985bc8dc
	internal virtual Void InitMethodProperty(String key, Object value) { }
	// RVA: 0x5fa4ea4 VA: 0x75985bcea4
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fa6dd8 VA: 0x75985bedd8
	public Int32 get_ArgCount() { }
	// RVA: 0x5fa6df4 VA: 0x75985bedf4
	public Object[] get_Args() { }
	// RVA: 0x5fa6dfc VA: 0x75985bedfc
	public LogicalCallContext get_LogicalCallContext() { }
	// RVA: 0x5fa6e74 VA: 0x75985bee74
	public MethodBase get_MethodBase() { }
	// RVA: 0x5fa7510 VA: 0x75985bf510
	public String get_MethodName() { }
	// RVA: 0x5fa7558 VA: 0x75985bf558
	public Object get_MethodSignature() { }
	// RVA: 0x5fa5364 VA: 0x75985bd364
	public virtual IDictionary get_Properties() { }
	// RVA: 0x5fa76a0 VA: 0x75985bf6a0
	internal virtual Void InitDictionary() { }
	// RVA: 0x5fa77ac VA: 0x75985bf7ac
	public String get_TypeName() { }
	// RVA: 0x5fa7808 VA: 0x75985bf808
	public String get_Uri() { }
	// RVA: 0x5fa7810 VA: 0x75985bf810
	public Void set_Uri(String value) { }
	// RVA: 0x5fa7818 VA: 0x75985bf818
	private String System.Runtime.Remoting.Messaging.IInternalMessage.get_Uri() { }
	// RVA: 0x5fa7820 VA: 0x75985bf820
	private Void System.Runtime.Remoting.Messaging.IInternalMessage.set_Uri(String value) { }
	// RVA: 0x5fa7828 VA: 0x75985bf828
	public Object GetArg(Int32 argNum) { }
	// RVA: 0x5fa7858 VA: 0x75985bf858
	public virtual Void Init() { }
	// RVA: 0x5fa6ea4 VA: 0x75985beea4
	public Void ResolveMethod() { }
	// RVA: 0x5fa785c VA: 0x75985bf85c
	private Type CastTo(String clientType, Type serverType) { }
	// RVA: 0x5fa7a40 VA: 0x75985bfa40
	private static String GetTypeNameFromAssemblyQualifiedName(String aqname) { }
	// RVA: 0x5fa7ae8 VA: 0x75985bfae8
	private Identity System.Runtime.Remoting.Messaging.IInternalMessage.get_TargetIdentity() { }
	// RVA: 0x5fa7af0 VA: 0x75985bfaf0
	private Void System.Runtime.Remoting.Messaging.IInternalMessage.set_TargetIdentity(Identity value) { }
	// RVA: 0x5fa79ec VA: 0x75985bf9ec
	private Type[] get_GenericArguments() { }
}
```