# ConnectionRequest

**Namespace:** `FlyingWormConsole3.LiteNetLib`


## Fields

- `Int32 _used`

- `ConnectionRequestResult <Result>k__BackingField`


## Methods

- `Void set_Result(ConnectionRequestResult)`

- `Boolean TryActivate()`

- `NetPeer AcceptIfKey(String)`

- `NetPeer Accept()`

- `Void Reject(Byte[], Int32, Int32, Boolean)`

- `Void Reject(Byte[], Int32, Int32)`

- `Void RejectForce(Byte[], Int32, Int32)`

- `Void RejectForce()`

- `Void RejectForce(Byte[])`

- `Void RejectForce(NetDataWriter)`

- `Void Reject()`

- `Void Reject(Byte[])`

- `Void Reject(NetDataWriter)`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib
public class ConnectionRequest
{
	private readonly NetManager _listener; // 0x10
	private Int32 _used; // 0x18
	public readonly NetDataReader Data; // 0x20
	private ConnectionRequestResult <Result>k__BackingField; // 0x28
	internal Int64 ConnectionTime; // 0x30
	internal Byte ConnectionNumber; // 0x38
	public readonly IPEndPoint RemoteEndPoint; // 0x40

	internal ConnectionRequestResult Result { get; set; }

	// RVA: 0x40f5054 VA: 0x759670d054
	internal ConnectionRequestResult get_Result() { }
	// RVA: 0x40f505c VA: 0x759670d05c
	private Void set_Result(ConnectionRequestResult value) { }
	// RVA: 0x40f5064 VA: 0x759670d064
	private Boolean TryActivate() { }
	// RVA: 0x40f508c VA: 0x759670d08c
	internal Void UpdateRequest(NetConnectRequestPacket connRequest) { }
	// RVA: 0x40f50bc VA: 0x759670d0bc
	internal Void .ctor(Int64 connectionId, Byte connectionNumber, NetDataReader netDataReader, IPEndPoint endPoint, NetManager listener) { }
	// RVA: 0x40f5134 VA: 0x759670d134
	public NetPeer AcceptIfKey(String key) { }
	// RVA: 0x40f57dc VA: 0x759670d7dc
	public NetPeer Accept() { }
	// RVA: 0x40f5840 VA: 0x759670d840
	public Void Reject(Byte[] rejectData, Int32 start, Int32 length, Boolean force) { }
	// RVA: 0x40f58c8 VA: 0x759670d8c8
	public Void Reject(Byte[] rejectData, Int32 start, Int32 length) { }
	// RVA: 0x40f58d0 VA: 0x759670d8d0
	public Void RejectForce(Byte[] rejectData, Int32 start, Int32 length) { }
	// RVA: 0x40f58d8 VA: 0x759670d8d8
	public Void RejectForce() { }
	// RVA: 0x40f58ec VA: 0x759670d8ec
	public Void RejectForce(Byte[] rejectData) { }
	// RVA: 0x40f590c VA: 0x759670d90c
	public Void RejectForce(NetDataWriter rejectData) { }
	// RVA: 0x40f5934 VA: 0x759670d934
	public Void Reject() { }
	// RVA: 0x40f5948 VA: 0x759670d948
	public Void Reject(Byte[] rejectData) { }
	// RVA: 0x40f5968 VA: 0x759670d968
	public Void Reject(NetDataWriter rejectData) { }
}
```