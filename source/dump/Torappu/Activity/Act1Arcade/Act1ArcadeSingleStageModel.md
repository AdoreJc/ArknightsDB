# Act1ArcadeSingleStageModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Boolean m_isTimeInvalid`

- `String <actId>k__BackingField`

- `String <stageId>k__BackingField`

- `String <zoneId>k__BackingField`

- `String <code>k__BackingField`

- `String <name>k__BackingField`

- `String <dangerLevel>k__BackingField`

- `String <diffDesc>k__BackingField`

- `String <storyDesc>k__BackingField`

- `String <mechDesc>k__BackingField`

- `Int32 <level>k__BackingField`

- `Int32 <maxSlot>k__BackingField`

- `Int64 <startTs>k__BackingField`

- `StageStatus <stageStatus>k__BackingField`

- `ArcadeStageRankRewardData <rankRewardData>k__BackingField`


## Properties

- `String actId`

- `String stageId`

- `String zoneId`

- `String code`

- `String name`

- `String dangerLevel`

- `String diffDesc`

- `String storyDesc`

- `String mechDesc`

- `Int32 level`

- `Int32 maxSlot`

- `Int64 startTs`

- `StageStatus stageStatus`

- `ArcadeStageRankRewardData rankRewardData`

- `Boolean isUnlock`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `String get_stageId()`

- `Void set_stageId(String)`

- `String get_zoneId()`

- `Void set_zoneId(String)`

- `String get_code()`

- `Void set_code(String)`

- `String get_name()`

- `Void set_name(String)`

- `String get_dangerLevel()`

- `Void set_dangerLevel(String)`

- `String get_diffDesc()`

- `Void set_diffDesc(String)`

- `String get_storyDesc()`

- `Void set_storyDesc(String)`

- `String get_mechDesc()`

- `Void set_mechDesc(String)`

- `Int32 get_level()`

- `Void set_level(Int32)`

- `Int32 get_maxSlot()`

- `Void set_maxSlot(Int32)`

- `Int64 get_startTs()`

- `Void set_startTs(Int64)`

- `StageStatus get_stageStatus()`

- `Void set_stageStatus(StageStatus)`

- `ArcadeStageRankRewardData get_rankRewardData()`

- `Void set_rankRewardData(ArcadeStageRankRewardData)`

- `Boolean get_isUnlock()`

- `Void LoadData(String, ArcadeStageAdditionalData)`

- `Void UpdatePlayerData()`

- `Rank GetRankByScore(Int32)`

- `Rank GetMaxRewardRank()`

