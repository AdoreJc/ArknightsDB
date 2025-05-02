# EnvoyTerminatorSink

**Namespace:** `System.Runtime.Remoting.Messaging`


## Methods

- `IMessage SyncProcessMessage(IMessage)`

- `IMessageCtrl AsyncProcessMessage(IMessage, IMessageSink)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class EnvoyTerminatorSink : IMessageSink
{
	public static EnvoyTerminatorSink Instance; // 0x0


	// RVA: 0x5fa67b4 VA: 0x75985be7b4
	public IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5fa6868 VA: 0x75985be868
	public IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
	// RVA: 0x5fa6928 VA: 0x75985be928
	public Void .ctor() { }
	// RVA: 0x5fa6930 VA: 0x75985be930
	private static Void .cctor() { }
}
```