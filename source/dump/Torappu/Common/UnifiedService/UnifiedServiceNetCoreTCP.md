# UnifiedServiceNetCoreTCP

**Namespace:** `Torappu.Common.UnifiedService`


## Fields

- `SocketNet m_socket`

- `ProtocolRegistry m_protocolSuite`


## Methods

- `Void set_msgParseErrListener(Action`1)`

- `Void _NetStateChanged(ConnectionState)`

- `Void RegisterProtocol()`

- `Void SetCmdProcessor(NetMsgID, ProtocolProcFunc`1)`

- `Boolean ProcMsg(NetMsg)`

- `Boolean _ProcMsg(Protocol)`

- `Void <>xLuaBaseProxy_OnUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Common.UnifiedService
public class UnifiedServiceNetCoreTCP : UnifiedServiceNetCore, INetMsgProcessor, IHotfixable
{
	private SocketNet m_socket; // 0x20
	private ProtocolRegistry m_protocolSuite; // 0x28
	private Dictionary`2 m_cmdProcessors; // 0x30
	private Action`1 <msgParseErrListener>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_msgParseErrListener; // 0x0
	private static DelegateBridge __Hotfix0_set_msgParseErrListener; // 0x8
	private static DelegateBridge __Hotfix0_OnConnectTo; // 0x10
	private static DelegateBridge __Hotfix0_OnDisConnect; // 0x18
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x20
	private static DelegateBridge __Hotfix0__NetStateChanged; // 0x28
	private static DelegateBridge __Hotfix0_RegisterProtocol; // 0x30
	private static DelegateBridge __Hotfix0_SetCmdProcessor; // 0x38
	private static DelegateBridge __Hotfix0_ProcMsg; // 0x40
	private static DelegateBridge __Hotfix0__ProcMsg; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action`1 msgParseErrListener { get; set; }

	// RVA: 0x3728ec0 VA: 0x7595d40ec0
	private Action`1 get_msgParseErrListener() { }
	// RVA: 0x3728f28 VA: 0x7595d40f28
	public Void set_msgParseErrListener(Action`1 value) { }
	// RVA: 0x3728fac VA: 0x7595d40fac
	protected override Void OnConnectTo(String host, Int32 port) { }
	// RVA: 0x3729120 VA: 0x7595d41120
	protected override Void OnDisConnect() { }
	// RVA: 0x37291a0 VA: 0x7595d411a0
	protected override Void OnUpdate() { }
	// RVA: 0x372921c VA: 0x7595d4121c
	private Void _NetStateChanged(ConnectionState state) { }
	// RVA: 0x VA: 0x0
	public Void RegisterProtocol() { }
	// RVA: 0x VA: 0x0
	public Void SetCmdProcessor(NetMsgID id, ProtocolProcFunc`1 procFunc) { }
	// RVA: 0x37292c0 VA: 0x7595d412c0
	public Boolean ProcMsg(NetMsg msg) { }
	// RVA: 0x37294bc VA: 0x7595d414bc
	private Boolean _ProcMsg(Protocol protocol) { }
	// RVA: 0x3729604 VA: 0x7595d41604
	public Void .ctor() { }
	// RVA: 0x37296b0 VA: 0x7595d416b0
	private Void <>xLuaBaseProxy_OnUpdate() { }
}
```