# EnemyDuelServiceBattleRoundSettleRequest

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `Int32 side`

- `Boolean finalSettle`


## Methods

- `Void <>xLuaBaseProxy_Write(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServiceBattleRoundSettleRequest : EnemyDuelServiceBattleRequest
{
	public Int32 side; // 0x10
	public Boolean finalSettle; // 0x14
	private static DelegateBridge __Hotfix0_get_requestID; // 0x0
	private static DelegateBridge __Hotfix0_Write; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override EnemyDuelServiceRequestID requestID { get; }

	// RVA: 0x29a82c8 VA: 0x7594fc02c8
	public override EnemyDuelServiceRequestID get_requestID() { }
	// RVA: 0x29a8330 VA: 0x7594fc0330
	public override Void Write(IStreamWriter to) { }
	// RVA: 0x29a83c8 VA: 0x7594fc03c8
	public Void .ctor() { }
	// RVA: 0x29a8434 VA: 0x7594fc0434
	private Void <>xLuaBaseProxy_Write(IStreamWriter P0) { }
}
```