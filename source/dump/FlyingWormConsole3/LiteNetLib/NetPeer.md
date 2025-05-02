# NetPeer

**Namespace:** `FlyingWormConsole3.LiteNetLib`


## Fields

- `Int32 _rtt`

- `Int32 _avgRtt`

- `Int32 _rttCount`

- `Double _resendDelay`

- `Int32 _pingSendTimer`

- `Int32 _rttResetTimer`

- `Int32 _timeSinceLastPacket`

- `Int64 _remoteDelta`

- `Int32 _mtu`

- `Int32 _mtuIdx`

- `Boolean _finishMtu`

- `Int32 _mtuCheckTimer`

- `Int32 _mtuCheckAttempts`

- `Int32 _fragmentId`

- `Int32 _mergePos`

- `Int32 _mergeCount`

- `Int32 _connectAttempts`

- `Int32 _connectTimer`

- `Int64 _connectTime`

- `Byte _connectNum`

- `ConnectionState _connectionState`

- `NetPacket _shutdownPacket`

- `Int32 _shutdownTimer`

- `Object Tag`


## Properties

- `ConnectionState ConnectionState`

- `Int32 Ping`

- `Int32 Mtu`

- `Int64 RemoteTimeDelta`

- `DateTime RemoteUtcTime`

- `Int32 TimeSinceLastPacket`


## Methods

- `Void set_ConnectionNum(Byte)`

- `ConnectionState get_ConnectionState()`

- `Int32 get_Ping()`

- `Int32 get_Mtu()`

- `Int64 get_RemoteTimeDelta()`

- `DateTime get_RemoteUtcTime()`

- `Int32 get_TimeSinceLastPacket()`

- `Void SetMtu(Int32)`

- `Void OverrideMtu(Int32)`

- `Int32 GetPacketsCountInReliableQueue(Byte, Boolean)`

- `BaseChannel CreateChannel(Byte)`

- `Int32 GetMaxSinglePacketSize(DeliveryMethod)`

- `Void SendWithDeliveryEvent(Byte[], Byte, DeliveryMethod, Object)`

- `Void SendWithDeliveryEvent(Byte[], Int32, Int32, Byte, DeliveryMethod, Object)`

- `Void SendWithDeliveryEvent(NetDataWriter, Byte, DeliveryMethod, Object)`

- `Void Send(Byte[], DeliveryMethod)`

- `Void Send(NetDataWriter, DeliveryMethod)`

- `Void Send(Byte[], Int32, Int32, DeliveryMethod)`

- `Void Send(Byte[], Byte, DeliveryMethod)`

- `Void Send(NetDataWriter, Byte, DeliveryMethod)`

- `Void Send(Byte[], Int32, Int32, Byte, DeliveryMethod)`

- `Void SendInternal(Byte[], Int32, Int32, Byte, DeliveryMethod, Object)`

- `Void Disconnect(Byte[])`

- `Void Disconnect(NetDataWriter)`

- `Void Disconnect(Byte[], Int32, Int32)`

- `Void Disconnect()`

- `Void UpdateRoundTripTime(Int32)`

- `Void ProcessMtuPacket(NetPacket)`

- `Void UpdateMtuLogic(Int32)`

