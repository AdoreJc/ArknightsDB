# DefaultFinishBattleResponse

**Namespace:** `Torappu`


## Fields

- `Single goldScale`

- `Single expScale`

- `Boolean suggestFriend`

- `FinishBattleResponseExtraData extra`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class DefaultFinishBattleResponse : CommonFinishBattleResponse
{
	public Single goldScale; // 0x68
	public Single expScale; // 0x6c
	public List`1 firstRewards; // 0x70
	public String[] unlockStages; // 0x78
	public List`1 pryResult; // 0x80
	public List`1 alert; // 0x88
	public Boolean suggestFriend; // 0x90
	public FinishBattleResponseExtraData extra; // 0x98


	// RVA: 0x32cb7b0 VA: 0x75958e37b0
	public override Void GetGoldAndExpScale(out Single goldScale, out Single expScale) { }
	// RVA: 0x32cb7c4 VA: 0x75958e37c4
	public override List`1 GetFirstRewards() { }
	// RVA: 0x32cb7cc VA: 0x75958e37cc
	public override List`1 GetPryResults() { }
	// RVA: 0x32cb7d4 VA: 0x75958e37d4
	public override String[] GetUnlockStages() { }
	// RVA: 0x32cb7dc VA: 0x75958e37dc
	public override List`1 GetAlert() { }
	// RVA: 0x32cb76c VA: 0x75958e376c
	public Void .ctor() { }
}
```