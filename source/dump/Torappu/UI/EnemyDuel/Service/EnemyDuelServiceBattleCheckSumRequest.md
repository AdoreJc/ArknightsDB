# EnemyDuelServiceBattleCheckSumRequest

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `Int32 seq`

- `UInt32 checkSum`


## Methods

- `Void <>xLuaBaseProxy_Write(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServiceBattleCheckSumRequest : EnemyDuelServiceBattleRequest
{
	public Int32 seq; // 0x10
	public UInt32 checkSum; // 0x14
	private static DelegateBridge __Hotfix0_get_requestID; // 0x0
	private static DelegateBridge __Hotfix0_Write; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override EnemyDuelServiceRequestID requestID { get; }

	// RVA: 0x29a873c VA: 0x7594fc073c
	public override EnemyDuelServiceRequestID get_requestID() { }
	// RVA: 0x29a87a4 VA: 0x7594fc07a4
	public override Void Write(IStreamWriter to) { }
	// RVA: 0x29a88fc VA: 0x7594fc08fc
	public Void .ctor() { }
	// RVA: 0x29a8968 VA: 0x7594fc0968
	private Void <>xLuaBaseProxy_Write(IStreamWriter P0) { }
}
```