# RemotingProxy

**Namespace:** `System.Runtime.Remoting.Proxies`


## Fields

- `IMessageSink _sink`

- `Boolean _hasEnvoySink`

- `ConstructionCall _ctorCall`


## Properties

- `String TypeName`


## Methods

- `String get_TypeName()`

- `Boolean CanCastTo(Type, Object)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Proxies
internal class RemotingProxy : RealProxy, IRemotingTypeInfo
{
	private static MethodInfo _cache_GetTypeMethod; // 0x0
	private static MethodInfo _cache_GetHashCodeMethod; // 0x8
	private IMessageSink _sink; // 0x50
	private Boolean _hasEnvoySink; // 0x58
	private ConstructionCall _ctorCall; // 0x60

	public String TypeName { get; }

	// RVA: 0x5f90c3c VA: 0x75985a8c3c
	internal Void .ctor(Type type, ClientIdentity identity) { }
	// RVA: 0x5f8e31c VA: 0x75985a631c
	internal Void .ctor(Type type, String activationUrl, Object[] activationAttributes) { }
	// RVA: 0x5f9167c VA: 0x75985a967c
	public override IMessage Invoke(IMessage request) { }
	// RVA: 0x5f92038 VA: 0x75985aa038
	internal Void AttachIdentity(Identity identity) { }
	// RVA: 0x5f8fa88 VA: 0x75985a7a88
	internal IMessage ActivateRemoteObject(IMethodMessage request) { }
	// RVA: 0x5f928c8 VA: 0x75985aa8c8
	public String get_TypeName() { }
	// RVA: 0x5f92a00 VA: 0x75985aaa00
	public Boolean CanCastTo(Type fromType, Object o) { }
	// RVA: 0x5f92c1c VA: 0x75985aac1c
	protected override Void Finalize() { }
	// RVA: 0x5f92d38 VA: 0x75985aad38
	private static Void .cctor() { }
}
```