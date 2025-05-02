# EnemyDuelServiceBattleEmotionRequest

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `String emojiGroup`

- `String emojiId`


## Methods

- `Void <>xLuaBaseProxy_Write(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServiceBattleEmotionRequest : EnemyDuelServiceBattleRequest
{
	public String emojiGroup; // 0x10
	public String emojiId; // 0x18
	private static DelegateBridge __Hotfix0_get_requestID; // 0x0
	private static DelegateBridge __Hotfix0_Write; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override EnemyDuelServiceRequestID requestID { get; }

	// RVA: 0x29a850c VA: 0x7594fc050c
	public override EnemyDuelServiceRequestID get_requestID() { }
	// RVA: 0x29a8574 VA: 0x7594fc0574
	public override Void Write(IStreamWriter to) { }
	// RVA: 0x29a86cc VA: 0x7594fc06cc
	public Void .ctor() { }
	// RVA: 0x29a8738 VA: 0x7594fc0738
	private Void <>xLuaBaseProxy_Write(IStreamWriter P0) { }
}
```