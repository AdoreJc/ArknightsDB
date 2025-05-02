# ServerObjectReplySink

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `IMessageSink _replySink`

- `ServerIdentity _identity`


## Methods

- `IMessage SyncProcessMessage(IMessage)`

- `IMessageCtrl AsyncProcessMessage(IMessage, IMessageSink)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class ServerObjectReplySink : IMessageSink
{
	private IMessageSink _replySink; // 0x10
	private ServerIdentity _identity; // 0x18


	// RVA: 0x5fac270 VA: 0x75985c4270
	public Void .ctor(ServerIdentity identity, IMessageSink replySink) { }
	// RVA: 0x5fac2b4 VA: 0x75985c42b4
	public IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5fac37c VA: 0x75985c437c
	public IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
}
```