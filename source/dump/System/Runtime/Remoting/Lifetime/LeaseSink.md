# LeaseSink

**Namespace:** `System.Runtime.Remoting.Lifetime`


## Fields

- `IMessageSink _nextSink`


## Methods

- `IMessage SyncProcessMessage(IMessage)`

- `IMessageCtrl AsyncProcessMessage(IMessage, IMessageSink)`

- `Void RenewLease(IMessage)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Lifetime
internal class LeaseSink : IMessageSink
{
	private IMessageSink _nextSink; // 0x10


	// RVA: 0x5f9402c VA: 0x75985ac02c
	public Void .ctor(IMessageSink nextSink) { }
	// RVA: 0x5f9405c VA: 0x75985ac05c
	public IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5f9439c VA: 0x75985ac39c
	public IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
	// RVA: 0x5f9410c VA: 0x75985ac10c
	private Void RenewLease(IMessage msg) { }
}
```