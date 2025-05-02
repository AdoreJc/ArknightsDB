# CampaignTable

**Namespace:** `Torappu`


## Fields

- `CampaignConstTable campaignConstTable`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CampaignTable
{
	public Dictionary`2 campaigns; // 0x10
	public Dictionary`2 campaignGroups; // 0x18
	public Dictionary`2 campaignRegions; // 0x20
	public Dictionary`2 campaignZones; // 0x28
	public Dictionary`2 campaignMissions; // 0x30
	public Dictionary`2 stageIndexInZoneMap; // 0x38
	public CampaignConstTable campaignConstTable; // 0x40
	public List`1 campaignRotateStageOpenTimes; // 0x48
	public List`1 campaignTrainingStageOpenTimes; // 0x50
	public List`1 campaignTrainingAllOpenTimes; // 0x58


	// RVA: 0x33c830c VA: 0x75959e030c
	public Void .ctor() { }
}
```