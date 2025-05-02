# ClientActivatedIdentity

**Namespace:** `System.Runtime.Remoting`


## Fields

- `MarshalByRefObject _targetThis`


## Methods

- `MarshalByRefObject GetServerObject()`

- `Void SetClientProxy(MarshalByRefObject)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
internal class ClientActivatedIdentity : ServerIdentity
{
	private MarshalByRefObject _targetThis; // 0x70


	// RVA: 0x5f89cb0 VA: 0x75985a1cb0
	public Void .ctor(String objectUri, Type objectType) { }
	// RVA: 0x5f8ac04 VA: 0x75985a2c04
	public MarshalByRefObject GetServerObject() { }
	// RVA: 0x5f8ac0c VA: 0x75985a2c0c
	public Void SetClientProxy(MarshalByRefObject obj) { }
	// RVA: 0x5f8ac14 VA: 0x75985a2c14
	public override Void OnLifetimeExpired() { }
	// RVA: 0x5f8ac70 VA: 0x75985a2c70
	public override IMessage SyncObjectProcessMessage(IMessage msg) { }
	// RVA: 0x5f8ad68 VA: 0x75985a2d68
	public override IMessageCtrl AsyncObjectProcessMessage(IMessage msg, IMessageSink replySink) { }
}
```