# CrossAppDomainChannel

**Namespace:** `System.Runtime.Remoting.Channels`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Channels
internal class CrossAppDomainChannel : IChannel, IChannelSender, IChannelReceiver
{
	private static Object s_lock; // 0x0

	public virtual String ChannelName { get; }
	public virtual Int32 ChannelPriority { get; }
	public virtual Object ChannelData { get; }

	// RVA: 0x5f9b6bc VA: 0x75985b36bc
	internal static Void RegisterCrossAppDomainChannel() { }
	// RVA: 0x5f9b808 VA: 0x75985b3808
	public virtual String get_ChannelName() { }
	// RVA: 0x5f9b848 VA: 0x75985b3848
	public virtual Int32 get_ChannelPriority() { }
	// RVA: 0x5f9b850 VA: 0x75985b3850
	public virtual Object get_ChannelData() { }
	// RVA: 0x5f9b8bc VA: 0x75985b38bc
	public virtual Void StartListening(Object data) { }
	// RVA: 0x5f9b8c0 VA: 0x75985b38c0
	public virtual IMessageSink CreateMessageSink(String url, Object data, out String uri) { }
	// RVA: 0x5f9b800 VA: 0x75985b3800
	public Void .ctor() { }
	// RVA: 0x5f9bcec VA: 0x75985b3cec
	private static Void .cctor() { }
}
```