- `Void SendMerged()`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib
public class NetPeer
{
	private Int32 _rtt; // 0x10
	private Int32 _avgRtt; // 0x14
	private Int32 _rttCount; // 0x18
	private Double _resendDelay; // 0x20
	private Int32 _pingSendTimer; // 0x28
	private Int32 _rttResetTimer; // 0x2c
	private readonly Stopwatch _pingTimer; // 0x30
	private Int32 _timeSinceLastPacket; // 0x38
	private Int64 _remoteDelta; // 0x40
	private readonly NetPacketPool _packetPool; // 0x48
	private readonly Object _shutdownLock; // 0x50
	internal NetPeer NextPeer; // 0x58
	internal NetPeer PrevPeer; // 0x60
	private readonly Queue`1 _unreliableChannel; // 0x68
	private readonly Queue`1 _channelSendQueue; // 0x70
	private readonly BaseChannel[] _channels; // 0x78
	private Int32 _mtu; // 0x80
	private Int32 _mtuIdx; // 0x84
	private Boolean _finishMtu; // 0x88
	private Int32 _mtuCheckTimer; // 0x8c
	private Int32 _mtuCheckAttempts; // 0x90
	private const Int32 MtuCheckDelay; // 0x0
	private const Int32 MaxMtuCheckAttempts; // 0x0
	private readonly Object _mtuMutex; // 0x98
	private Int32 _fragmentId; // 0xa0
	private readonly Dictionary`2 _holdedFragments; // 0xa8
	private readonly Dictionary`2 _deliveredFragments; // 0xb0
	private readonly NetPacket _mergeData; // 0xb8
	private Int32 _mergePos; // 0xc0
	private Int32 _mergeCount; // 0xc4
	private Int32 _connectAttempts; // 0xc8
	private Int32 _connectTimer; // 0xcc
	private Int64 _connectTime; // 0xd0
	private Byte _connectNum; // 0xd8
	private ConnectionState _connectionState; // 0xd9
	private NetPacket _shutdownPacket; // 0xe0
	private const Int32 ShutdownDelay; // 0x0
	private Int32 _shutdownTimer; // 0xe8
	private readonly NetPacket _pingPacket; // 0xf0
	private readonly NetPacket _pongPacket; // 0xf8
	private readonly NetPacket _connectRequestPacket; // 0x100
	private readonly NetPacket _connectAcceptPacket; // 0x108
	public readonly IPEndPoint EndPoint; // 0x110
	public readonly NetManager NetManager; // 0x118
	public readonly Int32 Id; // 0x120
	public Object Tag; // 0x128
	public readonly NetStatistics Statistics; // 0x130

	internal Byte ConnectionNum { get; set; }
	public ConnectionState ConnectionState { get; }
	internal Int64 ConnectTime { get; }
	public Int32 Ping { get; }
	public Int32 Mtu { get; }
	public Int64 RemoteTimeDelta { get; }
	public DateTime RemoteUtcTime { get; }
	public Int32 TimeSinceLastPacket { get; }
	internal Double ResendDelay { get; }

