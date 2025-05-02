# NetPacketProcessor

**Namespace:** `FlyingWormConsole3.LiteNetLib.Utils`


## Methods

- `Void RegisterNestedType()`

- `Void RegisterNestedType(Action`2, Func`2)`

- `Void RegisterNestedType(Func`1)`

- `Void ReadAllPackets(NetDataReader)`

- `Void ReadAllPackets(NetDataReader, Object)`

- `Void ReadPacket(NetDataReader)`

- `Void Send(NetPeer, T, DeliveryMethod)`

- `Void SendNetSerializable(NetPeer, T, DeliveryMethod)`

- `Void Send(NetManager, T, DeliveryMethod)`

- `Void SendNetSerializable(NetManager, T, DeliveryMethod)`

- `Void Write(NetDataWriter, T)`

- `Void WriteNetSerializable(NetDataWriter, T)`

- `Void ReadPacket(NetDataReader, Object)`

- `Void Subscribe(Action`1, Func`1)`

- `Void Subscribe(Action`2, Func`1)`

- `Void SubscribeReusable(Action`1)`

- `Void SubscribeReusable(Action`2)`

- `Void SubscribeNetSerializable(Action`2, Func`1)`

- `Void SubscribeNetSerializable(Action`1, Func`1)`

- `Void SubscribeNetSerializable(Action`2)`

- `Void SubscribeNetSerializable(Action`1)`

- `Boolean RemoveSubscription()`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib.Utils
public class NetPacketProcessor
{
	private readonly NetSerializer _netSerializer; // 0x10
	private readonly Dictionary`2 _callbacks; // 0x18
	private readonly NetDataWriter _netDataWriter; // 0x20


	// RVA: 0x410a4d4 VA: 0x75967224d4
	public Void .ctor() { }
	// RVA: 0x410a5dc VA: 0x75967225dc
	public Void .ctor(Int32 maxStringLength) { }
	// RVA: 0x VA: 0x0
	protected virtual UInt64 GetHash() { }
	// RVA: 0x410a784 VA: 0x7596722784
	protected virtual SubscribeDelegate GetCallbackFromData(NetDataReader reader) { }
	// RVA: 0x VA: 0x0
	protected virtual Void WriteHash(NetDataWriter writer) { }
	// RVA: 0x VA: 0x0
	public Void RegisterNestedType() { }
	// RVA: 0x VA: 0x0
	public Void RegisterNestedType(Action`2 writeDelegate, Func`2 readDelegate) { }
	// RVA: 0x VA: 0x0
	public Void RegisterNestedType(Func`1 constructor) { }
	// RVA: 0x410a8bc VA: 0x75967228bc
	public Void ReadAllPackets(NetDataReader reader) { }
	// RVA: 0x410a910 VA: 0x7596722910
	public Void ReadAllPackets(NetDataReader reader, Object userData) { }
	// RVA: 0x410a908 VA: 0x7596722908
	public Void ReadPacket(NetDataReader reader) { }
	// RVA: 0x VA: 0x0
	public Void Send(NetPeer peer, T packet, DeliveryMethod options) { }
	// RVA: 0x VA: 0x0
	public Void SendNetSerializable(NetPeer peer, T packet, DeliveryMethod options) { }
	// RVA: 0x VA: 0x0
	public Void Send(NetManager manager, T packet, DeliveryMethod options) { }
	// RVA: 0x VA: 0x0
	public Void SendNetSerializable(NetManager manager, T packet, DeliveryMethod options) { }
	// RVA: 0x VA: 0x0
	public Void Write(NetDataWriter writer, T packet) { }
	// RVA: 0x VA: 0x0
	public Void WriteNetSerializable(NetDataWriter writer, T packet) { }
	// RVA: 0x VA: 0x0
	public Byte[] Write(T packet) { }
	// RVA: 0x VA: 0x0
	public Byte[] WriteNetSerializable(T packet) { }
	// RVA: 0x410a960 VA: 0x7596722960
	public Void ReadPacket(NetDataReader reader, Object userData) { }
	// RVA: 0x VA: 0x0
	public Void Subscribe(Action`1 onReceive, Func`1 packetConstructor) { }
	// RVA: 0x VA: 0x0
	public Void Subscribe(Action`2 onReceive, Func`1 packetConstructor) { }
	// RVA: 0x VA: 0x0
	public Void SubscribeReusable(Action`1 onReceive) { }
	// RVA: 0x VA: 0x0
	public Void SubscribeReusable(Action`2 onReceive) { }
	// RVA: 0x VA: 0x0
	public Void SubscribeNetSerializable(Action`2 onReceive, Func`1 packetConstructor) { }
	// RVA: 0x VA: 0x0
	public Void SubscribeNetSerializable(Action`1 onReceive, Func`1 packetConstructor) { }
	// RVA: 0x VA: 0x0
	public Void SubscribeNetSerializable(Action`2 onReceive) { }
	// RVA: 0x VA: 0x0
	public Void SubscribeNetSerializable(Action`1 onReceive) { }
	// RVA: 0x VA: 0x0
	public Boolean RemoveSubscription() { }
}
```