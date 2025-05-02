# SandboxV2DungeonGameflowViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean isRift`

- `Boolean isGuide`

- `Boolean isChallenge`

- `GameState state`

- `Int32 day`

- `Int32 maxDay`

- `Int32 currAp`

- `Int32 maxAp`

- `SandboxV2SeasonType currSeason`

- `Int32 currSeasonRemainDays`

- `Int32 daysBeforeAssessment`

- `Int32 basementLevel`

- `Int32 basementMaxLevel`

- `Boolean basementCanUpgrade`

- `Boolean portableConstructUnlocked`

- `Boolean outpostConstructUnlocked`

- `Boolean shopUnlocked`

- `Boolean isSettleDay`

- `Boolean isRiftReserved`

- `RiftGameStatus riftStatus`

- `Int64 readArchiveTs`

- `Boolean supplyUnlocked`

- `Boolean supplyActive`

- `Boolean isRiftMainFail`

- `Boolean isRiftMainFinish`

- `String currSeasonName`

- `String currSeasonColor`

- `String currSeasonDesc`

- `String currSeasonFunctionDesc`

- `ChallengeStatus challengeStatus`


## Methods

- `Void UpdateData(UpdateParam)`

- `Int32 _GenBasementMaxLevel(UpdateParam)`

- `Boolean _CheckBasementUpgrade(UpdateParam)`

- `Void _LoadSeasonData(SandboxV2SeasonType, SandboxV2Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonGameflowViewModel : IHotfixable
{
	public Boolean isRift; // 0x10
	public Boolean isGuide; // 0x11
	public Boolean isChallenge; // 0x12
	public GameState state; // 0x14
	public Int32 day; // 0x18
	public Int32 maxDay; // 0x1c
	public Int32 currAp; // 0x20
	public Int32 maxAp; // 0x24
	public SandboxV2SeasonType currSeason; // 0x28
	public Int32 currSeasonRemainDays; // 0x2c
	public Int32 daysBeforeAssessment; // 0x30
	public Int32 basementLevel; // 0x34
	public Int32 basementMaxLevel; // 0x38
	public Boolean basementCanUpgrade; // 0x3c
	public Boolean portableConstructUnlocked; // 0x3d
	public Boolean outpostConstructUnlocked; // 0x3e
	public Boolean shopUnlocked; // 0x3f
	public Boolean isSettleDay; // 0x40
	public Boolean isRiftReserved; // 0x41
	public RiftGameStatus riftStatus; // 0x44
	public Dictionary`2 playerTrapDeployLimit; // 0x48
	public Int64 readArchiveTs; // 0x50
	public Boolean supplyUnlocked; // 0x58
	public Boolean supplyActive; // 0x59
	public Boolean isRiftMainFail; // 0x5a
	public Boolean isRiftMainFinish; // 0x5b
	public String currSeasonName; // 0x60
	public String currSeasonColor; // 0x68
	public String currSeasonDesc; // 0x70
	public String currSeasonFunctionDesc; // 0x78
	public ChallengeStatus challengeStatus; // 0x80
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge __Hotfix0__GenBasementMaxLevel; // 0x8
	private static DelegateBridge __Hotfix0__CheckBasementUpgrade; // 0x10
	private static DelegateBridge __Hotfix0__LoadSeasonData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x25c1d44 VA: 0x7594bd9d44
	public Void UpdateData(UpdateParam updateParam) { }
	// RVA: 0x25c21f8 VA: 0x7594bda1f8
	private Int32 _GenBasementMaxLevel(UpdateParam updateParam) { }
	// RVA: 0x25c2318 VA: 0x7594bda318
	private Boolean _CheckBasementUpgrade(UpdateParam updateParam) { }
	// RVA: 0x25c2528 VA: 0x7594bda528
	private Void _LoadSeasonData(SandboxV2SeasonType currSeason, SandboxV2Data topicDetailData) { }
	// RVA: 0x25c262c VA: 0x7594bda62c
	public Void .ctor() { }
}
```