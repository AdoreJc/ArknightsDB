# BasicCharInfoModel

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_isEmpty`

- `Int32 <instId>k__BackingField`

- `String <charId>k__BackingField`

- `String <skinId>k__BackingField`

- `String <tmplId>k__BackingField`

- `String <name>k__BackingField`

- `String <nickName>k__BackingField`

- `RarityRank <rarity>k__BackingField`

- `ProfessionCategory <profession>k__BackingField`

- `String <subProfessionId>k__BackingField`

- `EvolvePhase <evolvePhase>k__BackingField`

- `Int32 <potentialRank>k__BackingField`

- `String <description>k__BackingField`

- `String <positionStr>k__BackingField`

- `Int32 <level>k__BackingField`

- `Int32 <maxLevel>k__BackingField`

- `Single <expPercent>k__BackingField`

- `DateTime <gainTime>k__BackingField`

- `Int32 <favorPoint>k__BackingField`

- `CharStarMarkState <starMark>k__BackingField`

- `CharacterData m_charData`

- `PlayerCharacter m_playerData`

- `AttributesData m_attrData`


## Properties

- `Boolean isEmpty`

- `Int32 instId`

- `String charId`

- `String skinId`

- `String tmplId`

- `String name`

- `String nickName`

- `RarityRank rarity`

- `ProfessionCategory profession`

- `String subProfessionId`

- `EvolvePhase evolvePhase`

- `Int32 potentialRank`

- `String description`

- `String positionStr`

- `Int32 level`

- `Int32 maxLevel`

- `Single expPercent`

- `DateTime gainTime`

- `Int32 favorPoint`

- `CharStarMarkState starMark`

- `BuildableType position`

- `Int32 atk`

- `Int32 def`

- `Single magicRes`

- `Int32 cost`

- `Int32 maxHp`

- `Int32 blockCnt`

- `Int32 respawnTime`

- `Single atkSpeed`

- `AttributesData attrData`


## Methods

- `Boolean get_isEmpty()`

- `Int32 get_instId()`

- `Void set_instId(Int32)`

- `String get_charId()`

- `Void set_charId(String)`

- `String get_skinId()`

- `Void set_skinId(String)`

- `String get_tmplId()`

- `Void set_tmplId(String)`

- `String get_name()`

- `Void set_name(String)`

- `String get_nickName()`

- `Void set_nickName(String)`

- `RarityRank get_rarity()`

- `Void set_rarity(RarityRank)`

- `ProfessionCategory get_profession()`

- `Void set_profession(ProfessionCategory)`

- `String get_subProfessionId()`

- `Void set_subProfessionId(String)`

- `EvolvePhase get_evolvePhase()`

- `Void set_evolvePhase(EvolvePhase)`

- `Int32 get_potentialRank()`

- `Void set_potentialRank(Int32)`

- `String get_description()`

- `Void set_description(String)`

- `String get_positionStr()`

- `Void set_positionStr(String)`

- `Int32 get_level()`

- `Void set_level(Int32)`

- `Int32 get_maxLevel()`

- `Void set_maxLevel(Int32)`

- `Single get_expPercent()`

- `Void set_expPercent(Single)`

- `DateTime get_gainTime()`

- `Void set_gainTime(DateTime)`

- `Int32 get_favorPoint()`

- `Void set_favorPoint(Int32)`

- `CharStarMarkState get_starMark()`

- `Void set_starMark(CharStarMarkState)`

- `BuildableType get_position()`

- `AttributesData _AttrDataSecured()`

- `Int32 get_atk()`

- `Int32 get_def()`

- `Single get_magicRes()`

- `Int32 get_cost()`

- `Int32 get_maxHp()`

- `Int32 get_blockCnt()`

- `Int32 get_respawnTime()`

- `Single get_atkSpeed()`

- `AttributesData get_attrData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class BasicCharInfoModel
{
	public static readonly BasicCharInfoModel EMPTY; // 0x0
	private Boolean m_isEmpty; // 0x10
	private Int32 <instId>k__BackingField; // 0x14
	private String <charId>k__BackingField; // 0x18
	private String <skinId>k__BackingField; // 0x20
	private String <tmplId>k__BackingField; // 0x28
	private String <name>k__BackingField; // 0x30
	private String <nickName>k__BackingField; // 0x38
	private RarityRank <rarity>k__BackingField; // 0x40
	private ProfessionCategory <profession>k__BackingField; // 0x44
	private String <subProfessionId>k__BackingField; // 0x48
	private EvolvePhase <evolvePhase>k__BackingField; // 0x50
	private Int32 <potentialRank>k__BackingField; // 0x54
	private String <description>k__BackingField; // 0x58
	private String <positionStr>k__BackingField; // 0x60
	private Int32 <level>k__BackingField; // 0x68
	private Int32 <maxLevel>k__BackingField; // 0x6c
	private Single <expPercent>k__BackingField; // 0x70
	private DateTime <gainTime>k__BackingField; // 0x78
	private Int32 <favorPoint>k__BackingField; // 0x80
	private CharStarMarkState <starMark>k__BackingField; // 0x84
	private CharacterData m_charData; // 0x88
	private PlayerCharacter m_playerData; // 0x90
	private AttributesData m_attrData; // 0x98

	public Boolean isEmpty { get; }
	public Int32 instId { get; set; }
	public String charId { get; set; }
	public String skinId { get; set; }
	public String tmplId { get; set; }
	public String name { get; set; }
	public String nickName { get; set; }
	public RarityRank rarity { get; set; }
	public ProfessionCategory profession { get; set; }
	public String subProfessionId { get; set; }
	public EvolvePhase evolvePhase { get; set; }
	public Int32 potentialRank { get; set; }
	public String description { get; set; }
	public String positionStr { get; set; }
	public Int32 level { get; set; }
	public Int32 maxLevel { get; set; }
	public Single expPercent { get; set; }
	public DateTime gainTime { get; set; }
	public Int32 favorPoint { get; set; }
	public CharStarMarkState starMark { get; set; }
	public BuildableType position { get; }
	public Int32 atk { get; }
	public Int32 def { get; }
	public Single magicRes { get; }
	public Int32 cost { get; }
	public Int32 maxHp { get; }
	public Int32 blockCnt { get; }
	public Int32 respawnTime { get; }
	public Single atkSpeed { get; }
	public AttributesData attrData { get; }

	// RVA: 0x211ec50 VA: 0x7594736c50
	public Boolean get_isEmpty() { }
	// RVA: 0x211ec58 VA: 0x7594736c58
	public Int32 get_instId() { }
	// RVA: 0x211ec60 VA: 0x7594736c60
	protected Void set_instId(Int32 value) { }
	// RVA: 0x211ec68 VA: 0x7594736c68
	public String get_charId() { }
	// RVA: 0x211ec70 VA: 0x7594736c70
	protected Void set_charId(String value) { }
	// RVA: 0x211ec78 VA: 0x7594736c78
	public String get_skinId() { }
	// RVA: 0x211ec80 VA: 0x7594736c80
	protected Void set_skinId(String value) { }
	// RVA: 0x211ec88 VA: 0x7594736c88
	public String get_tmplId() { }
	// RVA: 0x211ec90 VA: 0x7594736c90
	protected Void set_tmplId(String value) { }
	// RVA: 0x211ec98 VA: 0x7594736c98
	public String get_name() { }
	// RVA: 0x211eca0 VA: 0x7594736ca0
	protected Void set_name(String value) { }
	// RVA: 0x211eca8 VA: 0x7594736ca8
	public String get_nickName() { }
	// RVA: 0x211ecb0 VA: 0x7594736cb0
	protected Void set_nickName(String value) { }
	// RVA: 0x211ecb8 VA: 0x7594736cb8
	public RarityRank get_rarity() { }
	// RVA: 0x211ecc0 VA: 0x7594736cc0
	protected Void set_rarity(RarityRank value) { }
	// RVA: 0x211ecc8 VA: 0x7594736cc8
	public ProfessionCategory get_profession() { }
	// RVA: 0x211ecd0 VA: 0x7594736cd0
	protected Void set_profession(ProfessionCategory value) { }
	// RVA: 0x211ecd8 VA: 0x7594736cd8
	public String get_subProfessionId() { }
	// RVA: 0x211ece0 VA: 0x7594736ce0
	protected Void set_subProfessionId(String value) { }
	// RVA: 0x211ece8 VA: 0x7594736ce8
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x211ecf0 VA: 0x7594736cf0
	protected Void set_evolvePhase(EvolvePhase value) { }
	// RVA: 0x211ecf8 VA: 0x7594736cf8
	public Int32 get_potentialRank() { }
	// RVA: 0x211ed00 VA: 0x7594736d00
	protected Void set_potentialRank(Int32 value) { }
	// RVA: 0x211ed08 VA: 0x7594736d08
	public String get_description() { }
	// RVA: 0x211ed10 VA: 0x7594736d10
	protected Void set_description(String value) { }
	// RVA: 0x211ed18 VA: 0x7594736d18
	public String get_positionStr() { }
	// RVA: 0x211ed20 VA: 0x7594736d20
	protected Void set_positionStr(String value) { }
	// RVA: 0x211ed28 VA: 0x7594736d28
	public Int32 get_level() { }
	// RVA: 0x211ed30 VA: 0x7594736d30
	protected Void set_level(Int32 value) { }
	// RVA: 0x211ed38 VA: 0x7594736d38
	public Int32 get_maxLevel() { }
	// RVA: 0x211ed40 VA: 0x7594736d40
	protected Void set_maxLevel(Int32 value) { }
	// RVA: 0x211ed48 VA: 0x7594736d48
	public Single get_expPercent() { }
	// RVA: 0x211ed50 VA: 0x7594736d50
	protected Void set_expPercent(Single value) { }
	// RVA: 0x211ed58 VA: 0x7594736d58
	public DateTime get_gainTime() { }
	// RVA: 0x211ed60 VA: 0x7594736d60
	protected Void set_gainTime(DateTime value) { }
	// RVA: 0x211ed68 VA: 0x7594736d68
	public Int32 get_favorPoint() { }
	// RVA: 0x211ed70 VA: 0x7594736d70
	protected Void set_favorPoint(Int32 value) { }
	// RVA: 0x211ed78 VA: 0x7594736d78
	public CharStarMarkState get_starMark() { }
	// RVA: 0x211ed80 VA: 0x7594736d80
	protected Void set_starMark(CharStarMarkState value) { }
	// RVA: 0x211ed88 VA: 0x7594736d88
	public BuildableType get_position() { }
	// RVA: 0x211eda0 VA: 0x7594736da0
	private AttributesData _AttrDataSecured() { }
	// RVA: 0x211eff8 VA: 0x7594736ff8
	public Int32 get_atk() { }
	// RVA: 0x211f08c VA: 0x759473708c
	public Int32 get_def() { }
	// RVA: 0x211f120 VA: 0x7594737120
	public Single get_magicRes() { }
	// RVA: 0x211f1b4 VA: 0x75947371b4
	public Int32 get_cost() { }
	// RVA: 0x211f248 VA: 0x7594737248
	public Int32 get_maxHp() { }
	// RVA: 0x211f2dc VA: 0x75947372dc
	public Int32 get_blockCnt() { }
	// RVA: 0x211f370 VA: 0x7594737370
	public Int32 get_respawnTime() { }
	// RVA: 0x211f404 VA: 0x7594737404
	public Single get_atkSpeed() { }
	// RVA: 0x211f498 VA: 0x7594737498
	public AttributesData get_attrData() { }
	// RVA: 0x211f49c VA: 0x759473749c
	protected Void .ctor() { }
	// RVA: 0x211f4a4 VA: 0x75947374a4
	public static BasicCharInfoModel LoadModelFromSharedChar(SharedCharData sharedChar, CharacterData charData) { }
	// RVA: 0x211f624 VA: 0x7594737624
	public static BasicCharInfoModel LoadModelFromBattleChar(BattleCharacterData battleCharData) { }
	// RVA: 0x211f720 VA: 0x7594737720
	public static BasicCharInfoModel LoadModelFromSharedCharWithPotenialRank(SharedCharData sharedChar, CharacterData charData) { }
	// RVA: 0x211f514 VA: 0x7594737514
	private Void .ctor(SharedCharData sharedChar, CharacterData charData) { }
	// RVA: 0x211f684 VA: 0x7594737684
	private Void .ctor(BattleCharacterData battleChar) { }
	// RVA: 0x211f79c VA: 0x759473779c
	public static BasicCharInfoModel LoadModelFromPlayerChar(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x211f80c VA: 0x759473780c
	public Void .ctor(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x211fb08 VA: 0x7594737b08
	public static BasicCharInfoModel LoadModelFromPredefinedChar(PredefinedCharStruct charStruct, CharacterData charData) { }
	// RVA: 0x211fba4 VA: 0x7594737ba4
	public Void .ctor(PredefinedCharStruct charStruct, CharacterData charData) { }
	// RVA: 0x211fcfc VA: 0x7594737cfc
	public static BasicCharInfoModel TestOnly_LoadChar(Int32 fakeInstId, CharacterData charData) { }
	// RVA: 0x211fd6c VA: 0x7594737d6c
	private Void .ctor(Int32 fakeInstId, CharacterData charData) { }
	// RVA: 0x211fe04 VA: 0x7594737e04
	private static Void .cctor() { }
}
```