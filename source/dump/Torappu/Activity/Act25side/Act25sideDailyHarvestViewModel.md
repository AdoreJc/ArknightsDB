# Act25sideDailyHarvestViewModel

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `String activityId`

- `Int32 m_rewardCnt`

- `Int32 m_rewardLimit`

- `DailyHarvest m_dailyHarvest`


## Properties

- `Int32 harvestRewardCnt`

- `DailyHarvest dailyHarvest`

- `Int64 nearestHarvestTimeSecs`

- `Int64 nearestHarvestTimestamp`

- `Boolean rewardMax`


## Methods

- `Int32 get_harvestRewardCnt()`

- `DailyHarvest get_dailyHarvest()`

- `Int64 get_nearestHarvestTimeSecs()`

- `Int64 get_nearestHarvestTimestamp()`

- `Boolean get_rewardMax()`

- `Int64 _CalNearestHarvestTimeSecs()`

- `Int64 _CalNearestHarvestTimestamp()`

- `Void LoadData(String)`

- `Void _CalculateReward(DailyHarvest)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideDailyHarvestViewModel : IHotfixable
{
	public String activityId; // 0x10
	private Int32 m_rewardCnt; // 0x18
	private Int32 m_rewardLimit; // 0x1c
	private DailyHarvest m_dailyHarvest; // 0x20
	private static DelegateBridge __Hotfix0_get_harvestRewardCnt; // 0x0
	private static DelegateBridge __Hotfix0_get_dailyHarvest; // 0x8
	private static DelegateBridge __Hotfix0_get_nearestHarvestTimeSecs; // 0x10
	private static DelegateBridge __Hotfix0_get_nearestHarvestTimestamp; // 0x18
	private static DelegateBridge __Hotfix0_get_rewardMax; // 0x20
	private static DelegateBridge __Hotfix0__CalNearestHarvestTimeSecs; // 0x28
	private static DelegateBridge __Hotfix0__CalNearestHarvestTimestamp; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0__CalculateReward; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int32 harvestRewardCnt { get; }
	public DailyHarvest dailyHarvest { get; }
	public Int64 nearestHarvestTimeSecs { get; }
	public Int64 nearestHarvestTimestamp { get; }
	public Boolean rewardMax { get; }

	// RVA: 0x3278568 VA: 0x7595890568
	public Int32 get_harvestRewardCnt() { }
	// RVA: 0x327e188 VA: 0x7595896188
	public DailyHarvest get_dailyHarvest() { }
	// RVA: 0x32807e8 VA: 0x75958987e8
	public Int64 get_nearestHarvestTimeSecs() { }
	// RVA: 0x3286ac4 VA: 0x759589eac4
	public Int64 get_nearestHarvestTimestamp() { }
	// RVA: 0x328156c VA: 0x759589956c
	public Boolean get_rewardMax() { }
	// RVA: 0x32869b4 VA: 0x759589e9b4
	private Int64 _CalNearestHarvestTimeSecs() { }
	// RVA: 0x3286b2c VA: 0x759589eb2c
	private Int64 _CalNearestHarvestTimestamp() { }
	// RVA: 0x3277a18 VA: 0x759588fa18
	public Void LoadData(String actId) { }
	// RVA: 0x3286c3c VA: 0x759589ec3c
	private Void _CalculateReward(DailyHarvest harvestData) { }
	// RVA: 0x3286d68 VA: 0x759589ed68
	public Void .ctor() { }
}
```