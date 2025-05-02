# CrossContextChannel

**Namespace:** `System.Runtime.Remoting.Contexts`


## Methods

- `IMessage SyncProcessMessage(IMessage)`

- `IMessageCtrl AsyncProcessMessage(IMessage, IMessageSink)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Contexts
internal class CrossContextChannel : IMessageSink
{


	// RVA: 0x5f9785c VA: 0x75985af85c
	public IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5f97c48 VA: 0x75985afc48
	public IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
	// RVA: 0x5f980f4 VA: 0x75985b00f4
	public Void .ctor() { }
}
```