# SandboxV2RacingBattleFinishViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2.BattleFinish`


## Fields

- `Int32 m_myRacerIdx`

- `String m_myMedalId`

- `Boolean <isValid>k__BackingField`

- `String <topicId>k__BackingField`

- `String <nodeId>k__BackingField`

- `String <stageName>k__BackingField`

- `Int32 <bestTime>k__BackingField`

- `Boolean <isGiveUp>k__BackingField`

- `Boolean <isNewBestTime>k__BackingField`


## Properties

- `Boolean isValid`

- `String topicId`

- `String nodeId`

- `String stageName`

- `Int32 bestTime`

- `Boolean isGiveUp`

- `Boolean isNewBestTime`

- `Int32 completeTime`

- `Boolean showReward`

- `SandboxV2RacerInfoModel myRacerModel`

- `Single myRacerIdx`

- `Boolean isSelfFirstWin`

- `String myMedalId`


## Methods

- `Boolean get_isValid()`

- `Void set_isValid(Boolean)`

- `String get_topicId()`

- `Void set_topicId(String)`

- `String get_nodeId()`

- `Void set_nodeId(String)`

- `String get_stageName()`

- `Void set_stageName(String)`

- `Int32 get_bestTime()`

- `Void set_bestTime(Int32)`

- `Boolean get_isGiveUp()`

- `Void set_isGiveUp(Boolean)`

- `Boolean get_isNewBestTime()`

- `Void set_isNewBestTime(Boolean)`

- `Int32 get_completeTime()`

- `Boolean get_showReward()`

- `SandboxV2RacerInfoModel get_myRacerModel()`

- `Single get_myRacerIdx()`

- `Boolean get_isSelfFirstWin()`

- `String get_myMedalId()`

- `Boolean IsMyRacer(Int32)`

- `Void LoadData()`

