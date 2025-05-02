# ServerObjectTerminatorSink

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `IMessageSink _nextSink`


## Methods

- `IMessage SyncProcessMessage(IMessage)`

- `IMessageCtrl AsyncProcessMessage(IMessage, IMessageSink)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class ServerObjectTerminatorSink : IMessageSink
{
	private IMessageSink _nextSink; // 0x10


	// RVA: 0x5f966d4 VA: 0x75985ae6d4
	public Void .ctor(IMessageSink nextSink) { }
	// RVA: 0x5fabf30 VA: 0x75985c3f30
	public IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5fac0a4 VA: 0x75985c40a4
	public IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
}
```