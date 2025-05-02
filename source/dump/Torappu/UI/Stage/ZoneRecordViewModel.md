# ZoneRecordViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String recordId`

- `String recordName`

- `String prevRecordId`

- `Int32 availableCount`

- `Int32 gainedCount`

- `Boolean pageNoteUnlock`

- `Boolean prevRecordNeedComplete`

- `Boolean stageBanned`

- `Boolean prevRecordAvialable`

- `String recordTitle1`

- `String recordTitle2`

- `ZoneRecordDiffStatus diffStatus`

- `Boolean hasRewardCanClaim`

- `RecordDiffIconType btnDiffIconType`


## Properties

- `Boolean isAllComplete`

- `Boolean hasUncomplete`

- `Boolean isUnlock`


## Methods

- `Boolean get_isAllComplete()`

- `Boolean get_hasUncomplete()`

- `Boolean get_isUnlock()`

- `Void LoadData(ZoneRecordData, IPlugin)`

- `Boolean CheckAvailableReward(ref)`

- `Boolean _IsPredefineOrHardRecord(RecordRewardStageDiff)`

- `RecordDiffIconType _GenDiffIconType(ZoneRecordDiffStatus)`

- `ZoneRecordDiffStatus _GenDiffStatus(RecordRewardStageDiff, Boolean)`

- `ZoneRecordRewardViewModel TryGetRewardViewModelByStageDiff(StageDiffGroup)`

- `Boolean _CheckRecordStageValid(String)`

- `Boolean _CheckRewardAvailable(String, Boolean)`

- `Boolean _CheckRewardGained(String)`

- `Boolean _CheckHaveMission(String, out)`

- `RecordRewardInfo _ProcessRewardItem(RecordRewardInfo, IPlugin)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordViewModel : IHotfixable
{
	public String recordId; // 0x10
	public String recordName; // 0x18
	public String prevRecordId; // 0x20
	public Int32 availableCount; // 0x28
	public Int32 gainedCount; // 0x2c
	public Boolean pageNoteUnlock; // 0x30
	public Boolean prevRecordNeedComplete; // 0x31
	public Boolean stageBanned; // 0x32
	public Boolean prevRecordAvialable; // 0x33
	public String recordTitle1; // 0x38
	public String recordTitle2; // 0x40
	public ZoneRecordDiffStatus diffStatus; // 0x48
	public Boolean hasRewardCanClaim; // 0x4c
	public List`1 rewardStatus; // 0x50
	public List`1 rewardViewModels; // 0x58
	public RecordDiffIconType btnDiffIconType; // 0x60
	private static DelegateBridge __Hotfix0_get_isAllComplete; // 0x0
	private static DelegateBridge __Hotfix0_get_hasUncomplete; // 0x8
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_CheckAvailableReward; // 0x20
	private static DelegateBridge __Hotfix0__IsPredefineOrHardRecord; // 0x28
	private static DelegateBridge __Hotfix0__GenDiffIconType; // 0x30
	private static DelegateBridge __Hotfix0__GenDiffStatus; // 0x38
	private static DelegateBridge __Hotfix0_TryGetRewardViewModelByStageDiff; // 0x40
	private static DelegateBridge __Hotfix0__CheckRecordStageValid; // 0x48
	private static DelegateBridge __Hotfix0__CheckRewardAvailable; // 0x50
	private static DelegateBridge __Hotfix0__CheckRewardGained; // 0x58
	private static DelegateBridge __Hotfix0__CheckHaveMission; // 0x60
	private static DelegateBridge __Hotfix0__ProcessRewardItem; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Boolean isAllComplete { get; }
	public Boolean hasUncomplete { get; }
	public Boolean isUnlock { get; }

	// RVA: 0x2fc6434 VA: 0x75955de434
	public Boolean get_isAllComplete() { }
	// RVA: 0x2fc64c4 VA: 0x75955de4c4
	public Boolean get_hasUncomplete() { }
	// RVA: 0x2fc6554 VA: 0x75955de554
	public Boolean get_isUnlock() { }
	// RVA: 0x2fc5460 VA: 0x75955dd460
	public Void LoadData(ZoneRecordData zoneRecord, IPlugin plugin) { }
	// RVA: 0x2fc5e94 VA: 0x75955dde94
	public Boolean CheckAvailableReward(ref String[] stageIds) { }
	// RVA: 0x2fc6e98 VA: 0x75955dee98
	private Boolean _IsPredefineOrHardRecord(RecordRewardStageDiff stageDiff) { }
	// RVA: 0x2fc6f1c VA: 0x75955def1c
	private RecordDiffIconType _GenDiffIconType(ZoneRecordDiffStatus diffStatus) { }
	// RVA: 0x2fc6dd4 VA: 0x75955dedd4
	private ZoneRecordDiffStatus _GenDiffStatus(RecordRewardStageDiff stageDiff, Boolean isUnlock) { }
	// RVA: 0x2fc6fb4 VA: 0x75955defb4
	public ZoneRecordRewardViewModel TryGetRewardViewModelByStageDiff(StageDiffGroup diffType) { }
	// RVA: 0x2fc6d18 VA: 0x75955ded18
	private Boolean _CheckRecordStageValid(String stageId) { }
	// RVA: 0x2fc6acc VA: 0x75955deacc
	private Boolean _CheckRewardAvailable(String stageId, Boolean haveMission) { }
	// RVA: 0x2fc6c08 VA: 0x75955dec08
	private Boolean _CheckRewardGained(String stageId) { }
	// RVA: 0x2fc6974 VA: 0x75955de974
	private Boolean _CheckHaveMission(String stageId, out String desc) { }
	// RVA: 0x2fc6634 VA: 0x75955de634
	private RecordRewardInfo _ProcessRewardItem(RecordRewardInfo prevReward, IPlugin plugin) { }
	// RVA: 0x2fc53f0 VA: 0x75955dd3f0
	public Void .ctor() { }
}
```