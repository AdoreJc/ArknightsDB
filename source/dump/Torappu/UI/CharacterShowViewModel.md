# CharacterShowViewModel

**Namespace:** `Torappu.UI`


## Fields

- `String <charId>k__BackingField`

- `String <tmplId>k__BackingField`

- `Int32 <potentialRank>k__BackingField`

- `Int32 <mainSkillLvl>k__BackingField`

- `EvolvePhase <evolvePhase>k__BackingField`

- `Int32 <level>k__BackingField`

- `Int32 <favorPoint>k__BackingField`

- `Int32 <exp>k__BackingField`

- `String <skinId>k__BackingField`

- `String <infoHint>k__BackingField`

- `Boolean <isAllSlotVisible>k__BackingField`

- `Boolean <isUnlockHintVisible>k__BackingField`

- `Boolean <isBuildingSkillVisible>k__BackingField`

- `Int32 defaultEquipIndex`

- `Int32 defaultSkillIndex`


## Properties

- `String charId`

- `String tmplId`

- `Int32 potentialRank`

- `Int32 mainSkillLvl`

- `EvolvePhase evolvePhase`

- `Int32 level`

- `Int32 favorPoint`

- `Int32 exp`

- `String skinId`

- `String infoHint`

- `Boolean isAllSlotVisible`

- `Boolean isUnlockHintVisible`

- `Boolean isBuildingSkillVisible`


## Methods

- `String get_charId()`

- `Void set_charId(String)`

- `String get_tmplId()`

- `Void set_tmplId(String)`

- `Int32 get_potentialRank()`

- `Void set_potentialRank(Int32)`

- `Int32 get_mainSkillLvl()`

- `Void set_mainSkillLvl(Int32)`

- `EvolvePhase get_evolvePhase()`

- `Void set_evolvePhase(EvolvePhase)`

- `Int32 get_level()`

- `Void set_level(Int32)`

- `Int32 get_favorPoint()`

- `Void set_favorPoint(Int32)`

- `Int32 get_exp()`

- `Void set_exp(Int32)`

- `String get_skinId()`

- `Void set_skinId(String)`

- `String get_infoHint()`

- `Void set_infoHint(String)`

- `Boolean get_isAllSlotVisible()`

- `Void set_isAllSlotVisible(Boolean)`

- `Boolean get_isUnlockHintVisible()`

- `Void set_isUnlockHintVisible(Boolean)`

- `Boolean get_isBuildingSkillVisible()`

- `Void set_isBuildingSkillVisible(Boolean)`

