# ActMultiV3MatchModeDiffModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String m_requireModeId`

- `Int32 m_requireModeStarCount`

- `String m_actId`

- `ActMultiV3MapDiffType <diffType>k__BackingField`

- `String <diffName>k__BackingField`

- `String <modeId>k__BackingField`

- `Boolean <isUnlock>k__BackingField`

- `String <unlockHint>k__BackingField`

- `Boolean <isDefaultSelect>k__BackingField`


## Properties

- `ActMultiV3MapDiffType diffType`

- `String diffName`

- `String modeId`

- `Boolean isUnlock`

- `String unlockHint`

- `Boolean isDefaultSelect`


## Methods

- `ActMultiV3MapDiffType get_diffType()`

- `Void set_diffType(ActMultiV3MapDiffType)`

- `String get_diffName()`

- `Void set_diffName(String)`

- `String get_modeId()`

- `Void set_modeId(String)`

- `Boolean get_isUnlock()`

- `Void set_isUnlock(Boolean)`

- `String get_unlockHint()`

- `Void set_unlockHint(String)`

- `Boolean get_isDefaultSelect()`

- `Void set_isDefaultSelect(Boolean)`

- `ActMultiV3MatchMapModel GetTrainingMapModel()`

- `Boolean FindNearestLockStage(Int64, out)`

- `Boolean CheckIfEmpty(Int64)`

- `Int32 CalcCurrStarCount()`

- `Int32 CalcTotalStarCount(Int64)`

- `Int64 CalcMaxScore()`

- `Boolean CheckIfHasNewTrack()`

- `Void LoadData(String, ActMultiV3Data, ActMultiV3MapTypeData)`

- `Void UpdatePlayerData()`

- `Void UpdateUnlockStatus(ActMultiV3QuickMatchModel)`

- `Int32 CalcCountOfMapWithStar(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MatchModeDiffModel : IHotfixable
{
	private List`1 m_mapList; // 0x10
	private String m_requireModeId; // 0x18
	private Int32 m_requireModeStarCount; // 0x20
	private String m_actId; // 0x28
	private ActMultiV3MapDiffType <diffType>k__BackingField; // 0x30
	private String <diffName>k__BackingField; // 0x38
	private String <modeId>k__BackingField; // 0x40
	private Boolean <isUnlock>k__BackingField; // 0x48
	private String <unlockHint>k__BackingField; // 0x50
	private Boolean <isDefaultSelect>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_diffType; // 0x0
	private static DelegateBridge __Hotfix0_set_diffType; // 0x8
	private static DelegateBridge __Hotfix0_get_diffName; // 0x10
	private static DelegateBridge __Hotfix0_set_diffName; // 0x18
	private static DelegateBridge __Hotfix0_get_modeId; // 0x20
	private static DelegateBridge __Hotfix0_set_modeId; // 0x28
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x30
	private static DelegateBridge __Hotfix0_set_isUnlock; // 0x38
	private static DelegateBridge __Hotfix0_get_unlockHint; // 0x40
	private static DelegateBridge __Hotfix0_set_unlockHint; // 0x48
	private static DelegateBridge __Hotfix0_get_isDefaultSelect; // 0x50
	private static DelegateBridge __Hotfix0_set_isDefaultSelect; // 0x58
	private static DelegateBridge __Hotfix0_GetTrainingMapModel; // 0x60
	private static DelegateBridge __Hotfix0_FindNearestLockStage; // 0x68
	private static DelegateBridge __Hotfix0_CheckIfEmpty; // 0x70
	private static DelegateBridge __Hotfix0_CalcCurrStarCount; // 0x78
	private static DelegateBridge __Hotfix0_CalcTotalStarCount; // 0x80
	private static DelegateBridge __Hotfix0_CalcMaxScore; // 0x88
	private static DelegateBridge __Hotfix0_CheckIfHasNewTrack; // 0x90
	private static DelegateBridge __Hotfix0_LoadData; // 0x98
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0xa0
	private static DelegateBridge __Hotfix0_UpdateUnlockStatus; // 0xa8
	private static DelegateBridge __Hotfix0_CalcCountOfMapWithStar; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public ActMultiV3MapDiffType diffType { get; set; }
	public String diffName { get; set; }
	public String modeId { get; set; }
	public Boolean isUnlock { get; set; }
	public String unlockHint { get; set; }
	public Boolean isDefaultSelect { get; set; }

	// RVA: 0x3133728 VA: 0x759574b728
	public ActMultiV3MapDiffType get_diffType() { }
	// RVA: 0x3133d78 VA: 0x759574bd78
	private Void set_diffType(ActMultiV3MapDiffType value) { }
	// RVA: 0x3133df4 VA: 0x759574bdf4
	public String get_diffName() { }
	// RVA: 0x3133e5c VA: 0x759574be5c
	private Void set_diffName(String value) { }
	// RVA: 0x31322e0 VA: 0x759574a2e0
	public String get_modeId() { }
	// RVA: 0x3133ee0 VA: 0x759574bee0
	private Void set_modeId(String value) { }
	// RVA: 0x3132278 VA: 0x759574a278
	public Boolean get_isUnlock() { }
	// RVA: 0x3133f64 VA: 0x759574bf64
	private Void set_isUnlock(Boolean value) { }
	// RVA: 0x3133fe4 VA: 0x759574bfe4
	public String get_unlockHint() { }
	// RVA: 0x313404c VA: 0x759574c04c
	private Void set_unlockHint(String value) { }
	// RVA: 0x3133790 VA: 0x759574b790
	public Boolean get_isDefaultSelect() { }
	// RVA: 0x31340d0 VA: 0x759574c0d0
	private Void set_isDefaultSelect(Boolean value) { }
	// RVA: 0x3134150 VA: 0x759574c150
	public ActMultiV3MatchMapModel GetTrainingMapModel() { }
	// RVA: 0x31334b0 VA: 0x759574b4b0
	public Boolean FindNearestLockStage(Int64 currTs, out Int64 nearestTs) { }
	// RVA: 0x312f648 VA: 0x7595747648
	public Boolean CheckIfEmpty(Int64 currTs) { }
	// RVA: 0x3131af4 VA: 0x7595749af4
	public Int32 CalcCurrStarCount() { }
	// RVA: 0x313434c VA: 0x759574c34c
	public Int32 CalcTotalStarCount(Int64 currTs) { }
	// RVA: 0x31344d8 VA: 0x759574c4d8
	public Int64 CalcMaxScore() { }
	// RVA: 0x313465c VA: 0x759574c65c
	public Boolean CheckIfHasNewTrack() { }
	// RVA: 0x31338bc VA: 0x759574b8bc
	public Void LoadData(String actId, ActMultiV3Data actData, ActMultiV3MapTypeData mapTypeData) { }
	// RVA: 0x3133bbc VA: 0x759574bbbc
	public Void UpdatePlayerData() { }
	// RVA: 0x3133ca4 VA: 0x759574bca4
	public Void UpdateUnlockStatus(ActMultiV3QuickMatchModel matchModel) { }
	// RVA: 0x3132ee0 VA: 0x759574aee0
	public Int32 CalcCountOfMapWithStar(Int32 requireMapStar) { }
	// RVA: 0x31337f8 VA: 0x759574b7f8
	public Void .ctor() { }
}
```