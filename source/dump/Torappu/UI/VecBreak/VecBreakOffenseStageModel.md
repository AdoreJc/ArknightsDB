# VecBreakOffenseStageModel

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `VecBreakOffenseBossModel m_bossModel`

- `Boolean m_isTimeInvalid`

- `String <actId>k__BackingField`

- `String <stageId>k__BackingField`

- `String <code>k__BackingField`

- `String <name>k__BackingField`

- `String <diffDesc>k__BackingField`

- `String <storyDesc>k__BackingField`

- `Int32 <level>k__BackingField`

- `Int64 <startTs>k__BackingField`

- `StageStatus <stageStatus>k__BackingField`

- `ItemBundle <firstRewardItem>k__BackingField`

- `ItemBundle <commonRewardItem>k__BackingField`

- `ActVecBreakParticleType <particleType>k__BackingField`


## Properties

- `String actId`

- `String stageId`

- `String code`

- `String name`

- `String diffDesc`

- `String storyDesc`

- `Int32 level`

- `Int64 startTs`

- `StageStatus stageStatus`

- `ItemBundle firstRewardItem`

- `ItemBundle commonRewardItem`

- `ActVecBreakParticleType particleType`

- `Boolean isUnlock`

- `Boolean hasBoss`

- `Boolean canNavTo`

- `VecBreakOffenseBossModel bossModel`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `String get_stageId()`

- `Void set_stageId(String)`

- `String get_code()`

- `Void set_code(String)`

- `String get_name()`

- `Void set_name(String)`

- `String get_diffDesc()`

- `Void set_diffDesc(String)`

- `String get_storyDesc()`

- `Void set_storyDesc(String)`

- `Int32 get_level()`

- `Void set_level(Int32)`

- `Int64 get_startTs()`

- `Void set_startTs(Int64)`

- `StageStatus get_stageStatus()`

- `Void set_stageStatus(StageStatus)`

- `ItemBundle get_firstRewardItem()`

- `Void set_firstRewardItem(ItemBundle)`

- `ItemBundle get_commonRewardItem()`

- `Void set_commonRewardItem(ItemBundle)`

- `ActVecBreakParticleType get_particleType()`

- `Void set_particleType(ActVecBreakParticleType)`

- `Boolean get_isUnlock()`

- `Boolean get_hasBoss()`

- `Boolean get_canNavTo()`

- `VecBreakOffenseBossModel get_bossModel()`

- `Void LoadData(String, ActVecBreakOffenseStageData)`

- `Void UpdatePlayerData()`

- `Boolean IsFirstComplete(Boolean)`

