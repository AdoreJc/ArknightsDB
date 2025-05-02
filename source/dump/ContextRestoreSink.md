# ContextRestoreSink

**Namespace:** ` `


## Fields

- `IMessageSink _next`

- `Context _context`

- `IMessage _call`


## Methods

- `IMessage SyncProcessMessage(IMessage)`

- `IMessageCtrl AsyncProcessMessage(IMessage, IMessageSink)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class ContextRestoreSink : IMessageSink
{
	private IMessageSink _next; // 0x10
	private Context _context; // 0x18
	private IMessage _call; // 0x20


	// RVA: 0x5f98094 VA: 0x75985b0094
	public Void .ctor(IMessageSink next, Context context, IMessage call) { }
	// RVA: 0x5f980fc VA: 0x75985b00fc
	public IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5f983bc VA: 0x75985b03bc
	public IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
}
```