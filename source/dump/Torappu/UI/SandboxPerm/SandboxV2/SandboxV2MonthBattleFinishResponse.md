# SandboxV2MonthBattleFinishResponse

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean success`

- `Boolean firstPass`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2MonthBattleFinishResponse : CommonFinishBattleResponse
{
	public Boolean success; // 0x68
	public List`1 enemyRushCount; // 0x70
	public Boolean firstPass; // 0x78


	// RVA: 0x2607008 VA: 0x7594c1f008
	public override Void GetGoldAndExpScale(out Single goldScale, out Single expScale) { }
	// RVA: 0x2607014 VA: 0x7594c1f014
	public override List`1 GetFirstRewards() { }
	// RVA: 0x260701c VA: 0x7594c1f01c
	public override String[] GetUnlockStages() { }
	// RVA: 0x2607024 VA: 0x7594c1f024
	public override List`1 GetAlert() { }
	// RVA: 0x260702c VA: 0x7594c1f02c
	public Void .ctor() { }
}
```