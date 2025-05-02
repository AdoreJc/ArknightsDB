# CrossAppDomainSink

**Namespace:** `System.Runtime.Remoting.Channels`


## Fields

- `Int32 _domainID`


## Methods

- `Void SendAsyncMessage(Object)`

- `Void <AsyncProcessMessage>b__10_0(Object)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Channels
internal class CrossAppDomainSink : IMessageSink
{
	private static Hashtable s_sinks; // 0x0
	private static MethodInfo processMessageMethod; // 0x8
	private Int32 _domainID; // 0x10

	internal Int32 TargetDomainId { get; }

	// RVA: 0x5f9bd70 VA: 0x75985b3d70
	internal Void .ctor(Int32 domainID) { }
	// RVA: 0x5f9ba4c VA: 0x75985b3a4c
	internal static CrossAppDomainSink GetSink(Int32 domainID) { }
	// RVA: 0x5f9bd98 VA: 0x75985b3d98
	internal Int32 get_TargetDomainId() { }
	// RVA: 0x5f9bda0 VA: 0x75985b3da0
	private static ProcessMessageRes ProcessMessageInDomain(Byte[] arrRequest, CADMethodCallMessage cadMsg) { }
	// RVA: 0x5f9c034 VA: 0x75985b4034
	public virtual IMessage SyncProcessMessage(IMessage msgRequest) { }
	// RVA: 0x5f9c80c VA: 0x75985b480c
	public virtual IMessageCtrl AsyncProcessMessage(IMessage reqMsg, IMessageSink replySink) { }
	// RVA: 0x5f9c91c VA: 0x75985b491c
	public Void SendAsyncMessage(Object data) { }
	// RVA: 0x5f9ca28 VA: 0x75985b4a28
	private static Void .cctor() { }
	// RVA: 0x5f9cb3c VA: 0x75985b4b3c
	private Void <AsyncProcessMessage>b__10_0(Object data) { }
}
```