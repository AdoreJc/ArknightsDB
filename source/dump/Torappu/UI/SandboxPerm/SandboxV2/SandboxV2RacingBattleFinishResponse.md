# SandboxV2RacingBattleFinishResponse

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean giveUp`

- `String myRacer`

- `String myMedalId`

- `Boolean isNewBest`

- `Int32 bestTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacingBattleFinishResponse : CommonFinishBattleResponse
{
	public Boolean giveUp; // 0x68
	public String myRacer; // 0x70
	public String myMedalId; // 0x78
	public List`1 rankList; // 0x80
	public Boolean isNewBest; // 0x88
	public Int32 bestTime; // 0x8c
	public List`1 rewards; // 0x90


	// RVA: 0x2606ea4 VA: 0x7594c1eea4
	public override List`1 GetAlert() { }
	// RVA: 0x2606eac VA: 0x7594c1eeac
	public override List`1 GetFirstRewards() { }
	// RVA: 0x2606eb4 VA: 0x7594c1eeb4
	public override Void GetGoldAndExpScale(out Single goldScale, out Single expScale) { }
	// RVA: 0x2606ec0 VA: 0x7594c1eec0
	public override String[] GetUnlockStages() { }
	// RVA: 0x2606ec8 VA: 0x7594c1eec8
	public Void .ctor() { }
}
```