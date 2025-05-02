# EventBasedNetListener

**Namespace:** `FlyingWormConsole3.LiteNetLib`


## Fields

- `OnPeerConnected PeerConnectedEvent`

- `OnPeerDisconnected PeerDisconnectedEvent`

- `OnNetworkError NetworkErrorEvent`

- `OnNetworkReceive NetworkReceiveEvent`

- `OnNetworkReceiveUnconnected NetworkReceiveUnconnectedEvent`

- `OnNetworkLatencyUpdate NetworkLatencyUpdateEvent`

- `OnConnectionRequest ConnectionRequestEvent`

- `OnDeliveryEvent DeliveryEvent`

- `OnNtpResponseEvent NtpResponseEvent`


## Methods

- `Void add_PeerConnectedEvent(OnPeerConnected)`

- `Void remove_PeerConnectedEvent(OnPeerConnected)`

- `Void add_PeerDisconnectedEvent(OnPeerDisconnected)`

- `Void remove_PeerDisconnectedEvent(OnPeerDisconnected)`

- `Void add_NetworkErrorEvent(OnNetworkError)`

- `Void remove_NetworkErrorEvent(OnNetworkError)`

- `Void add_NetworkReceiveEvent(OnNetworkReceive)`

- `Void remove_NetworkReceiveEvent(OnNetworkReceive)`

- `Void add_NetworkReceiveUnconnectedEvent(OnNetworkReceiveUnconnected)`

- `Void remove_NetworkReceiveUnconnectedEvent(OnNetworkReceiveUnconnected)`

- `Void add_NetworkLatencyUpdateEvent(OnNetworkLatencyUpdate)`

- `Void remove_NetworkLatencyUpdateEvent(OnNetworkLatencyUpdate)`

- `Void add_ConnectionRequestEvent(OnConnectionRequest)`

- `Void remove_ConnectionRequestEvent(OnConnectionRequest)`

- `Void add_DeliveryEvent(OnDeliveryEvent)`

- `Void remove_DeliveryEvent(OnDeliveryEvent)`

- `Void add_NtpResponseEvent(OnNtpResponseEvent)`

- `Void remove_NtpResponseEvent(OnNtpResponseEvent)`

- `Void ClearPeerConnectedEvent()`

- `Void ClearPeerDisconnectedEvent()`

- `Void ClearNetworkErrorEvent()`

- `Void ClearNetworkReceiveEvent()`

- `Void ClearNetworkReceiveUnconnectedEvent()`

- `Void ClearNetworkLatencyUpdateEvent()`

- `Void ClearConnectionRequestEvent()`

- `Void ClearDeliveryEvent()`

- `Void ClearNtpResponseEvent()`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib
public class EventBasedNetListener : INetEventListener, IDeliveryEventListener, INtpEventListener
{
	private OnPeerConnected PeerConnectedEvent; // 0x10
	private OnPeerDisconnected PeerDisconnectedEvent; // 0x18
	private OnNetworkError NetworkErrorEvent; // 0x20
	private OnNetworkReceive NetworkReceiveEvent; // 0x28
	private OnNetworkReceiveUnconnected NetworkReceiveUnconnectedEvent; // 0x30
	private OnNetworkLatencyUpdate NetworkLatencyUpdateEvent; // 0x38
	private OnConnectionRequest ConnectionRequestEvent; // 0x40
	private OnDeliveryEvent DeliveryEvent; // 0x48
	private OnNtpResponseEvent NtpResponseEvent; // 0x50


