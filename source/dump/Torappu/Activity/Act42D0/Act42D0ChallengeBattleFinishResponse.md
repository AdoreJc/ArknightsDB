# Act42D0ChallengeBattleFinishResponse

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String stageId`

- `Int32 progress`

- `Boolean isNew`

- `Int32 milestoneGot`

- `Int32 milestoneAfter`

- `Int64 finishTs`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0ChallengeBattleFinishResponse : CommonFinishBattleResponse
{
	public String stageId; // 0x68
	public Int32 progress; // 0x70
	public Boolean isNew; // 0x74
	public Int32 milestoneGot; // 0x78
	public Int32 milestoneAfter; // 0x7c
	public Int64 finishTs; // 0x80


	// RVA: 0x3203a84 VA: 0x759581ba84
	public override List`1 GetAlert() { }
	// RVA: 0x3203a8c VA: 0x759581ba8c
	public override List`1 GetFirstRewards() { }
	// RVA: 0x3203a94 VA: 0x759581ba94
	public override Void GetGoldAndExpScale(out Single goldScale, out Single expScale) { }
	// RVA: 0x3203aa0 VA: 0x759581baa0
	public override String[] GetUnlockStages() { }
	// RVA: 0x3203aa8 VA: 0x759581baa8
	public Void .ctor() { }
}
```