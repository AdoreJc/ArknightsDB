# Act42D0NormalBattleFinishResponse

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String stageId`

- `Int32 ratingLv`

- `Boolean isNew`

- `Int32 milestoneGot`

- `Int32 milestoneAfter`

- `Int64 finishTs`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0NormalBattleFinishResponse : CommonFinishBattleResponse
{
	public String stageId; // 0x68
	public Int32 ratingLv; // 0x70
	public Boolean isNew; // 0x74
	public Int32 milestoneGot; // 0x78
	public Int32 milestoneAfter; // 0x7c
	public List`1 buffs; // 0x80
	public Int64 finishTs; // 0x88


	// RVA: 0x3203974 VA: 0x759581b974
	public override List`1 GetAlert() { }
	// RVA: 0x320397c VA: 0x759581b97c
	public override List`1 GetFirstRewards() { }
	// RVA: 0x3203984 VA: 0x759581b984
	public override String[] GetUnlockStages() { }
	// RVA: 0x320398c VA: 0x759581b98c
	public override Void GetGoldAndExpScale(out Single goldScale, out Single expScale) { }
	// RVA: 0x3203998 VA: 0x759581b998
	public Void .ctor() { }
}
```