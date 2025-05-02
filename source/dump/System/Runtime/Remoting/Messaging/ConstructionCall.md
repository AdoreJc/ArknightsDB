# ConstructionCall

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `IActivator _activator`

- `IList _contextProperties`

- `Type _activationType`

- `String _activationTypeName`

- `Boolean _isContextOk`

- `RemotingProxy _sourceProxy`


## Properties

- `Type ActivationType`

- `String ActivationTypeName`

- `IActivator Activator`

- `IList ContextProperties`


## Methods

- `Type get_ActivationType()`

- `String get_ActivationTypeName()`

- `IActivator get_Activator()`

- `Void set_Activator(IActivator)`

- `IList get_ContextProperties()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
public class ConstructionCall : MethodCall, IConstructionCallMessage, IMessage, IMethodCallMessage, IMethodMessage
{
	private IActivator _activator; // 0x68
	private Object[] _activationAttributes; // 0x70
	private IList _contextProperties; // 0x78
	private Type _activationType; // 0x80
	private String _activationTypeName; // 0x88
	private Boolean _isContextOk; // 0x90
	private RemotingProxy _sourceProxy; // 0x98

	internal Boolean IsContextOk { get; set; }
	public Type ActivationType { get; }
	public String ActivationTypeName { get; }
	public IActivator Activator { get; set; }
	public Object[] CallSiteActivationAttributes { get; }
	public IList ContextProperties { get; }
	public override IDictionary Properties { get; }
	internal RemotingProxy SourceProxy { get; set; }

	// RVA: 0x5f8fb64 VA: 0x75985a7b64
	internal Void .ctor(Type type) { }
	// RVA: 0x5fa4288 VA: 0x75985bc288
	internal Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fa4338 VA: 0x75985bc338
	internal override Void InitDictionary() { }
	// RVA: 0x5fa4490 VA: 0x75985bc490
	internal Boolean get_IsContextOk() { }
	// RVA: 0x5fa4498 VA: 0x75985bc498
	internal Void set_IsContextOk(Boolean value) { }
	// RVA: 0x5fa44a4 VA: 0x75985bc4a4
	public Type get_ActivationType() { }
	// RVA: 0x5fa4578 VA: 0x75985bc578
	public String get_ActivationTypeName() { }
	// RVA: 0x5fa4580 VA: 0x75985bc580
	public IActivator get_Activator() { }
	// RVA: 0x5fa4588 VA: 0x75985bc588
	public Void set_Activator(IActivator value) { }
	// RVA: 0x5fa4590 VA: 0x75985bc590
	public Object[] get_CallSiteActivationAttributes() { }
	// RVA: 0x5fa4598 VA: 0x75985bc598
	internal Void SetActivationAttributes(Object[] attributes) { }
	// RVA: 0x5fa45a0 VA: 0x75985bc5a0
	public IList get_ContextProperties() { }
	// RVA: 0x5fa4618 VA: 0x75985bc618
	internal override Void InitMethodProperty(String key, Object value) { }
	// RVA: 0x5fa4d0c VA: 0x75985bcd0c
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fa5334 VA: 0x75985bd334
	public override IDictionary get_Properties() { }
	// RVA: 0x5fa5394 VA: 0x75985bd394
	internal RemotingProxy get_SourceProxy() { }
	// RVA: 0x5fa539c VA: 0x75985bd39c
	internal Void set_SourceProxy(RemotingProxy value) { }
}
```