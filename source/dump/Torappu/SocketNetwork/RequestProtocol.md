# RequestProtocol

**Namespace:** `Torappu.SocketNetwork`


## Fields

- `IStreamSerialize m_body`


## Methods

- `Void <>xLuaBaseProxy_OnWrite(IStreamWriter)`

- `String <>xLuaBaseProxy_ToString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SocketNetwork
public class RequestProtocol : Protocol
{
	private IStreamSerialize m_body; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnWrite; // 0x8
	private static DelegateBridge __Hotfix0_ToString; // 0x10


	// RVA: 0x3570668 VA: 0x7595b88668
	public Void .ctor(UInt32 pid, IStreamSerialize body) { }
	// RVA: 0x3570704 VA: 0x7595b88704
	protected override Void OnWrite(IStreamWriter to) { }
	// RVA: 0x357079c VA: 0x7595b8879c
	public override String ToString() { }
	// RVA: 0x3570870 VA: 0x7595b88870
	private Void <>xLuaBaseProxy_OnWrite(IStreamWriter P0) { }
	// RVA: 0x3570874 VA: 0x7595b88874
	private String <>xLuaBaseProxy_ToString() { }
}
```