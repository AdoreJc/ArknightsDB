# ProtocolRegistry

**Namespace:** `Torappu.SocketNetwork`


## Methods

- `T Get()`

- `Protocol Get(NetMsgID)`

- `Protocol _GetProtocol(Int32)`

- `Boolean Register(NetMsgID)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SocketNetwork
public class ProtocolRegistry : INetProtocolSuite, IHotfixable
{
	private readonly List`1 m_creators; // 0x10
	private readonly List`1 m_protocols; // 0x18
	private readonly Dictionary`2 m_idFinder; // 0x20
	private readonly Dictionary`2 m_typeFinder; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Get; // 0x8
	private static DelegateBridge __Hotfix1_Get; // 0x10
	private static DelegateBridge __Hotfix0__GetProtocol; // 0x18
	private static DelegateBridge __Hotfix0_Register; // 0x20


	// RVA: 0x357087c VA: 0x7595b8887c
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public T Get() { }
	// RVA: 0x3570a30 VA: 0x7595b88a30
	public Protocol Get(NetMsgID id) { }
	// RVA: 0x3570aec VA: 0x7595b88aec
	private Protocol _GetProtocol(Int32 idx) { }
	// RVA: 0x VA: 0x0
	public Boolean Register(NetMsgID id) { }
}
```