- `CharQuery GetCharQuery()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CharacterShowViewModel : IHotfixable
{
	private String <charId>k__BackingField; // 0x10
	private String <tmplId>k__BackingField; // 0x18
	private Int32 <potentialRank>k__BackingField; // 0x20
	private Int32 <mainSkillLvl>k__BackingField; // 0x24
	private EvolvePhase <evolvePhase>k__BackingField; // 0x28
	private Int32 <level>k__BackingField; // 0x2c
	private Int32 <favorPoint>k__BackingField; // 0x30
	private Int32 <exp>k__BackingField; // 0x34
	private String <skinId>k__BackingField; // 0x38
	private String <infoHint>k__BackingField; // 0x40
	private Boolean <isAllSlotVisible>k__BackingField; // 0x48
	private Boolean <isUnlockHintVisible>k__BackingField; // 0x49
	private Boolean <isBuildingSkillVisible>k__BackingField; // 0x4a
	public List`1 equipList; // 0x50
	public List`1 skillList; // 0x58
	public Int32 defaultEquipIndex; // 0x60
	public Int32 defaultSkillIndex; // 0x64
	private static DelegateBridge __Hotfix0_get_charId; // 0x0
	private static DelegateBridge __Hotfix0_set_charId; // 0x8
	private static DelegateBridge __Hotfix0_get_tmplId; // 0x10
	private static DelegateBridge __Hotfix0_set_tmplId; // 0x18
	private static DelegateBridge __Hotfix0_get_potentialRank; // 0x20
	private static DelegateBridge __Hotfix0_set_potentialRank; // 0x28
	private static DelegateBridge __Hotfix0_get_mainSkillLvl; // 0x30
	private static DelegateBridge __Hotfix0_set_mainSkillLvl; // 0x38
	private static DelegateBridge __Hotfix0_get_evolvePhase; // 0x40
	private static DelegateBridge __Hotfix0_set_evolvePhase; // 0x48
	private static DelegateBridge __Hotfix0_get_level; // 0x50
	private static DelegateBridge __Hotfix0_set_level; // 0x58
	private static DelegateBridge __Hotfix0_get_favorPoint; // 0x60
	private static DelegateBridge __Hotfix0_set_favorPoint; // 0x68
	private static DelegateBridge __Hotfix0_get_exp; // 0x70
	private static DelegateBridge __Hotfix0_set_exp; // 0x78
	private static DelegateBridge __Hotfix0_get_skinId; // 0x80
	private static DelegateBridge __Hotfix0_set_skinId; // 0x88
	private static DelegateBridge __Hotfix0_get_infoHint; // 0x90
	private static DelegateBridge __Hotfix0_set_infoHint; // 0x98
	private static DelegateBridge __Hotfix0_get_isAllSlotVisible; // 0xa0
	private static DelegateBridge __Hotfix0_set_isAllSlotVisible; // 0xa8
	private static DelegateBridge __Hotfix0_get_isUnlockHintVisible; // 0xb0
	private static DelegateBridge __Hotfix0_set_isUnlockHintVisible; // 0xb8
	private static DelegateBridge __Hotfix0_get_isBuildingSkillVisible; // 0xc0
	private static DelegateBridge __Hotfix0_set_isBuildingSkillVisible; // 0xc8
	private static DelegateBridge __Hotfix0_GetCharQuery; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8
	private static DelegateBridge __Hotfix0_CreateSingleSlotAssistFromSharedData; // 0xe0
	private static DelegateBridge __Hotfix0_CreateMultiSlotAssistFromSharedData; // 0xe8
	private static DelegateBridge __Hotfix1_CreateMultiSlotAssistFromSharedData; // 0xf0
	private static DelegateBridge __Hotfix0__CreateMultiSlotAssistFromSharedData; // 0xf8
	private static DelegateBridge __Hotfix0_CreateVoucherEvolveTwoShowModel; // 0x100
	private static DelegateBridge __Hotfix0_CreateFullCultiChar; // 0x108
	private static DelegateBridge __Hotfix0_CreateCharShowForRogueTeam; // 0x110
	private static DelegateBridge __Hotfix0__CreateFullCultiCharImpl; // 0x118

	public String charId { get; set; }
	public String tmplId { get; set; }
	public Int32 potentialRank { get; set; }
	public Int32 mainSkillLvl { get; set; }
	public EvolvePhase evolvePhase { get; set; }
	public Int32 level { get; set; }
	public Int32 favorPoint { get; set; }
	public Int32 exp { get; set; }
	public String skinId { get; set; }
	public String infoHint { get; set; }
	public Boolean isAllSlotVisible { get; set; }
	public Boolean isUnlockHintVisible { get; set; }
	public Boolean isBuildingSkillVisible { get; set; }

	// RVA: 0x2106934 VA: 0x759471e934
	public String get_charId() { }
	// RVA: 0x210699c VA: 0x759471e99c
	private Void set_charId(String value) { }
	// RVA: 0x2106a20 VA: 0x759471ea20
	public String get_tmplId() { }
	// RVA: 0x2106a88 VA: 0x759471ea88
	private Void set_tmplId(String value) { }
	// RVA: 0x2106b0c VA: 0x759471eb0c
	public Int32 get_potentialRank() { }
	// RVA: 0x2106b74 VA: 0x759471eb74
	private Void set_potentialRank(Int32 value) { }
	// RVA: 0x2106bf0 VA: 0x759471ebf0
	public Int32 get_mainSkillLvl() { }
	// RVA: 0x2106c58 VA: 0x759471ec58
	private Void set_mainSkillLvl(Int32 value) { }
	// RVA: 0x2106cd4 VA: 0x759471ecd4
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x2106d3c VA: 0x759471ed3c
	private Void set_evolvePhase(EvolvePhase value) { }
	// RVA: 0x2106db8 VA: 0x759471edb8
	public Int32 get_level() { }
	// RVA: 0x2106e20 VA: 0x759471ee20
	private Void set_level(Int32 value) { }
	// RVA: 0x2106e9c VA: 0x759471ee9c
	public Int32 get_favorPoint() { }
	// RVA: 0x2106f04 VA: 0x759471ef04
	private Void set_favorPoint(Int32 value) { }
	// RVA: 0x2106f80 VA: 0x759471ef80
	public Int32 get_exp() { }
	// RVA: 0x2106fe8 VA: 0x759471efe8
	private Void set_exp(Int32 value) { }
	// RVA: 0x2107064 VA: 0x759471f064
	public String get_skinId() { }
	// RVA: 0x21070cc VA: 0x759471f0cc
	private Void set_skinId(String value) { }
	// RVA: 0x2107150 VA: 0x759471f150
	public String get_infoHint() { }
	// RVA: 0x21071b8 VA: 0x759471f1b8
	private Void set_infoHint(String value) { }
	// RVA: 0x210723c VA: 0x759471f23c
	public Boolean get_isAllSlotVisible() { }
	// RVA: 0x21072a4 VA: 0x759471f2a4
	private Void set_isAllSlotVisible(Boolean value) { }
	// RVA: 0x2107324 VA: 0x759471f324
	public Boolean get_isUnlockHintVisible() { }
	// RVA: 0x210738c VA: 0x759471f38c
	private Void set_isUnlockHintVisible(Boolean value) { }
	// RVA: 0x210740c VA: 0x759471f40c
	public Boolean get_isBuildingSkillVisible() { }
	// RVA: 0x2107474 VA: 0x759471f474
	private Void set_isBuildingSkillVisible(Boolean value) { }
	// RVA: 0x21074f4 VA: 0x759471f4f4
	public CharQuery GetCharQuery() { }
	// RVA: 0x21075c4 VA: 0x759471f5c4
	private Void .ctor() { }
	// RVA: 0x2107634 VA: 0x759471f634
	public static CharacterShowViewModel CreateSingleSlotAssistFromSharedData(SharedCharData sharedCharData) { }
	// RVA: 0x2107a9c VA: 0x759471fa9c
	public static CharacterShowViewModel CreateMultiSlotAssistFromSharedData(ModifiedSharedCharData sharedCharData, Boolean usePlayerSelection) { }
	// RVA: 0x2108144 VA: 0x7594720144
	public static CharacterShowViewModel CreateMultiSlotAssistFromSharedData(SharedCharData sharedCharData, String infoHint) { }
	// RVA: 0x2107b40 VA: 0x759471fb40
	private static CharacterShowViewModel _CreateMultiSlotAssistFromSharedData(SharedCharData sharedCharData, Boolean usePlayerSelection, Boolean isEquipLimited, String infoHint) { }
	// RVA: 0x21081cc VA: 0x75947201cc
	public static CharacterShowViewModel CreateVoucherEvolveTwoShowModel(Int32 instId) { }
	// RVA: 0x2108890 VA: 0x7594720890
	public static CharacterShowViewModel CreateFullCultiChar(String charId) { }
	// RVA: 0x2108f58 VA: 0x7594720f58
	public static CharacterShowViewModel CreateCharShowForRogueTeam(String charId, String tmplId) { }
	// RVA: 0x2108938 VA: 0x7594720938
	private static CharacterShowViewModel _CreateFullCultiCharImpl(String charId, Boolean isUnlockHintVisible, Boolean isMaxPotential, Boolean isBuildingSkillVisible, String infoHint, String tmplId) { }
}
```