# TeamJoinDn

**Namespace:** ` `


## Fields

- `EnemyDuelProtocolRetCode retCode`

- `String reason`

- `Int64 svrTime`


## Methods

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TeamJoinDn : Protocol
{
	public const Int32 ID; // 0x0
	public EnemyDuelProtocolRetCode retCode; // 0x14
	public String reason; // 0x18
	public Int64 svrTime; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnRead; // 0x8


	// RVA: 0x29b4bcc VA: 0x7594fccbcc
	public Void .ctor() { }
	// RVA: 0x29b4c40 VA: 0x7594fccc40
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x29b4e00 VA: 0x7594fcce00
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```