	// RVA: 0x4101b74 VA: 0x7596719b74
	internal Byte get_ConnectionNum() { }
	// RVA: 0x4101b7c VA: 0x7596719b7c
	private Void set_ConnectionNum(Byte value) { }
	// RVA: 0x4101bc8 VA: 0x7596719bc8
	public ConnectionState get_ConnectionState() { }
	// RVA: 0x4101bd0 VA: 0x7596719bd0
	internal Int64 get_ConnectTime() { }
	// RVA: 0x4101bd8 VA: 0x7596719bd8
	public Int32 get_Ping() { }
	// RVA: 0x4101bec VA: 0x7596719bec
	public Int32 get_Mtu() { }
	// RVA: 0x4101bf4 VA: 0x7596719bf4
	public Int64 get_RemoteTimeDelta() { }
	// RVA: 0x4101bfc VA: 0x7596719bfc
	public DateTime get_RemoteUtcTime() { }
	// RVA: 0x4101c8c VA: 0x7596719c8c
	public Int32 get_TimeSinceLastPacket() { }
	// RVA: 0x4101c94 VA: 0x7596719c94
	internal Double get_ResendDelay() { }
	// RVA: 0x40fd384 VA: 0x7596715384
	internal Void .ctor(NetManager netManager, IPEndPoint remoteEndPoint, Int32 id) { }
	// RVA: 0x4101cac VA: 0x7596719cac
	private Void SetMtu(Int32 mtuIdx) { }
	// RVA: 0x4101c9c VA: 0x7596719c9c
	private Void OverrideMtu(Int32 mtuValue) { }
	// RVA: 0x4101d54 VA: 0x7596719d54
	public Int32 GetPacketsCountInReliableQueue(Byte channelNumber, Boolean ordered) { }
	// RVA: 0x4101e04 VA: 0x7596719e04
	private BaseChannel CreateChannel(Byte idx) { }
	// RVA: 0x41006a8 VA: 0x75967186a8
	internal Void .ctor(NetManager netManager, IPEndPoint remoteEndPoint, Int32 id, Byte connectNum, NetDataWriter connectData) { }
	// RVA: 0x40fd7b0 VA: 0x75967157b0
	internal Void .ctor(NetManager netManager, IPEndPoint remoteEndPoint, Int32 id, Int64 connectId, Byte connectNum) { }
	// RVA: 0x40fd794 VA: 0x7596715794
	internal Void Reject(Int64 connectionId, Byte connectionNumber, Byte[] data, Int32 start, Int32 length) { }
	// RVA: 0x40fe1f4 VA: 0x75967161f4
	internal Boolean ProcessConnectAccept(NetConnectAcceptPacket packet) { }
	// RVA: 0x41021d8 VA: 0x759671a1d8
	public Int32 GetMaxSinglePacketSize(DeliveryMethod options) { }
	// RVA: 0x4102250 VA: 0x759671a250
	public Void SendWithDeliveryEvent(Byte[] data, Byte channelNumber, DeliveryMethod deliveryMethod, Object userData) { }
	// RVA: 0x4102700 VA: 0x759671a700
	public Void SendWithDeliveryEvent(Byte[] data, Int32 start, Int32 length, Byte channelNumber, DeliveryMethod deliveryMethod, Object userData) { }
	// RVA: 0x4102764 VA: 0x759671a764
	public Void SendWithDeliveryEvent(NetDataWriter dataWriter, Byte channelNumber, DeliveryMethod deliveryMethod, Object userData) { }
	// RVA: 0x41027f0 VA: 0x759671a7f0
	public Void Send(Byte[] data, DeliveryMethod deliveryMethod) { }
	// RVA: 0x4102818 VA: 0x759671a818
	public Void Send(NetDataWriter dataWriter, DeliveryMethod deliveryMethod) { }
	// RVA: 0x4102848 VA: 0x759671a848
	public Void Send(Byte[] data, Int32 start, Int32 length, DeliveryMethod options) { }
	// RVA: 0x4102858 VA: 0x759671a858
	public Void Send(Byte[] data, Byte channelNumber, DeliveryMethod deliveryMethod) { }
	// RVA: 0x4102880 VA: 0x759671a880
	public Void Send(NetDataWriter dataWriter, Byte channelNumber, DeliveryMethod deliveryMethod) { }
	// RVA: 0x40fec44 VA: 0x7596716c44
	public Void Send(Byte[] data, Int32 start, Int32 length, Byte channelNumber, DeliveryMethod deliveryMethod) { }
	// RVA: 0x41022d4 VA: 0x759671a2d4
	private Void SendInternal(Byte[] data, Int32 start, Int32 length, Byte channelNumber, DeliveryMethod deliveryMethod, Object userData) { }
	// RVA: 0x41028b0 VA: 0x759671a8b0
	public Void Disconnect(Byte[] data) { }
	// RVA: 0x41028d4 VA: 0x759671a8d4
	public Void Disconnect(NetDataWriter writer) { }
	// RVA: 0x41028f8 VA: 0x759671a8f8
	public Void Disconnect(Byte[] data, Int32 start, Int32 count) { }
	// RVA: 0x4102940 VA: 0x759671a940
	public Void Disconnect() { }
	// RVA: 0x40fe024 VA: 0x7596716024
	internal DisconnectResult ProcessDisconnect(NetPacket packet) { }
	// RVA: 0x40f4f18 VA: 0x759670cf18
	internal Void AddToReliableChannelSendQueue(BaseChannel channel) { }
	// RVA: 0x40fb238 VA: 0x7596713238
	internal ShutdownResult Shutdown(Byte[] data, Int32 start, Int32 length, Boolean force) { }
	// RVA: 0x4102984 VA: 0x759671a984
	private Void UpdateRoundTripTime(Int32 roundTripTime) { }
	// RVA: 0x41029c0 VA: 0x759671a9c0
	internal Void AddReliablePacket(DeliveryMethod method, NetPacket p) { }
	// RVA: 0x4102f30 VA: 0x759671af30
	private Void ProcessMtuPacket(NetPacket packet) { }
	// RVA: 0x4103338 VA: 0x759671b338
	private Void UpdateMtuLogic(Int32 deltaTime) { }
	// RVA: 0x40fdb00 VA: 0x7596715b00
	internal ConnectRequestResult ProcessConnectRequest(NetConnectRequestPacket connRequest) { }
	// RVA: 0x40fe258 VA: 0x7596716258
	internal Void ProcessPacket(NetPacket packet) { }
	// RVA: 0x41035c8 VA: 0x759671b5c8
	private Void SendMerged() { }
	// RVA: 0x4103668 VA: 0x759671b668
	internal Void SendUserData(NetPacket packet) { }
	// RVA: 0x40fbd54 VA: 0x7596713d54
	internal Void Update(Int32 deltaTime) { }
	// RVA: 0x4103784 VA: 0x759671b784
	internal Void RecycleAndDeliver(NetPacket packet) { }
}
```