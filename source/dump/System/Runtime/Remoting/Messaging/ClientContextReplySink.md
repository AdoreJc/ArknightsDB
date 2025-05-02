# ClientContextReplySink

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `IMessageSink _replySink`

- `Context _context`


## Methods

- `IMessage SyncProcessMessage(IMessage)`

- `IMessageCtrl AsyncProcessMessage(IMessage, IMessageSink)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class ClientContextReplySink : IMessageSink
{
	private IMessageSink _replySink; // 0x10
	private Context _context; // 0x18


	// RVA: 0x5fa40f8 VA: 0x75985bc0f8
	public Void .ctor(Context ctx, IMessageSink replySink) { }
	// RVA: 0x5fa413c VA: 0x75985bc13c
	public IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5fa4240 VA: 0x75985bc240
	public IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
}
```