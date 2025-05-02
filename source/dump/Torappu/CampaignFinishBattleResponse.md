# CampaignFinishBattleResponse

**Namespace:** `Torappu`


## Fields

- `Int32 currentFeeBefore`

- `Int32 currentFeeAfter`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CampaignFinishBattleResponse : CommonFinishBattleResponse
{
	public Int32 currentFeeBefore; // 0x68
	public Int32 currentFeeAfter; // 0x6c
	public String[] unlockStages; // 0x70
	public List`1 alert; // 0x78


	// RVA: 0x32ca010 VA: 0x75958e2010
	public override Void GetGoldAndExpScale(out Single goldScale, out Single expScale) { }
	// RVA: 0x32ca020 VA: 0x75958e2020
	public override List`1 GetFirstRewards() { }
	// RVA: 0x32ca028 VA: 0x75958e2028
	public override String[] GetUnlockStages() { }
	// RVA: 0x32ca030 VA: 0x75958e2030
	public override List`1 GetAlert() { }
	// RVA: 0x32ca038 VA: 0x75958e2038
	public Void .ctor() { }
}
```