# ClientIdentity

**Namespace:** `System.Runtime.Remoting`


## Fields

- `WeakReference _proxyReference`


## Properties

- `MarshalByRefObject ClientProxy`

- `String TargetUri`


## Methods

- `MarshalByRefObject get_ClientProxy()`

- `Void set_ClientProxy(MarshalByRefObject)`

- `String get_TargetUri()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
internal class ClientIdentity : Identity
{
	private WeakReference _proxyReference; // 0x48

	public MarshalByRefObject ClientProxy { get; set; }
	public String TargetUri { get; }

	// RVA: 0x5f7ce2c VA: 0x7598594e2c
	public Void .ctor(String objectUri, ObjRef objRef) { }
	// RVA: 0x5f7cf60 VA: 0x7598594f60
	public MarshalByRefObject get_ClientProxy() { }
	// RVA: 0x5f7cfe8 VA: 0x7598594fe8
	public Void set_ClientProxy(MarshalByRefObject value) { }
	// RVA: 0x5f7d060 VA: 0x7598595060
	public override ObjRef CreateObjRef(Type requestedType) { }
	// RVA: 0x5f7d068 VA: 0x7598595068
	public String get_TargetUri() { }
}
```