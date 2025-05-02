# EnemyDuelServiceTeamGetNameCardRequest

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `String uid`


## Methods

- `Void <>xLuaBaseProxy_Write(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServiceTeamGetNameCardRequest : EnemyDuelServiceTeamRequest
{
	public String uid; // 0x10
	private static DelegateBridge __Hotfix0_get_requestID; // 0x0
	private static DelegateBridge __Hotfix0_Write; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override EnemyDuelServiceRequestID requestID { get; }

	// RVA: 0x29a77e8 VA: 0x7594fbf7e8
	public override EnemyDuelServiceRequestID get_requestID() { }
	// RVA: 0x29a7850 VA: 0x7594fbf850
	public override Void Write(IStreamWriter to) { }
	// RVA: 0x29a3ea4 VA: 0x7594fbbea4
	public Void .ctor() { }
	// RVA: 0x29a7944 VA: 0x7594fbf944
	private Void <>xLuaBaseProxy_Write(IStreamWriter P0) { }
}
```