- `Void _InitBasicInfo(SandboxV2RacingBattleFinishResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2.BattleFinish
public class SandboxV2RacingBattleFinishViewModel : IHotfixable
{
	private List`1 m_racerList; // 0x10
	private List`1 m_rewardList; // 0x18
	private Int32 m_myRacerIdx; // 0x20
	private String m_myMedalId; // 0x28
	private Boolean <isValid>k__BackingField; // 0x30
	private String <topicId>k__BackingField; // 0x38
	private String <nodeId>k__BackingField; // 0x40
	private String <stageName>k__BackingField; // 0x48
	private Int32 <bestTime>k__BackingField; // 0x50
	private Boolean <isGiveUp>k__BackingField; // 0x54
	private Boolean <isNewBestTime>k__BackingField; // 0x55
	private static DelegateBridge __Hotfix0_get_isValid; // 0x0
	private static DelegateBridge __Hotfix0_set_isValid; // 0x8
	private static DelegateBridge __Hotfix0_get_topicId; // 0x10
	private static DelegateBridge __Hotfix0_set_topicId; // 0x18
	private static DelegateBridge __Hotfix0_get_nodeId; // 0x20
	private static DelegateBridge __Hotfix0_set_nodeId; // 0x28
	private static DelegateBridge __Hotfix0_get_stageName; // 0x30
	private static DelegateBridge __Hotfix0_set_stageName; // 0x38
	private static DelegateBridge __Hotfix0_get_bestTime; // 0x40
	private static DelegateBridge __Hotfix0_set_bestTime; // 0x48
	private static DelegateBridge __Hotfix0_get_isGiveUp; // 0x50
	private static DelegateBridge __Hotfix0_set_isGiveUp; // 0x58
	private static DelegateBridge __Hotfix0_get_isNewBestTime; // 0x60
	private static DelegateBridge __Hotfix0_set_isNewBestTime; // 0x68
	private static DelegateBridge __Hotfix0_get_completeTime; // 0x70
	private static DelegateBridge __Hotfix0_get_showReward; // 0x78
	private static DelegateBridge __Hotfix0_get_rewardList; // 0x80
	private static DelegateBridge __Hotfix0_get_myRacerModel; // 0x88
	private static DelegateBridge __Hotfix0_get_myRacerIdx; // 0x90
	private static DelegateBridge __Hotfix0_get_isSelfFirstWin; // 0x98
	private static DelegateBridge __Hotfix0_get_myMedalId; // 0xa0
	private static DelegateBridge __Hotfix0_get_racerList; // 0xa8
	private static DelegateBridge __Hotfix0_IsMyRacer; // 0xb0
	private static DelegateBridge __Hotfix0_LoadData; // 0xb8
	private static DelegateBridge __Hotfix0__InitBasicInfo; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public Boolean isValid { get; set; }
	public String topicId { get; set; }
	public String nodeId { get; set; }
	public String stageName { get; set; }
	public Int32 bestTime { get; set; }
	public Boolean isGiveUp { get; set; }
	public Boolean isNewBestTime { get; set; }
	public Int32 completeTime { get; }
	public Boolean showReward { get; }
	public List`1 rewardList { get; }
	public SandboxV2RacerInfoModel myRacerModel { get; }
	public Single myRacerIdx { get; }
	public Boolean isSelfFirstWin { get; }
	public String myMedalId { get; }
	public List`1 racerList { get; }

	// RVA: 0x262aa98 VA: 0x7594c42a98
	public Boolean get_isValid() { }
	// RVA: 0x262c6f4 VA: 0x7594c446f4
	private Void set_isValid(Boolean value) { }
	// RVA: 0x262ba30 VA: 0x7594c43a30
	public String get_topicId() { }
	// RVA: 0x262c774 VA: 0x7594c44774
	private Void set_topicId(String value) { }
	// RVA: 0x262c7f8 VA: 0x7594c447f8
	public String get_nodeId() { }
	// RVA: 0x262c860 VA: 0x7594c44860
	private Void set_nodeId(String value) { }
	// RVA: 0x262b494 VA: 0x7594c43494
	public String get_stageName() { }
	// RVA: 0x262c8e4 VA: 0x7594c448e4
	private Void set_stageName(String value) { }
	// RVA: 0x262b59c VA: 0x7594c4359c
	public Int32 get_bestTime() { }
	// RVA: 0x262c968 VA: 0x7594c44968
	private Void set_bestTime(Int32 value) { }
	// RVA: 0x262ab00 VA: 0x7594c42b00
	public Boolean get_isGiveUp() { }
	// RVA: 0x262c9e4 VA: 0x7594c449e4
	private Void set_isGiveUp(Boolean value) { }
	// RVA: 0x262b604 VA: 0x7594c43604
	public Boolean get_isNewBestTime() { }
	// RVA: 0x262ca64 VA: 0x7594c44a64
	private Void set_isNewBestTime(Boolean value) { }
	// RVA: 0x262b4fc VA: 0x7594c434fc
	public Int32 get_completeTime() { }
	// RVA: 0x262b79c VA: 0x7594c4379c
	public Boolean get_showReward() { }
	// RVA: 0x262b898 VA: 0x7594c43898
	public List`1 get_rewardList() { }
	// RVA: 0x262b40c VA: 0x7594c4340c
	public SandboxV2RacerInfoModel get_myRacerModel() { }
	// RVA: 0x262b3a0 VA: 0x7594c433a0
	public Single get_myRacerIdx() { }
	// RVA: 0x262b984 VA: 0x7594c43984
	public Boolean get_isSelfFirstWin() { }
	// RVA: 0x262ba98 VA: 0x7594c43a98
	public String get_myMedalId() { }
	// RVA: 0x262b338 VA: 0x7594c43338
	public List`1 get_racerList() { }
	// RVA: 0x262b66c VA: 0x7594c4366c
	public Boolean IsMyRacer(Int32 racerIdx) { }
	// RVA: 0x262a6a8 VA: 0x7594c426a8
	public Void LoadData() { }
	// RVA: 0x262cae4 VA: 0x7594c44ae4
	private Void _InitBasicInfo(SandboxV2RacingBattleFinishResponse finishResponse) { }
	// RVA: 0x262bc14 VA: 0x7594c43c14
	public Void .ctor() { }
}
```