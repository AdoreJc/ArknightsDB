# SingletonIdentity

**Namespace:** `System.Runtime.Remoting`


## Methods

- `MarshalByRefObject GetServerObject()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
internal class SingletonIdentity : ServerIdentity
{


	// RVA: 0x5f89d34 VA: 0x75985a1d34
	public Void .ctor(String objectUri, Context context, Type objectType) { }
	// RVA: 0x5f8ae6c VA: 0x75985a2e6c
	public MarshalByRefObject GetServerObject() { }
	// RVA: 0x5f8b05c VA: 0x75985a305c
	public override IMessage SyncObjectProcessMessage(IMessage msg) { }
	// RVA: 0x5f8b148 VA: 0x75985a3148
	public override IMessageCtrl AsyncObjectProcessMessage(IMessage msg, IMessageSink replySink) { }
}
```