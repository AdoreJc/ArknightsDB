# SandboxV2BattleStartResponse

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean isEnemyRush`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BattleStartResponse : CommonStartBattleResponse
{
	public Boolean isEnemyRush; // 0x38
	public List`1 extraRunes; // 0x40
	public List`1 lureInsect; // 0x48
	public Dictionary`2 shinyAnimals; // 0x50
	public List`1 shinyUniEnemy; // 0x58


	// RVA: 0x26065b4 VA: 0x7594c1e5b4
	public override Int32 GetApFailReturn() { }
	// RVA: 0x26065bc VA: 0x7594c1e5bc
	public override Boolean GetInApProtectPeriod() { }
	// RVA: 0x26065c4 VA: 0x7594c1e5c4
	public override Boolean GetIsApProtect() { }
	// RVA: 0x26065cc VA: 0x7594c1e5cc
	public override Boolean GetNotifyPowerScoreNotEnoughIfFailed() { }
	// RVA: 0x26065d4 VA: 0x7594c1e5d4
	public Void .ctor() { }
}
```