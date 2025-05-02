# EnemyDuelServiceBattleBetRequest

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `String id`

- `EnemyDuelChoiceSide side`

- `Boolean isPlayer`

- `Boolean allin`


## Methods

- `Void <>xLuaBaseProxy_Write(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServiceBattleBetRequest : EnemyDuelServiceBattleRequest
{
	public String id; // 0x10
	public EnemyDuelChoiceSide side; // 0x18
	public Boolean isPlayer; // 0x1c
	public Boolean allin; // 0x1d
	private static DelegateBridge __Hotfix0_get_requestID; // 0x0
	private static DelegateBridge __Hotfix0_Write; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override EnemyDuelServiceRequestID requestID { get; }

	// RVA: 0x29a7fd0 VA: 0x7594fbffd0
	public override EnemyDuelServiceRequestID get_requestID() { }
	// RVA: 0x29a8038 VA: 0x7594fc0038
	public override Void Write(IStreamWriter to) { }
	// RVA: 0x29a8258 VA: 0x7594fc0258
	public Void .ctor() { }
	// RVA: 0x29a82c4 VA: 0x7594fc02c4
	private Void <>xLuaBaseProxy_Write(IStreamWriter P0) { }
}
```