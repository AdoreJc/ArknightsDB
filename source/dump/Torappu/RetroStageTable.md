# RetroStageTable

**Namespace:** `Torappu`


## Fields

- `RetroTrailRuleData ruleData`

- `ActivityCustomData customData`

- `Int32 initRetroCoin`

- `Int32 retroCoinPerWeek`

- `Int32 retroUnlockCost`

- `String retroDetail`

- `Int64 retroPreShowTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RetroStageTable
{
	public ListDict`2 zoneToRetro; // 0x10
	public Dictionary`2 stageValidInfo; // 0x18
	public Dictionary`2 stages; // 0x20
	public Dictionary`2 retroActList; // 0x28
	public Dictionary`2 retroTrailList; // 0x30
	public Dictionary`2 stageList; // 0x38
	public RetroTrailRuleData ruleData; // 0x40
	public ActivityCustomData customData; // 0x48
	public Int32 initRetroCoin; // 0x50
	public Int32 retroCoinPerWeek; // 0x54
	public Dictionary`2 retroCoinMaxOfLevels; // 0x58
	public Int32 retroUnlockCost; // 0x60
	public String retroDetail; // 0x68
	public Int64 retroPreShowTime; // 0x70


	// RVA: 0x34a725c VA: 0x7595abf25c
	public Void .ctor() { }
}
```