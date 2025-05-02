# ZoneRecordGroupViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String zoneId`

- `Int32 m_currentIdx`

- `ZoneRecordUnlockData unlockData`

- `Boolean unlocked`


## Properties

- `Int32 currentRecordIdx`


## Methods

- `Int32 get_currentRecordIdx()`

- `Void set_currentRecordIdx(Int32)`

- `ZoneRecordViewModel GetCurrentRecordViewModel()`

- `Boolean CheckAvailableReward(ref)`

- `DiffRewardStatus GetRewardStatus(StageDiffGroup)`

- `ZoneRecordViewModel GetZoneRecordById(String, out)`

- `Boolean _CheckRecordRewardNeedComplete(String)`

- `Boolean _CheckRecordAvailable(String)`

- `Boolean _CheckUnlock(ZoneRecordUnlockData)`

- `Void _TryUpdateRewardStatus(ZoneRecordViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordGroupViewModel : IHotfixable
{
	public String zoneId; // 0x10
	protected Int32 m_currentIdx; // 0x18
	protected Dictionary`2 recordAvaiDict; // 0x20
	public List`1 recordList; // 0x28
	public ZoneRecordUnlockData unlockData; // 0x30
	public Boolean unlocked; // 0x38
	public Dictionary`2 rewardStatusDict; // 0x40
	private static DelegateBridge __Hotfix0_get_currentRecordIdx; // 0x0
	private static DelegateBridge __Hotfix0_set_currentRecordIdx; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_GetCurrentRecordViewModel; // 0x18
	private static DelegateBridge __Hotfix0_CheckAvailableReward; // 0x20
	private static DelegateBridge __Hotfix0_GetRewardStatus; // 0x28
	private static DelegateBridge __Hotfix0_GetZoneRecordById; // 0x30
	private static DelegateBridge __Hotfix0__CheckRecordRewardNeedComplete; // 0x38
	private static DelegateBridge __Hotfix0__CheckRecordAvailable; // 0x40
	private static DelegateBridge __Hotfix0__CheckUnlock; // 0x48
	private static DelegateBridge __Hotfix0__TryUpdateRewardStatus; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Int32 currentRecordIdx { get; set; }

	// RVA: 0x2fc4d80 VA: 0x75955dcd80
	public Int32 get_currentRecordIdx() { }
	// RVA: 0x2fc4de8 VA: 0x75955dcde8
	public Void set_currentRecordIdx(Int32 value) { }
	// RVA: 0x2fc4e64 VA: 0x75955dce64
	public virtual Void LoadData(ZoneRecordGroupData groupData) { }
	// RVA: 0x2fc5d30 VA: 0x75955ddd30
	public ZoneRecordViewModel GetCurrentRecordViewModel() { }
	// RVA: 0x2fc5dfc VA: 0x75955dddfc
	public Boolean CheckAvailableReward(ref String[] stageIds) { }
	// RVA: 0x2fc60dc VA: 0x75955de0dc
	public DiffRewardStatus GetRewardStatus(StageDiffGroup stageDiff) { }
	// RVA: 0x2fc61a0 VA: 0x75955de1a0
	public ZoneRecordViewModel GetZoneRecordById(String recordId, out Int32 index) { }
	// RVA: 0x2fc5b78 VA: 0x75955ddb78
	protected Boolean _CheckRecordRewardNeedComplete(String prevRecordId) { }
	// RVA: 0x2fc5a9c VA: 0x75955dda9c
	protected Boolean _CheckRecordAvailable(String recordId) { }
	// RVA: 0x2fc5c78 VA: 0x75955ddc78
	protected Boolean _CheckUnlock(ZoneRecordUnlockData unlockData) { }
	// RVA: 0x2fc58c4 VA: 0x75955dd8c4
	protected Void _TryUpdateRewardStatus(ZoneRecordViewModel recordViewModel) { }
	// RVA: 0x2fc62c8 VA: 0x75955de2c8
	public Void .ctor() { }
}
```