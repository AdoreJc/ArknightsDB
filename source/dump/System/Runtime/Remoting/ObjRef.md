# ObjRef

**Namespace:** `System.Runtime.Remoting`


## Fields

- `IChannelInfo channel_info`

- `String uri`

- `IRemotingTypeInfo typeInfo`

- `IEnvoyInfo envoyInfo`

- `Int32 flags`

- `Type _serverType`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
public class ObjRef : IObjectReference, ISerializable
{
	private IChannelInfo channel_info; // 0x10
	private String uri; // 0x18
	private IRemotingTypeInfo typeInfo; // 0x20
	private IEnvoyInfo envoyInfo; // 0x28
	private Int32 flags; // 0x30
	private Type _serverType; // 0x38
	private static Int32 MarshalledObjectRef; // 0x0
	private static Int32 WellKnowObjectRef; // 0x4

	internal Boolean IsReferenceToWellKnow { get; }
	public virtual IChannelInfo ChannelInfo { get; }
	public virtual IEnvoyInfo EnvoyInfo { get; set; }
	public virtual IRemotingTypeInfo TypeInfo { get; set; }
	public virtual String URI { get; set; }
	internal Type ServerType { get; }

	// RVA: 0x5f7d65c VA: 0x759859565c
	public Void .ctor() { }
	// RVA: 0x5f7d6dc VA: 0x75985956dc
	internal Void .ctor(String uri, IChannelInfo cinfo) { }
	// RVA: 0x5f7d720 VA: 0x7598595720
	internal ObjRef DeserializeInTheCurrentDomain(Int32 domainId, Byte[] tInfo) { }
	// RVA: 0x5f7d85c VA: 0x759859585c
	internal Byte[] SerializeType() { }
	// RVA: 0x5f7d8d8 VA: 0x75985958d8
	internal Void .ctor(Type type, String url, Object remoteChannelData) { }
	// RVA: 0x5f7de98 VA: 0x7598595e98
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f7e468 VA: 0x7598596468
	internal Boolean get_IsReferenceToWellKnow() { }
	// RVA: 0x5f7e4d0 VA: 0x75985964d0
	public virtual IChannelInfo get_ChannelInfo() { }
	// RVA: 0x5f7e4d8 VA: 0x75985964d8
	public virtual IEnvoyInfo get_EnvoyInfo() { }
	// RVA: 0x5f7e4e0 VA: 0x75985964e0
	public virtual Void set_EnvoyInfo(IEnvoyInfo value) { }
	// RVA: 0x5f7e4e8 VA: 0x75985964e8
	public virtual IRemotingTypeInfo get_TypeInfo() { }
	// RVA: 0x5f7e4f0 VA: 0x75985964f0
	public virtual Void set_TypeInfo(IRemotingTypeInfo value) { }
	// RVA: 0x5f7e4f8 VA: 0x75985964f8
	public virtual String get_URI() { }
	// RVA: 0x5f7e500 VA: 0x7598596500
	public virtual Void set_URI(String value) { }
	// RVA: 0x5f7e508 VA: 0x7598596508
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f7e6e0 VA: 0x75985966e0
	public virtual Object GetRealObject(StreamingContext context) { }
	// RVA: 0x5f7d678 VA: 0x7598595678
	internal Void UpdateChannelInfo() { }
	// RVA: 0x5f7e7dc VA: 0x75985967dc
	internal Type get_ServerType() { }
	// RVA: 0x5f7e92c VA: 0x759859692c
	private static Void .cctor() { }
}
```