- `StageStatus _CalcStageStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSingleStageModel : IHotfixable
{
	private Boolean m_isTimeInvalid; // 0x10
	private String <actId>k__BackingField; // 0x18
	private String <stageId>k__BackingField; // 0x20
	private String <zoneId>k__BackingField; // 0x28
	private String <code>k__BackingField; // 0x30
	private String <name>k__BackingField; // 0x38
	private String <dangerLevel>k__BackingField; // 0x40
	private String <diffDesc>k__BackingField; // 0x48
	private String <storyDesc>k__BackingField; // 0x50
	private String <mechDesc>k__BackingField; // 0x58
	private Int32 <level>k__BackingField; // 0x60
	private Int32 <maxSlot>k__BackingField; // 0x64
	private Int64 <startTs>k__BackingField; // 0x68
	private StageStatus <stageStatus>k__BackingField; // 0x70
	private ArcadeStageRankRewardData <rankRewardData>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_stageId; // 0x10
	private static DelegateBridge __Hotfix0_set_stageId; // 0x18
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x20
	private static DelegateBridge __Hotfix0_set_zoneId; // 0x28
	private static DelegateBridge __Hotfix0_get_code; // 0x30
	private static DelegateBridge __Hotfix0_set_code; // 0x38
	private static DelegateBridge __Hotfix0_get_name; // 0x40
	private static DelegateBridge __Hotfix0_set_name; // 0x48
	private static DelegateBridge __Hotfix0_get_dangerLevel; // 0x50
	private static DelegateBridge __Hotfix0_set_dangerLevel; // 0x58
	private static DelegateBridge __Hotfix0_get_diffDesc; // 0x60
	private static DelegateBridge __Hotfix0_set_diffDesc; // 0x68
	private static DelegateBridge __Hotfix0_get_storyDesc; // 0x70
	private static DelegateBridge __Hotfix0_set_storyDesc; // 0x78
	private static DelegateBridge __Hotfix0_get_mechDesc; // 0x80
	private static DelegateBridge __Hotfix0_set_mechDesc; // 0x88
	private static DelegateBridge __Hotfix0_get_level; // 0x90
	private static DelegateBridge __Hotfix0_set_level; // 0x98
	private static DelegateBridge __Hotfix0_get_maxSlot; // 0xa0
	private static DelegateBridge __Hotfix0_set_maxSlot; // 0xa8
	private static DelegateBridge __Hotfix0_get_startTs; // 0xb0
	private static DelegateBridge __Hotfix0_set_startTs; // 0xb8
	private static DelegateBridge __Hotfix0_get_stageStatus; // 0xc0
	private static DelegateBridge __Hotfix0_set_stageStatus; // 0xc8
	private static DelegateBridge __Hotfix0_get_rankRewardData; // 0xd0
	private static DelegateBridge __Hotfix0_set_rankRewardData; // 0xd8
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0xe0
	private static DelegateBridge __Hotfix0_LoadData; // 0xe8
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0xf0
	private static DelegateBridge __Hotfix0_GetRankByScore; // 0xf8
	private static DelegateBridge __Hotfix0_GetMaxRewardRank; // 0x100
	private static DelegateBridge __Hotfix0__CalcStageStatus; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110

	public String actId { get; set; }
	public String stageId { get; set; }
	public String zoneId { get; set; }
	public String code { get; set; }
	public String name { get; set; }
	public String dangerLevel { get; set; }
	public String diffDesc { get; set; }
	public String storyDesc { get; set; }
	public String mechDesc { get; set; }
	public Int32 level { get; set; }
	public Int32 maxSlot { get; set; }
	public Int64 startTs { get; set; }
	public StageStatus stageStatus { get; set; }
	public ArcadeStageRankRewardData rankRewardData { get; set; }
	public Boolean isUnlock { get; }

	// RVA: 0x340ba24 VA: 0x7595a23a24
	public String get_actId() { }
	// RVA: 0x340ba8c VA: 0x7595a23a8c
	private Void set_actId(String value) { }
	// RVA: 0x340bb10 VA: 0x7595a23b10
	public String get_stageId() { }
	// RVA: 0x340bb78 VA: 0x7595a23b78
	private Void set_stageId(String value) { }
	// RVA: 0x340bbfc VA: 0x7595a23bfc
	public String get_zoneId() { }
	// RVA: 0x340bc64 VA: 0x7595a23c64
	private Void set_zoneId(String value) { }
	// RVA: 0x340bce8 VA: 0x7595a23ce8
	public String get_code() { }
	// RVA: 0x340bd50 VA: 0x7595a23d50
	private Void set_code(String value) { }
	// RVA: 0x340bdd4 VA: 0x7595a23dd4
	public String get_name() { }
	// RVA: 0x340be3c VA: 0x7595a23e3c
	private Void set_name(String value) { }
	// RVA: 0x340bec0 VA: 0x7595a23ec0
	public String get_dangerLevel() { }
	// RVA: 0x340bf28 VA: 0x7595a23f28
	private Void set_dangerLevel(String value) { }
	// RVA: 0x340bfac VA: 0x7595a23fac
	public String get_diffDesc() { }
	// RVA: 0x340c014 VA: 0x7595a24014
	private Void set_diffDesc(String value) { }
	// RVA: 0x340c098 VA: 0x7595a24098
	public String get_storyDesc() { }
	// RVA: 0x340c100 VA: 0x7595a24100
	private Void set_storyDesc(String value) { }
	// RVA: 0x340c184 VA: 0x7595a24184
	public String get_mechDesc() { }
	// RVA: 0x340c1ec VA: 0x7595a241ec
	private Void set_mechDesc(String value) { }
	// RVA: 0x340c270 VA: 0x7595a24270
	public Int32 get_level() { }
	// RVA: 0x340c2d8 VA: 0x7595a242d8
	private Void set_level(Int32 value) { }
	// RVA: 0x340c354 VA: 0x7595a24354
	public Int32 get_maxSlot() { }
	// RVA: 0x340c3bc VA: 0x7595a243bc
	private Void set_maxSlot(Int32 value) { }
	// RVA: 0x340c438 VA: 0x7595a24438
	public Int64 get_startTs() { }
	// RVA: 0x340c4a0 VA: 0x7595a244a0
	private Void set_startTs(Int64 value) { }
	// RVA: 0x340c51c VA: 0x7595a2451c
	public StageStatus get_stageStatus() { }
	// RVA: 0x340c584 VA: 0x7595a24584
	private Void set_stageStatus(StageStatus value) { }
	// RVA: 0x340c600 VA: 0x7595a24600
	public ArcadeStageRankRewardData get_rankRewardData() { }
	// RVA: 0x340c668 VA: 0x7595a24668
	private Void set_rankRewardData(ArcadeStageRankRewardData value) { }
	// RVA: 0x340c6ec VA: 0x7595a246ec
	public Boolean get_isUnlock() { }
	// RVA: 0x340c778 VA: 0x7595a24778
	public Void LoadData(String actId, ArcadeStageAdditionalData stageAdditionalData) { }
	// RVA: 0x340c914 VA: 0x7595a24914
	public Void UpdatePlayerData() { }
	// RVA: 0x340ca70 VA: 0x7595a24a70
	public Rank GetRankByScore(Int32 score) { }
	// RVA: 0x340cba4 VA: 0x7595a24ba4
	public Rank GetMaxRewardRank() { }
	// RVA: 0x340c988 VA: 0x7595a24988
	private StageStatus _CalcStageStatus() { }
	// RVA: 0x340cc28 VA: 0x7595a24c28
	public Void .ctor() { }
}
```