# NetManager

**Namespace:** `FlyingWormConsole3.LiteNetLib`


## Fields

- `Thread _logicThread`

- `Boolean _manualMode`

- `NetEvent _netEventPoolHead`

- `NetPeer _headPeer`

- `Int32 _connectedPeersCount`

- `Int32 _lastPeerId`

- `Byte _channelsCount`

- `Boolean UnconnectedMessagesEnabled`

- `Boolean NatPunchEnabled`

- `Int32 UpdateTime`

- `Int32 PingInterval`

- `Int32 DisconnectTimeout`

- `Boolean SimulatePacketLoss`

- `Boolean SimulateLatency`

- `Int32 SimulationPacketLossChance`

- `Int32 SimulationMinLatency`

- `Int32 SimulationMaxLatency`

- `Boolean UnsyncedEvents`

- `Boolean UnsyncedReceiveEvent`

- `Boolean UnsyncedDeliveryEvent`

- `Boolean BroadcastReceiveEnabled`

- `Int32 ReconnectDelay`

- `Int32 MaxConnectAttempts`

- `Boolean ReuseAddress`

- `Boolean EnableStatistics`

- `Boolean AutoRecycle`

- `IPv6Mode IPv6Enabled`

- `Int32 MtuOverride`

- `Boolean UseSafeMtu`

- `Boolean DisconnectOnUnreachable`


## Properties

- `Boolean IsRunning`

- `Int32 LocalPort`

- `NetPeer FirstPeer`

- `Byte ChannelsCount`

- `Int32 ConnectedPeersCount`

- `Int32 ExtraPacketSizeForLayer`


## Methods

- `Boolean get_IsRunning()`

- `Int32 get_LocalPort()`

- `NetPeer get_FirstPeer()`

- `Byte get_ChannelsCount()`

- `Void set_ChannelsCount(Byte)`

- `NetPeer GetPeerById(Int32)`

- `Int32 get_ConnectedPeersCount()`

- `Int32 get_ExtraPacketSizeForLayer()`

- `Boolean TryGetPeer(IPEndPoint, out)`

- `Void AddPeer(NetPeer)`

- `Void RemovePeer(NetPeer)`

- `Void RemovePeerInternal(NetPeer)`

- `Void DisconnectPeer(NetPeer, DisconnectReason, SocketError, Boolean, Byte[], Int32, Int32, NetPacket)`

- `Void CreateEvent(EType, NetPeer, IPEndPoint, SocketError, Int32, DisconnectReason, ConnectionRequest, DeliveryMethod, NetPacket, Object)`

- `Void ProcessEvent(NetEvent)`

- `Void UpdateLogic()`

- `Void ProcessDelayedPackets()`

- `Void ProcessNtpRequests(Int32)`

- `Void ManualUpdate(Int32)`

- `Void ManualReceive()`

- `Int32 GetNextPeerId()`

- `Void ProcessConnectRequest(IPEndPoint, NetPeer, NetConnectRequestPacket)`

- `Void DataReceived(NetPacket, IPEndPoint)`

- `Void SendToAll(NetDataWriter, DeliveryMethod)`

- `Void SendToAll(Byte[], DeliveryMethod)`

- `Void SendToAll(Byte[], Int32, Int32, DeliveryMethod)`

- `Void SendToAll(NetDataWriter, Byte, DeliveryMethod)`

- `Void SendToAll(Byte[], Byte, DeliveryMethod)`

- `Void SendToAll(Byte[], Int32, Int32, Byte, DeliveryMethod)`

- `Void SendToAll(NetDataWriter, DeliveryMethod, NetPeer)`

- `Void SendToAll(Byte[], DeliveryMethod, NetPeer)`

- `Void SendToAll(Byte[], Int32, Int32, DeliveryMethod, NetPeer)`

- `Void SendToAll(NetDataWriter, Byte, DeliveryMethod, NetPeer)`

- `Void SendToAll(Byte[], Byte, DeliveryMethod, NetPeer)`

- `Void SendToAll(Byte[], Int32, Int32, Byte, DeliveryMethod, NetPeer)`

- `Boolean Start()`

- `Boolean Start(IPAddress, IPAddress, Int32)`

- `Boolean Start(String, String, Int32)`

- `Boolean Start(Int32)`

- `Boolean StartInManualMode(IPAddress, IPAddress, Int32)`

- `Boolean StartInManualMode(String, String, Int32)`