- `StageStatus _CalcStageStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakOffenseStageModel : IHotfixable
{
	private VecBreakOffenseBossModel m_bossModel; // 0x10
	private Boolean m_isTimeInvalid; // 0x18
	private String <actId>k__BackingField; // 0x20
	private String <stageId>k__BackingField; // 0x28
	private String <code>k__BackingField; // 0x30
	private String <name>k__BackingField; // 0x38
	private String <diffDesc>k__BackingField; // 0x40
	private String <storyDesc>k__BackingField; // 0x48
	private Int32 <level>k__BackingField; // 0x50
	private Int64 <startTs>k__BackingField; // 0x58
	private StageStatus <stageStatus>k__BackingField; // 0x60
	private ItemBundle <firstRewardItem>k__BackingField; // 0x68
	private ItemBundle <commonRewardItem>k__BackingField; // 0x70
	private ActVecBreakParticleType <particleType>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_stageId; // 0x10
	private static DelegateBridge __Hotfix0_set_stageId; // 0x18
	private static DelegateBridge __Hotfix0_get_code; // 0x20
	private static DelegateBridge __Hotfix0_set_code; // 0x28
	private static DelegateBridge __Hotfix0_get_name; // 0x30
	private static DelegateBridge __Hotfix0_set_name; // 0x38
	private static DelegateBridge __Hotfix0_get_diffDesc; // 0x40
	private static DelegateBridge __Hotfix0_set_diffDesc; // 0x48
	private static DelegateBridge __Hotfix0_get_storyDesc; // 0x50
	private static DelegateBridge __Hotfix0_set_storyDesc; // 0x58
	private static DelegateBridge __Hotfix0_get_level; // 0x60
	private static DelegateBridge __Hotfix0_set_level; // 0x68
	private static DelegateBridge __Hotfix0_get_startTs; // 0x70
	private static DelegateBridge __Hotfix0_set_startTs; // 0x78
	private static DelegateBridge __Hotfix0_get_stageStatus; // 0x80
	private static DelegateBridge __Hotfix0_set_stageStatus; // 0x88
	private static DelegateBridge __Hotfix0_get_firstRewardItem; // 0x90
	private static DelegateBridge __Hotfix0_set_firstRewardItem; // 0x98
	private static DelegateBridge __Hotfix0_get_commonRewardItem; // 0xa0
	private static DelegateBridge __Hotfix0_set_commonRewardItem; // 0xa8
	private static DelegateBridge __Hotfix0_get_particleType; // 0xb0
	private static DelegateBridge __Hotfix0_set_particleType; // 0xb8
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0xc0
	private static DelegateBridge __Hotfix0_get_hasBoss; // 0xc8
	private static DelegateBridge __Hotfix0_get_canNavTo; // 0xd0
	private static DelegateBridge __Hotfix0_get_bossModel; // 0xd8
	private static DelegateBridge __Hotfix0_LoadData; // 0xe0
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0xe8
	private static DelegateBridge __Hotfix0_IsFirstComplete; // 0xf0
	private static DelegateBridge __Hotfix0__CalcStageStatus; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	public String actId { get; set; }
	public String stageId { get; set; }
	public String code { get; set; }
	public String name { get; set; }
	public String diffDesc { get; set; }
	public String storyDesc { get; set; }
	public Int32 level { get; set; }
	public Int64 startTs { get; set; }
	public StageStatus stageStatus { get; set; }
	public ItemBundle firstRewardItem { get; set; }
	public ItemBundle commonRewardItem { get; set; }
	public ActVecBreakParticleType particleType { get; set; }
	public Boolean isUnlock { get; }
	public Boolean hasBoss { get; }
	public Boolean canNavTo { get; }
	public VecBreakOffenseBossModel bossModel { get; }

	// RVA: 0x22d00cc VA: 0x75948e80cc
	public String get_actId() { }
	// RVA: 0x22d0134 VA: 0x75948e8134
	private Void set_actId(String value) { }
	// RVA: 0x22d01b8 VA: 0x75948e81b8
	public String get_stageId() { }
	// RVA: 0x22d0220 VA: 0x75948e8220
	private Void set_stageId(String value) { }
	// RVA: 0x22d02a4 VA: 0x75948e82a4
	public String get_code() { }
	// RVA: 0x22d030c VA: 0x75948e830c
	private Void set_code(String value) { }
	// RVA: 0x22d0390 VA: 0x75948e8390
	public String get_name() { }
	// RVA: 0x22d03f8 VA: 0x75948e83f8
	private Void set_name(String value) { }
	// RVA: 0x22d047c VA: 0x75948e847c
	public String get_diffDesc() { }
	// RVA: 0x22d04e4 VA: 0x75948e84e4
	private Void set_diffDesc(String value) { }
	// RVA: 0x22d0568 VA: 0x75948e8568
	public String get_storyDesc() { }
	// RVA: 0x22d05d0 VA: 0x75948e85d0
	private Void set_storyDesc(String value) { }
	// RVA: 0x22d0654 VA: 0x75948e8654
	public Int32 get_level() { }
	// RVA: 0x22d06bc VA: 0x75948e86bc
	private Void set_level(Int32 value) { }
	// RVA: 0x22d0738 VA: 0x75948e8738
	public Int64 get_startTs() { }
	// RVA: 0x22d07a0 VA: 0x75948e87a0
	private Void set_startTs(Int64 value) { }
	// RVA: 0x22ce6dc VA: 0x75948e66dc
	public StageStatus get_stageStatus() { }
	// RVA: 0x22d081c VA: 0x75948e881c
	private Void set_stageStatus(StageStatus value) { }
	// RVA: 0x22d0898 VA: 0x75948e8898
	public ItemBundle get_firstRewardItem() { }
	// RVA: 0x22d0900 VA: 0x75948e8900
	private Void set_firstRewardItem(ItemBundle value) { }
	// RVA: 0x22d0984 VA: 0x75948e8984
	public ItemBundle get_commonRewardItem() { }
	// RVA: 0x22d09ec VA: 0x75948e89ec
	private Void set_commonRewardItem(ItemBundle value) { }
	// RVA: 0x22d0a70 VA: 0x75948e8a70
	public ActVecBreakParticleType get_particleType() { }
	// RVA: 0x22d0ad8 VA: 0x75948e8ad8
	private Void set_particleType(ActVecBreakParticleType value) { }
	// RVA: 0x22d0b54 VA: 0x75948e8b54
	public Boolean get_isUnlock() { }
	// RVA: 0x22ce744 VA: 0x75948e6744
	public Boolean get_hasBoss() { }
	// RVA: 0x22d0be0 VA: 0x75948e8be0
	public Boolean get_canNavTo() { }
	// RVA: 0x22d0c7c VA: 0x75948e8c7c
	public VecBreakOffenseBossModel get_bossModel() { }
	// RVA: 0x22d0ce4 VA: 0x75948e8ce4
	public Void LoadData(String actId, ActVecBreakOffenseStageData offenseStageData) { }
	// RVA: 0x22d0e44 VA: 0x75948e8e44
	public Void UpdatePlayerData() { }
	// RVA: 0x22d0fa0 VA: 0x75948e8fa0
	public Boolean IsFirstComplete(Boolean isCompleteBefore) { }
	// RVA: 0x22d0eb8 VA: 0x75948e8eb8
	private StageStatus _CalcStageStatus() { }
	// RVA: 0x22d1034 VA: 0x75948e9034
	public Void .ctor() { }
}
```