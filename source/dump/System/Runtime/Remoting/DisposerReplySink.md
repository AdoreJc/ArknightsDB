# DisposerReplySink

**Namespace:** `System.Runtime.Remoting`


## Fields

- `IMessageSink _next`

- `IDisposable _disposable`


## Methods

- `IMessage SyncProcessMessage(IMessage)`

- `IMessageCtrl AsyncProcessMessage(IMessage, IMessageSink)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
internal class DisposerReplySink : IMessageSink
{
	private IMessageSink _next; // 0x10
	private IDisposable _disposable; // 0x18


	// RVA: 0x5f8b614 VA: 0x75985a3614
	public Void .ctor(IMessageSink next, IDisposable disposable) { }
	// RVA: 0x5f8b658 VA: 0x75985a3658
	public IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5f8b774 VA: 0x75985a3774
	public IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
}
```