- `Boolean StartInManualMode(Int32)`

- `Boolean SendUnconnectedMessage(Byte[], IPEndPoint)`

- `Boolean SendUnconnectedMessage(NetDataWriter, IPEndPoint)`

- `Boolean SendUnconnectedMessage(Byte[], Int32, Int32, IPEndPoint)`

- `Boolean SendBroadcast(NetDataWriter, Int32)`

- `Boolean SendBroadcast(Byte[], Int32)`

- `Boolean SendBroadcast(Byte[], Int32, Int32, Int32)`

- `Void TriggerUpdate()`

- `Void PollEvents()`

- `NetPeer Connect(String, Int32, String)`

- `NetPeer Connect(String, Int32, NetDataWriter)`

- `NetPeer Connect(IPEndPoint, String)`

- `NetPeer Connect(IPEndPoint, NetDataWriter)`

- `Void Stop()`

- `Void Stop(Boolean)`

- `Int32 GetPeersCount(ConnectionState)`

- `Void GetPeersNonAlloc(List`1, ConnectionState)`

- `Void DisconnectAll()`

- `Void DisconnectAll(Byte[], Int32, Int32)`

- `Void DisconnectPeerForce(NetPeer)`

- `Void DisconnectPeer(NetPeer)`

- `Void DisconnectPeer(NetPeer, Byte[])`

- `Void DisconnectPeer(NetPeer, NetDataWriter)`

- `Void DisconnectPeer(NetPeer, Byte[], Int32, Int32)`

- `Void CreateNtpRequest(IPEndPoint)`

- `Void CreateNtpRequest(String, Int32)`

- `Void CreateNtpRequest(String)`

- `NetPeerEnumerator GetEnumerator()`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib
public class NetManager : IEnumerable`1, IEnumerable
{
	private readonly NetSocket _socket; // 0x10
	private Thread _logicThread; // 0x18
	private Boolean _manualMode; // 0x20
	private readonly AutoResetEvent _updateTriggerEvent; // 0x28
	private readonly Queue`1 _netEventsQueue; // 0x30
	private NetEvent _netEventPoolHead; // 0x38
	private readonly INetEventListener _netEventListener; // 0x40
	private readonly IDeliveryEventListener _deliveryEventListener; // 0x48
	private readonly INtpEventListener _ntpEventListener; // 0x50
	private readonly Dictionary`2 _peersDict; // 0x58
	private readonly Dictionary`2 _requestsDict; // 0x60
	private readonly Dictionary`2 _ntpRequests; // 0x68
	private readonly ReaderWriterLockSlim _peersLock; // 0x70
	private NetPeer _headPeer; // 0x78
	private Int32 _connectedPeersCount; // 0x80
	private readonly List`1 _connectedPeerListCache; // 0x88
	private NetPeer[] _peersArray; // 0x90
	private readonly PacketLayerBase _extraPacketLayer; // 0x98
	private Int32 _lastPeerId; // 0xa0
	private readonly Queue`1 _peerIds; // 0xa8
	private Byte _channelsCount; // 0xb0
	private readonly Object _eventLock; // 0xb8
	internal readonly NetPacketPool NetPacketPool; // 0xc0
	public Boolean UnconnectedMessagesEnabled; // 0xc8
	public Boolean NatPunchEnabled; // 0xc9
	public Int32 UpdateTime; // 0xcc
	public Int32 PingInterval; // 0xd0
	public Int32 DisconnectTimeout; // 0xd4
	public Boolean SimulatePacketLoss; // 0xd8
	public Boolean SimulateLatency; // 0xd9
	public Int32 SimulationPacketLossChance; // 0xdc
	public Int32 SimulationMinLatency; // 0xe0
	public Int32 SimulationMaxLatency; // 0xe4
	public Boolean UnsyncedEvents; // 0xe8
	public Boolean UnsyncedReceiveEvent; // 0xe9
	public Boolean UnsyncedDeliveryEvent; // 0xea
	public Boolean BroadcastReceiveEnabled; // 0xeb
	public Int32 ReconnectDelay; // 0xec
	public Int32 MaxConnectAttempts; // 0xf0
	public Boolean ReuseAddress; // 0xf4
	public readonly NetStatistics Statistics; // 0xf8
	public Boolean EnableStatistics; // 0x100
	public readonly NatPunchModule NatPunchModule; // 0x108
	public Boolean AutoRecycle; // 0x110
	public IPv6Mode IPv6Enabled; // 0x114
	public Int32 MtuOverride; // 0x118
	public Boolean UseSafeMtu; // 0x11c
	public Boolean DisconnectOnUnreachable; // 0x11d

