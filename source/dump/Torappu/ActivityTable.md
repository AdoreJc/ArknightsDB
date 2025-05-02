# ActivityTable

**Namespace:** `Torappu`


## Fields

- `ActivityDetailTable activity`

- `ActivityExtraData extraData`

- `AprilFoolTable actFunData`

- `CartData carData`

- `SiracusaData siracusaData`

- `FireworkData fireworkData`

- `FifthAnnivExploreData fifthAnnivExploreData`


## Methods

- `Boolean ShouldSerializeactFunData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActivityTable
{
	public Dictionary`2 basicInfo; // 0x10
	public Dictionary`2 homeActConfig; // 0x18
	public Dictionary`2 zoneToActivity; // 0x20
	public Dictionary`2 actTimeTrackPoint; // 0x28
	public List`1 missionData; // 0x30
	public List`1 missionGroup; // 0x38
	public Dictionary`2 replicateMissions; // 0x40
	public ActivityDetailTable activity; // 0x48
	public ActivityExtraData extraData; // 0x50
	public Dictionary`2 activityItems; // 0x58
	public ListDict`2 syncPoints; // 0x60
	public Dictionary`2 dynActs; // 0x68
	public Dictionary`2 stageRewardsData; // 0x70
	public List`1 actThemes; // 0x78
	public AprilFoolTable actFunData; // 0x80
	public CartData carData; // 0x88
	public SiracusaData siracusaData; // 0x90
	public FireworkData fireworkData; // 0x98
	public Dictionary`2 kvSwitchData; // 0xa0
	public Dictionary`2 dynEntrySwitchData; // 0xa8
	public List`1 hiddenStageData; // 0xb0
	public Dictionary`2 missionArchives; // 0xb8
	public FifthAnnivExploreData fifthAnnivExploreData; // 0xc0
	public Dictionary`2 stringRes; // 0xc8
	public Dictionary`2 activityTraps; // 0xd0
	public Dictionary`2 activityTrapMissions; // 0xd8
	public Dictionary`2 trapRuneDataDict; // 0xe0
	public Dictionary`2 activityTemplateMissionStyles; // 0xe8
	public Dictionary`2 activityCrossDayTrackTypeDataDict; // 0xf0
	public Dictionary`2 activityCrossDayTrackTypeMap; // 0xf8


	// RVA: 0x33bcea8 VA: 0x75959d4ea8
	public virtual Boolean ShouldSerializeactThemes() { }
	// RVA: 0x33bceb0 VA: 0x75959d4eb0
	public Boolean ShouldSerializeactFunData() { }
	// RVA: 0x33bcf0c VA: 0x75959d4f0c
	public virtual Boolean ShouldSerializefireworkData() { }
	// RVA: 0x33bcf1c VA: 0x75959d4f1c
	public Void .ctor() { }
}
```