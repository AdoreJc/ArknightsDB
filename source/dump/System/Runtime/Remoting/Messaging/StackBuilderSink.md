# StackBuilderSink

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `MarshalByRefObject _target`

- `RealProxy _rp`


## Methods

- `IMessage SyncProcessMessage(IMessage)`

- `IMessageCtrl AsyncProcessMessage(IMessage, IMessageSink)`

- `Void ExecuteAsyncMessage(Object)`

- `Void CheckParameters(IMessage)`

- `Void <AsyncProcessMessage>b__4_0(Object)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class StackBuilderSink : IMessageSink
{
	private MarshalByRefObject _target; // 0x10
	private RealProxy _rp; // 0x18


	// RVA: 0x5f9660c VA: 0x75985ae60c
	public Void .ctor(MarshalByRefObject obj, Boolean forceInternalExecute) { }
	// RVA: 0x5fac3bc VA: 0x75985c43bc
	public IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5fac8d8 VA: 0x75985c48d8
	public IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
	// RVA: 0x5faca10 VA: 0x75985c4a10
	private Void ExecuteAsyncMessage(Object ob) { }
	// RVA: 0x5fac488 VA: 0x75985c4488
	private Void CheckParameters(IMessage msg) { }
	// RVA: 0x5facc10 VA: 0x75985c4c10
	private Void <AsyncProcessMessage>b__4_0(Object data) { }
}
```