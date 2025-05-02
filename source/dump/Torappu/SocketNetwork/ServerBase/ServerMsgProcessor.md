# ServerMsgProcessor

**Namespace:** `Torappu.SocketNetwork.ServerBase`


## Fields

- `IServerLogRule <logRule>k__BackingField`


## Properties

- `IServerLogRule logRule`


## Methods

- `IServerLogRule get_logRule()`

- `Void set_logRule(IServerLogRule)`

- `Void set_msgParseErrListener(Action`1)`

- `Boolean ProcMsg(NetMsg)`

- `Boolean ProcMsg(Protocol)`

- `Void Register(NetMsgID, ProtocolHandler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SocketNetwork.ServerBase
public class ServerMsgProcessor : INetMsgProcessor, IHotfixable
{
	private Dictionary`2 m_handles; // 0x10
	private readonly INetProtocolSuite m_protocols; // 0x18
	private IServerLogRule <logRule>k__BackingField; // 0x20
	private Action`1 <msgParseErrListener>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_logRule; // 0x0
	private static DelegateBridge __Hotfix0_set_logRule; // 0x8
	private static DelegateBridge __Hotfix0_get_msgParseErrListener; // 0x10
	private static DelegateBridge __Hotfix0_set_msgParseErrListener; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20
	private static DelegateBridge __Hotfix0_ProcMsg; // 0x28
	private static DelegateBridge __Hotfix1_ProcMsg; // 0x30
	private static DelegateBridge __Hotfix0_Register; // 0x38

	public IServerLogRule logRule { get; set; }
	private Action`1 msgParseErrListener { get; set; }

	// RVA: 0x3573ae4 VA: 0x7595b8bae4
	public IServerLogRule get_logRule() { }
	// RVA: 0x35724c4 VA: 0x7595b8a4c4
	public Void set_logRule(IServerLogRule value) { }
	// RVA: 0x3573b4c VA: 0x7595b8bb4c
	private Action`1 get_msgParseErrListener() { }
	// RVA: 0x3572724 VA: 0x7595b8a724
	public Void set_msgParseErrListener(Action`1 value) { }
	// RVA: 0x3572690 VA: 0x7595b8a690
	public Void .ctor(INetProtocolSuite protocolSuit) { }
	// RVA: 0x3573bb4 VA: 0x7595b8bbb4
	public Boolean ProcMsg(NetMsg msg) { }
	// RVA: 0x3572fd0 VA: 0x7595b8afd0
	public Boolean ProcMsg(Protocol protocol) { }
	// RVA: 0x357355c VA: 0x7595b8b55c
	public Void Register(NetMsgID id, ProtocolHandler handler) { }
}
```