	// RVA: 0x40f5990 VA: 0x759670d990
	public Void add_PeerConnectedEvent(OnPeerConnected value) { }
	// RVA: 0x40f5a2c VA: 0x759670da2c
	public Void remove_PeerConnectedEvent(OnPeerConnected value) { }
	// RVA: 0x40f5ac8 VA: 0x759670dac8
	public Void add_PeerDisconnectedEvent(OnPeerDisconnected value) { }
	// RVA: 0x40f5b64 VA: 0x759670db64
	public Void remove_PeerDisconnectedEvent(OnPeerDisconnected value) { }
	// RVA: 0x40f5c00 VA: 0x759670dc00
	public Void add_NetworkErrorEvent(OnNetworkError value) { }
	// RVA: 0x40f5c9c VA: 0x759670dc9c
	public Void remove_NetworkErrorEvent(OnNetworkError value) { }
	// RVA: 0x40f5d38 VA: 0x759670dd38
	public Void add_NetworkReceiveEvent(OnNetworkReceive value) { }
	// RVA: 0x40f5dd4 VA: 0x759670ddd4
	public Void remove_NetworkReceiveEvent(OnNetworkReceive value) { }
	// RVA: 0x40f5e70 VA: 0x759670de70
	public Void add_NetworkReceiveUnconnectedEvent(OnNetworkReceiveUnconnected value) { }
	// RVA: 0x40f5f0c VA: 0x759670df0c
	public Void remove_NetworkReceiveUnconnectedEvent(OnNetworkReceiveUnconnected value) { }
	// RVA: 0x40f5fa8 VA: 0x759670dfa8
	public Void add_NetworkLatencyUpdateEvent(OnNetworkLatencyUpdate value) { }
	// RVA: 0x40f6044 VA: 0x759670e044
	public Void remove_NetworkLatencyUpdateEvent(OnNetworkLatencyUpdate value) { }
	// RVA: 0x40f60e0 VA: 0x759670e0e0
	public Void add_ConnectionRequestEvent(OnConnectionRequest value) { }
	// RVA: 0x40f617c VA: 0x759670e17c
	public Void remove_ConnectionRequestEvent(OnConnectionRequest value) { }
	// RVA: 0x40f6218 VA: 0x759670e218
	public Void add_DeliveryEvent(OnDeliveryEvent value) { }
	// RVA: 0x40f62b4 VA: 0x759670e2b4
	public Void remove_DeliveryEvent(OnDeliveryEvent value) { }
	// RVA: 0x40f6350 VA: 0x759670e350
	public Void add_NtpResponseEvent(OnNtpResponseEvent value) { }
	// RVA: 0x40f63ec VA: 0x759670e3ec
	public Void remove_NtpResponseEvent(OnNtpResponseEvent value) { }
	// RVA: 0x40f6488 VA: 0x759670e488
	public Void ClearPeerConnectedEvent() { }
	// RVA: 0x40f6494 VA: 0x759670e494
	public Void ClearPeerDisconnectedEvent() { }
	// RVA: 0x40f64a0 VA: 0x759670e4a0
	public Void ClearNetworkErrorEvent() { }
	// RVA: 0x40f64ac VA: 0x759670e4ac
	public Void ClearNetworkReceiveEvent() { }
	// RVA: 0x40f64b8 VA: 0x759670e4b8
	public Void ClearNetworkReceiveUnconnectedEvent() { }
	// RVA: 0x40f64c4 VA: 0x759670e4c4
	public Void ClearNetworkLatencyUpdateEvent() { }
	// RVA: 0x40f64d0 VA: 0x759670e4d0
	public Void ClearConnectionRequestEvent() { }
	// RVA: 0x40f64dc VA: 0x759670e4dc
	public Void ClearDeliveryEvent() { }
	// RVA: 0x40f64e8 VA: 0x759670e4e8
	public Void ClearNtpResponseEvent() { }
	// RVA: 0x40f64f4 VA: 0x759670e4f4
	private Void FlyingWormConsole3.LiteNetLib.INetEventListener.OnPeerConnected(NetPeer peer) { }
	// RVA: 0x40f6510 VA: 0x759670e510
	private Void FlyingWormConsole3.LiteNetLib.INetEventListener.OnPeerDisconnected(NetPeer peer, DisconnectInfo disconnectInfo) { }
	// RVA: 0x40f652c VA: 0x759670e52c
	private Void FlyingWormConsole3.LiteNetLib.INetEventListener.OnNetworkError(IPEndPoint endPoint, SocketError socketErrorCode) { }
	// RVA: 0x40f6548 VA: 0x759670e548
	private Void FlyingWormConsole3.LiteNetLib.INetEventListener.OnNetworkReceive(NetPeer peer, NetPacketReader reader, DeliveryMethod deliveryMethod) { }
	// RVA: 0x40f6564 VA: 0x759670e564
	private Void FlyingWormConsole3.LiteNetLib.INetEventListener.OnNetworkReceiveUnconnected(IPEndPoint remoteEndPoint, NetPacketReader reader, UnconnectedMessageType messageType) { }
	// RVA: 0x40f6580 VA: 0x759670e580
	private Void FlyingWormConsole3.LiteNetLib.INetEventListener.OnNetworkLatencyUpdate(NetPeer peer, Int32 latency) { }
	// RVA: 0x40f659c VA: 0x759670e59c
	private Void FlyingWormConsole3.LiteNetLib.INetEventListener.OnConnectionRequest(ConnectionRequest request) { }
	// RVA: 0x40f65b8 VA: 0x759670e5b8
	private Void FlyingWormConsole3.LiteNetLib.IDeliveryEventListener.OnMessageDelivered(NetPeer peer, Object userData) { }
	// RVA: 0x40f65d4 VA: 0x759670e5d4
	private Void FlyingWormConsole3.LiteNetLib.INtpEventListener.OnNtpResponse(NtpPacket packet) { }
	// RVA: 0x40f65f0 VA: 0x759670e5f0
	public Void .ctor() { }
}
```