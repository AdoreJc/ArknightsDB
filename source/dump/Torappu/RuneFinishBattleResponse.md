# RuneFinishBattleResponse

**Namespace:** `Torappu`


## Fields

- `Int32 score`

- `Int32 from`

- `Int32 to`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RuneFinishBattleResponse : CommonFinishBattleResponse
{
	public Int32 score; // 0x68
	public Int32 from; // 0x6c
	public Int32 to; // 0x70


	// RVA: 0x32ccc34 VA: 0x75958e4c34
	public override List`1 GetFirstRewards() { }
	// RVA: 0x32ccc3c VA: 0x75958e4c3c
	public override Void GetGoldAndExpScale(out Single goldScale, out Single expScale) { }
	// RVA: 0x32ccc48 VA: 0x75958e4c48
	public override String[] GetUnlockStages() { }
	// RVA: 0x32ccc50 VA: 0x75958e4c50
	public override List`1 GetAlert() { }
	// RVA: 0x32ccc58 VA: 0x75958e4c58
	public Void .ctor() { }
}
```