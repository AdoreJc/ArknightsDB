# EnemyDuelServiceTeamChangeAllowNpcRequest

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `Boolean allowNpc`


## Methods

- `Void <>xLuaBaseProxy_Write(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServiceTeamChangeAllowNpcRequest : EnemyDuelServiceTeamRequest
{
	public Boolean allowNpc; // 0x10
	private static DelegateBridge __Hotfix0_get_requestID; // 0x0
	private static DelegateBridge __Hotfix0_Write; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override EnemyDuelServiceRequestID requestID { get; }

	// RVA: 0x29a7a84 VA: 0x7594fbfa84
	public override EnemyDuelServiceRequestID get_requestID() { }
	// RVA: 0x29a7aec VA: 0x7594fbfaec
	public override Void Write(IStreamWriter to) { }
	// RVA: 0x29a34d8 VA: 0x7594fbb4d8
	public Void .ctor() { }
	// RVA: 0x29a7be0 VA: 0x7594fbfbe0
	private Void <>xLuaBaseProxy_Write(IStreamWriter P0) { }
}
```