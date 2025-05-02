# TCPConnection

**Namespace:** `Torappu.SocketNetwork.Connections`


## Fields

- `Socket m_socket`


## Methods

- `Void _Connected(IAsyncResult)`

- `Void _SendCallback(IAsyncResult)`

- `Void _TryRevData()`

- `Void _Received(IAsyncResult)`

- `Void <>xLuaBaseProxy_OnStart(IPAddress, Int32)`

- `Void <>xLuaBaseProxy_OnStop()`

- `Void <>xLuaBaseProxy_OnTryToSend()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SocketNetwork.Connections
public class TCPConnection : Connection
{
	private Socket m_socket; // 0x48
	private readonly ByteArray m_asyncSendBuff; // 0x50
	private readonly ByteArray m_asyncRevBuff; // 0x58
	private readonly AsyncCallback SendCB; // 0x60
	private readonly AsyncCallback RevCB; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnStart; // 0x8
	private static DelegateBridge __Hotfix0__Connected; // 0x10
	private static DelegateBridge __Hotfix0_OnStop; // 0x18
	private static DelegateBridge __Hotfix0_OnTryToSend; // 0x20
	private static DelegateBridge __Hotfix0__SendCallback; // 0x28
	private static DelegateBridge __Hotfix0__TryRevData; // 0x30
	private static DelegateBridge __Hotfix0__Received; // 0x38


	// RVA: 0x3575f4c VA: 0x7595b8df4c
	public Void .ctor() { }
	// RVA: 0x35760c4 VA: 0x7595b8e0c4
	protected override Void OnStart(IPAddress address, Int32 port) { }
	// RVA: 0x357633c VA: 0x7595b8e33c
	private Void _Connected(IAsyncResult result) { }
	// RVA: 0x35768c8 VA: 0x7595b8e8c8
	protected override Void OnStop() { }
	// RVA: 0x3576a94 VA: 0x7595b8ea94
	protected override Void OnTryToSend() { }
	// RVA: 0x3576e7c VA: 0x7595b8ee7c
	private Void _SendCallback(IAsyncResult result) { }
	// RVA: 0x35766a4 VA: 0x7595b8e6a4
	private Void _TryRevData() { }
	// RVA: 0x3577384 VA: 0x7595b8f384
	private Void _Received(IAsyncResult result) { }
	// RVA: 0x35777a8 VA: 0x7595b8f7a8
	private Void <>xLuaBaseProxy_OnStart(IPAddress P0, Int32 P1) { }
	// RVA: 0x35777ac VA: 0x7595b8f7ac
	private Void <>xLuaBaseProxy_OnStop() { }
	// RVA: 0x35777b0 VA: 0x7595b8f7b0
	private Void <>xLuaBaseProxy_OnTryToSend() { }
}
```