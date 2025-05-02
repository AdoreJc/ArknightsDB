# CrisisV2BattleFinishResponse

**Namespace:** `Torappu`


## Fields

- `String mapId`

- `Boolean isNewRecord`

- `Int64 ts`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CrisisV2BattleFinishResponse : CommonFinishBattleResponse
{
	public String mapId; // 0x68
	public List`1 scoreRecord; // 0x70
	public List`1 scoreCurrent; // 0x78
	public Boolean isNewRecord; // 0x80
	public List`1 commentNew; // 0x88
	public List`1 commentOld; // 0x90
	public List`1 runeCount; // 0x98
	public Int64 ts; // 0xa0
	public List`1 runeIds; // 0xa8


	// RVA: 0x32ca4cc VA: 0x75958e24cc
	public override Void GetGoldAndExpScale(out Single goldScale, out Single expScale) { }
	// RVA: 0x32ca4d8 VA: 0x75958e24d8
	public override List`1 GetFirstRewards() { }
	// RVA: 0x32ca4e0 VA: 0x75958e24e0
	public override String[] GetUnlockStages() { }
	// RVA: 0x32ca4e8 VA: 0x75958e24e8
	public override List`1 GetAlert() { }
	// RVA: 0x32ca4f0 VA: 0x75958e24f0
	public Void .ctor() { }
}
```