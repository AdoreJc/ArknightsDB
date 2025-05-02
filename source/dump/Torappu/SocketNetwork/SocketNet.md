# SocketNet

**Namespace:** `Torappu.SocketNetwork`


## Fields

- `Connection m_connection`

- `INetMsgProcessor m_processor`

- `INetProtocolSuite <protocolSuite>k__BackingField`


## Properties

- `INetProtocolSuite protocolSuite`

- `Int32 ping`

- `Boolean connected`


## Methods

- `INetProtocolSuite get_protocolSuite()`

- `Void set_protocolSuite(INetProtocolSuite)`

- `Void add_eStateChanged(Action`1)`

- `Void remove_eStateChanged(Action`1)`

- `Int32 get_ping()`

- `Void Init(INetMsgProcessor)`

- `Void Connect(String, Int32)`

- `Void DisConnect()`

- `Void SendMsg(NetMsg)`

- `Void SendMsg(NetMsgID)`

- `Void SendMsgWithCallback(NetMsg, NetMsgID, NetMsgHandler)`

- `Void CancelMsgCallback(NetMsgID)`

- `Boolean get_connected()`

- `Void Update()`

- `Boolean _InternalProcess(NetMsg)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SocketNetwork
public class SocketNet : IHotfixable
{
	private Connection m_connection; // 0x10
	private INetMsgProcessor m_processor; // 0x18
	private INetProtocolSuite <protocolSuite>k__BackingField; // 0x20
	private Dictionary`2 m_tempHander; // 0x28
	private Action`1 eStateChanged; // 0x30
	private static Stopwatch sWatch; // 0x0
	private static DelegateBridge __Hotfix0_get_protocolSuite; // 0x8
	private static DelegateBridge __Hotfix0_set_protocolSuite; // 0x10
	private static DelegateBridge __Hotfix0_add_eStateChanged; // 0x18
	private static DelegateBridge __Hotfix0_remove_eStateChanged; // 0x20
	private static DelegateBridge __Hotfix0_get_ping; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x38
	private static DelegateBridge __Hotfix0_Connect; // 0x40
	private static DelegateBridge __Hotfix0_DisConnect; // 0x48
	private static DelegateBridge __Hotfix0_SendMsg; // 0x50
	private static DelegateBridge __Hotfix1_SendMsg; // 0x58
	private static DelegateBridge __Hotfix0_SendMsgWithCallback; // 0x60
	private static DelegateBridge __Hotfix0_CancelMsgCallback; // 0x68
	private static DelegateBridge __Hotfix0_get_connected; // 0x70
	private static DelegateBridge __Hotfix0_Update; // 0x78
	private static DelegateBridge __Hotfix0__InternalProcess; // 0x80
	private static DelegateBridge __Hotfix0_get_highResolutionTick; // 0x88

	public INetProtocolSuite protocolSuite { get; set; }
	public Int32 ping { get; }
	public Boolean connected { get; }
	public static Int64 highResolutionTick { get; }

	// RVA: 0x3570da8 VA: 0x7595b88da8
	public INetProtocolSuite get_protocolSuite() { }
	// RVA: 0x3570e20 VA: 0x7595b88e20
	private Void set_protocolSuite(INetProtocolSuite value) { }
	// RVA: 0x3570eb4 VA: 0x7595b88eb4
	public Void add_eStateChanged(Action`1 value) { }
	// RVA: 0x3570fb8 VA: 0x7595b88fb8
	public Void remove_eStateChanged(Action`1 value) { }
	// RVA: 0x35710bc VA: 0x7595b890bc
	public Int32 get_ping() { }
	// RVA: 0x35711b8 VA: 0x7595b891b8
	public Void .ctor() { }
	// RVA: 0x3571238 VA: 0x7595b89238
	public Void Init(INetMsgProcessor processor) { }
	// RVA: 0x VA: 0x0
	public Void Connect(String host, Int32 port) { }
	// RVA: 0x3571320 VA: 0x7595b89320
	public Void DisConnect() { }
	// RVA: 0x35716a0 VA: 0x7595b896a0
	public Void SendMsg(NetMsg msg) { }
	// RVA: 0x3571938 VA: 0x7595b89938
	public Void SendMsg(NetMsgID pid) { }
	// RVA: 0x35719f4 VA: 0x7595b899f4
	public Void SendMsgWithCallback(NetMsg msg, NetMsgID id, NetMsgHandler handler) { }
	// RVA: 0x3571ad0 VA: 0x7595b89ad0
	public Void CancelMsgCallback(NetMsgID id) { }
	// RVA: 0x3571754 VA: 0x7595b89754
	public Boolean get_connected() { }
	// RVA: 0x3571be8 VA: 0x7595b89be8
	public Void Update() { }
	// RVA: 0x3571ef8 VA: 0x7595b89ef8
	private Boolean _InternalProcess(NetMsg msg) { }
	// RVA: 0x35720e4 VA: 0x7595b8a0e4
	private static Void .cctor() { }
	// RVA: 0x3572180 VA: 0x7595b8a180
	public static Int64 get_highResolutionTick() { }
}
```