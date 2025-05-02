# SandboxV2BattleFinishResponse

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean success`

- `Boolean isEnemyRush`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BattleFinishResponse : CommonFinishBattleResponse
{
	public Boolean success; // 0x68
	public Boolean isEnemyRush; // 0x69
	public List`1 enemyRushCount; // 0x70
	public List`1 rewards; // 0x78
	public List`1 randomRewards; // 0x80


	// RVA: 0x2606ce4 VA: 0x7594c1ece4
	public override List`1 GetAlert() { }
	// RVA: 0x2606cec VA: 0x7594c1ecec
	public override List`1 GetFirstRewards() { }
	// RVA: 0x2606cf4 VA: 0x7594c1ecf4
	public override Void GetGoldAndExpScale(out Single goldScale, out Single expScale) { }
	// RVA: 0x2606d00 VA: 0x7594c1ed00
	public override String[] GetUnlockStages() { }
	// RVA: 0x2606d08 VA: 0x7594c1ed08
	public Void .ctor() { }
}
```