	public Boolean IsRunning { get; }
	public Int32 LocalPort { get; }
	public NetPeer FirstPeer { get; }
	public Byte ChannelsCount { get; set; }
	public List`1 ConnectedPeerList { get; }
	public Int32 ConnectedPeersCount { get; }
	public Int32 ExtraPacketSizeForLayer { get; }

	// RVA: 0x40f9bc0 VA: 0x7596711bc0
	public Boolean get_IsRunning() { }
	// RVA: 0x40f9be4 VA: 0x7596711be4
	public Int32 get_LocalPort() { }
	// RVA: 0x40f9c00 VA: 0x7596711c00
	public NetPeer get_FirstPeer() { }
	// RVA: 0x40f9c18 VA: 0x7596711c18
	public Byte get_ChannelsCount() { }
	// RVA: 0x40f9c20 VA: 0x7596711c20
	public Void set_ChannelsCount(Byte value) { }
	// RVA: 0x40f9c8c VA: 0x7596711c8c
	public List`1 get_ConnectedPeerList() { }
	// RVA: 0x40f9dd4 VA: 0x7596711dd4
	public NetPeer GetPeerById(Int32 id) { }
	// RVA: 0x40f9e04 VA: 0x7596711e04
	public Int32 get_ConnectedPeersCount() { }
	// RVA: 0x40f9e1c VA: 0x7596711e1c
	public Int32 get_ExtraPacketSizeForLayer() { }
	// RVA: 0x40f9e34 VA: 0x7596711e34
	private Boolean TryGetPeer(IPEndPoint endPoint, out NetPeer peer) { }
	// RVA: 0x40f9ecc VA: 0x7596711ecc
	private Void AddPeer(NetPeer peer) { }
	// RVA: 0x40fa048 VA: 0x7596712048
	private Void RemovePeer(NetPeer peer) { }
	// RVA: 0x40fa090 VA: 0x7596712090
	private Void RemovePeerInternal(NetPeer peer) { }
	// RVA: 0x40fa288 VA: 0x7596712288
	public Void .ctor(INetEventListener listener, PacketLayerBase extraPacketLayer) { }
	// RVA: 0x40fa8a8 VA: 0x75967128a8
	internal Void ConnectionLatencyUpdated(NetPeer fromPeer, Int32 latency) { }
	// RVA: 0x40fac1c VA: 0x7596712c1c
	internal Void MessageDelivered(NetPeer fromPeer, Object userData) { }
	// RVA: 0x40fac68 VA: 0x7596712c68
	internal Int32 SendRawAndRecycle(NetPacket packet, IPEndPoint remoteEndPoint) { }
	// RVA: 0x40faee8 VA: 0x7596712ee8
	internal Int32 SendRaw(NetPacket packet, IPEndPoint remoteEndPoint) { }
	// RVA: 0x40facbc VA: 0x7596712cbc
	internal Int32 SendRaw(Byte[] message, Int32 start, Int32 length, IPEndPoint remoteEndPoint) { }
	// RVA: 0x40fb138 VA: 0x7596713138
	internal Void DisconnectPeerForce(NetPeer peer, DisconnectReason reason, SocketError socketErrorCode, NetPacket eventData) { }
	// RVA: 0x40fb180 VA: 0x7596713180
	private Void DisconnectPeer(NetPeer peer, DisconnectReason reason, SocketError socketErrorCode, Boolean force, Byte[] data, Int32 start, Int32 count, NetPacket eventData) { }
	// RVA: 0x40fa8e8 VA: 0x75967128e8
	private Void CreateEvent(EType type, NetPeer peer, IPEndPoint remoteEndPoint, SocketError errorCode, Int32 latency, DisconnectReason disconnectReason, ConnectionRequest connectionRequest, DeliveryMethod deliveryMethod, NetPacket readerSource, Object userData) { }
	// RVA: 0x40fb5a8 VA: 0x75967135a8
	private Void ProcessEvent(NetEvent evt) { }
	// RVA: 0x40f99b0 VA: 0x75967119b0
	internal Void RecycleEvent(NetEvent evt) { }
	// RVA: 0x40fbaa4 VA: 0x7596713aa4
	private Void UpdateLogic() { }
	// RVA: 0x40fc674 VA: 0x7596714674
	private Void ProcessDelayedPackets() { }
	// RVA: 0x40fc2b4 VA: 0x75967142b4
	private Void ProcessNtpRequests(Int32 elapsedMilliseconds) { }
	// RVA: 0x40fc678 VA: 0x7596714678
	public Void ManualUpdate(Int32 elapsedMilliseconds) { }
	// RVA: 0x40fc6fc VA: 0x75967146fc
	public Void ManualReceive() { }
	// RVA: 0x40fc764 VA: 0x7596714764
	internal Void OnMessageReceived(NetPacket packet, SocketError errorCode, IPEndPoint remoteEndPoint) { }
	// RVA: 0x40f53e0 VA: 0x759670d3e0
	internal NetPeer OnConnectionSolved(ConnectionRequest request, Byte[] rejectData, Int32 start, Int32 length) { }
	// RVA: 0x40fd254 VA: 0x7596715254
	private Int32 GetNextPeerId() { }
	// RVA: 0x40fd81c VA: 0x759671581c
	private Void ProcessConnectRequest(IPEndPoint remoteEndPoint, NetPeer netPeer, NetConnectRequestPacket connRequest) { }
	// RVA: 0x40fca0c VA: 0x7596714a0c
	private Void DataReceived(NetPacket packet, IPEndPoint remoteEndPoint) { }
	// RVA: 0x40fe808 VA: 0x7596716808
	internal Void CreateReceiveEvent(NetPacket packet, DeliveryMethod method, Int32 headerSize, NetPeer fromPeer) { }
	// RVA: 0x40fea88 VA: 0x7596716a88
	public Void SendToAll(NetDataWriter writer, DeliveryMethod options) { }
	// RVA: 0x40feac0 VA: 0x7596716ac0
	public Void SendToAll(Byte[] data, DeliveryMethod options) { }
	// RVA: 0x40feab4 VA: 0x7596716ab4
	public Void SendToAll(Byte[] data, Int32 start, Int32 length, DeliveryMethod options) { }
	// RVA: 0x40febf4 VA: 0x7596716bf4
	public Void SendToAll(NetDataWriter writer, Byte channelNumber, DeliveryMethod options) { }
	// RVA: 0x40fec20 VA: 0x7596716c20
	public Void SendToAll(Byte[] data, Byte channelNumber, DeliveryMethod options) { }
	// RVA: 0x40feae4 VA: 0x7596716ae4
	public Void SendToAll(Byte[] data, Int32 start, Int32 length, Byte channelNumber, DeliveryMethod options) { }
	// RVA: 0x40fec4c VA: 0x7596716c4c
	public Void SendToAll(NetDataWriter writer, DeliveryMethod options, NetPeer excludePeer) { }
	// RVA: 0x40feda0 VA: 0x7596716da0
	public Void SendToAll(Byte[] data, DeliveryMethod options, NetPeer excludePeer) { }
	// RVA: 0x40fedc8 VA: 0x7596716dc8
	public Void SendToAll(Byte[] data, Int32 start, Int32 length, DeliveryMethod options, NetPeer excludePeer) { }
	// RVA: 0x40fedd8 VA: 0x7596716dd8
	public Void SendToAll(NetDataWriter writer, Byte channelNumber, DeliveryMethod options, NetPeer excludePeer) { }
	// RVA: 0x40fee08 VA: 0x7596716e08
	public Void SendToAll(Byte[] data, Byte channelNumber, DeliveryMethod options, NetPeer excludePeer) { }
	// RVA: 0x40fec7c VA: 0x7596716c7c
	public Void SendToAll(Byte[] data, Int32 start, Int32 length, Byte channelNumber, DeliveryMethod options, NetPeer excludePeer) { }
	// RVA: 0x40fee30 VA: 0x7596716e30
	public Boolean Start() { }
	// RVA: 0x40feeac VA: 0x7596716eac
	public Boolean Start(IPAddress addressIPv4, IPAddress addressIPv6, Int32 port) { }
	// RVA: 0x40ff580 VA: 0x7596717580
	public Boolean Start(String addressIPv4, String addressIPv6, Int32 port) { }
	// RVA: 0x40fee38 VA: 0x7596716e38
	public Boolean Start(Int32 port) { }
	// RVA: 0x40ff7c8 VA: 0x75967177c8
	public Boolean StartInManualMode(IPAddress addressIPv4, IPAddress addressIPv6, Int32 port) { }
	// RVA: 0x40ff7f8 VA: 0x75967177f8
	public Boolean StartInManualMode(String addressIPv4, String addressIPv6, Int32 port) { }
	// RVA: 0x40ff888 VA: 0x7596717888
	public Boolean StartInManualMode(Int32 port) { }
	// RVA: 0x40ff8fc VA: 0x75967178fc
	public Boolean SendUnconnectedMessage(Byte[] message, IPEndPoint remoteEndPoint) { }
	// RVA: 0x40ff970 VA: 0x7596717970
	public Boolean SendUnconnectedMessage(NetDataWriter writer, IPEndPoint remoteEndPoint) { }
	// RVA: 0x40ff91c VA: 0x759671791c
	public Boolean SendUnconnectedMessage(Byte[] message, Int32 start, Int32 length, IPEndPoint remoteEndPoint) { }
	// RVA: 0x40ffa54 VA: 0x7596717a54
	public Boolean SendBroadcast(NetDataWriter writer, Int32 port) { }
	// RVA: 0x40ffbf0 VA: 0x7596717bf0
	public Boolean SendBroadcast(Byte[] data, Int32 port) { }
	// RVA: 0x40ffa7c VA: 0x7596717a7c
	public Boolean SendBroadcast(Byte[] data, Int32 start, Int32 length, Int32 port) { }
	// RVA: 0x40fffcc VA: 0x7596717fcc
	public Void TriggerUpdate() { }
	// RVA: 0x40fffe8 VA: 0x7596717fe8
	public Void PollEvents() { }
	// RVA: 0x41001fc VA: 0x75967181fc
	public NetPeer Connect(String address, Int32 port, String key) { }
	// RVA: 0x41002a4 VA: 0x75967182a4
	public NetPeer Connect(String address, Int32 port, NetDataWriter connectionData) { }
	// RVA: 0x4100678 VA: 0x7596718678
	public NetPeer Connect(IPEndPoint target, String key) { }
	// RVA: 0x41003ec VA: 0x75967183ec
	public NetPeer Connect(IPEndPoint target, NetDataWriter connectionData) { }
	// RVA: 0x41007c8 VA: 0x75967187c8
	public Void Stop() { }
	// RVA: 0x41007d0 VA: 0x75967187d0
	public Void Stop(Boolean sendDisconnectMessages) { }
	// RVA: 0x4100bc8 VA: 0x7596718bc8
	public Int32 GetPeersCount(ConnectionState peerState) { }
	// RVA: 0x40f9cac VA: 0x7596711cac
	public Void GetPeersNonAlloc(List`1 peers, ConnectionState peerState) { }
	// RVA: 0x4100c3c VA: 0x7596718c3c
	public Void DisconnectAll() { }
	// RVA: 0x4100c4c VA: 0x7596718c4c
	public Void DisconnectAll(Byte[] data, Int32 start, Int32 count) { }
	// RVA: 0x4100cdc VA: 0x7596718cdc
	public Void DisconnectPeerForce(NetPeer peer) { }
	// RVA: 0x4100d10 VA: 0x7596718d10
	public Void DisconnectPeer(NetPeer peer) { }
	// RVA: 0x4100d78 VA: 0x7596718d78
	public Void DisconnectPeer(NetPeer peer, Byte[] data) { }
	// RVA: 0x4100db4 VA: 0x7596718db4
	public Void DisconnectPeer(NetPeer peer, NetDataWriter writer) { }
	// RVA: 0x4100d44 VA: 0x7596718d44
	public Void DisconnectPeer(NetPeer peer, Byte[] data, Int32 start, Int32 count) { }
	// RVA: 0x4100df0 VA: 0x7596718df0
	public Void CreateNtpRequest(IPEndPoint endPoint) { }
	// RVA: 0x4100e88 VA: 0x7596718e88
	public Void CreateNtpRequest(String ntpServerAddress, Int32 port) { }
	// RVA: 0x4100f5c VA: 0x7596718f5c
	public Void CreateNtpRequest(String ntpServerAddress) { }
	// RVA: 0x410102c VA: 0x759671902c
	public NetPeerEnumerator GetEnumerator() { }
	// RVA: 0x41010a0 VA: 0x75967190a0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<FlyingWormConsole3.LiteNetLib.NetPeer>.GetEnumerator() { }
	// RVA: 0x410112c VA: 0x759671912c
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```