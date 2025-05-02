# ClientContextTerminatorSink

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `Context _context`


## Methods

- `IMessage SyncProcessMessage(IMessage)`

- `IMessageCtrl AsyncProcessMessage(IMessage, IMessageSink)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class ClientContextTerminatorSink : IMessageSink
{
	private Context _context; // 0x10


	// RVA: 0x5f96410 VA: 0x75985ae410
	public Void .ctor(Context ctx) { }
	// RVA: 0x5fa3cf8 VA: 0x75985bbcf8
	public IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5fa3ed0 VA: 0x75985bbed0
	public IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
}
```