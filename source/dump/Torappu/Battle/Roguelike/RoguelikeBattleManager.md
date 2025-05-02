# RoguelikeBattleManager

**Namespace:** `Torappu.Battle.Roguelike`


## Fields

- `String m_goldKey`

- `Int32 m_gold`

- `String m_fragmentKey`

- `Int32 m_fragment`

- `RoguelikeInput m_input`

- `RoguelikeRelicValidator m_validator`

- `FP m_lifePointModifierScale`

- `BattlePlayerData m_playerData`

- `LevelData m_levelData`


## Properties

- `FP lifePointModifierScale`

- `BattlePlayerData battlePlayerData`

- `LevelData levelData`


## Methods

- `FP get_lifePointModifierScale()`

- `Void set_lifePointModifierScale(FP)`

- `BattlePlayerData get_battlePlayerData()`

- `LevelData get_levelData()`

- `Void Init(RoguelikeInput, BattlePlayerData, LevelData)`

- `Void _RegisterRelicClasses()`

- `Void _Register(String)`

- `BasicRelic _CreateInternal(RoguelikeBuff, Int32)`

- `Void _CreateRelic(RoguelikeBuff, Int32)`

- `Int32 _TryRecalculateStackLayerInBattle(RoguelikeBuff, Int32)`

- `Boolean CheckExtraCondition(Blackboard, out)`

- `Void _CreateCharBuff(RoguelikeGameCharBuffBattleData)`

- `Void _ApplyFinalAttributes(AttributesData)`

- `Void _ClearAttributeCache()`

- `Void PreProcessCharacter(ref)`

- `Void PreprocessDeckCard(ref)`

- `Void PreprocessEnemy(ref)`

- `Options PreprocessLevelOptions(Options, Int32, Int32)`

- `PredefinedData PreprocessLevelPredefines(PredefinedData)`

- `Boolean ContainsCharacterRelic()`

- `Void OnApplyingGlobalModifier(ref)`

- `Void _OnModifyLifePoint(ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike
public class RoguelikeBattleManager : IHotfixable
{
	public const String RELIC_DYNAMIC_ABILITY_KEY; // 0x0
	public const String ENEMY_RELIC_DYNAMIC_ABILITY_KEY; // 0x0
	public const String RELIC_INSERT_TOKEN_KEY; // 0x0
	public const String RELIC_INSERT_TOKEN_INST; // 0x0
	public const String RELIC_DYNAMIC_ABILITY_KEY_AT_ROOT; // 0x0
	public const String RELIC_CHAR_SHARED_DATA; // 0x0
	public const String RELIC_BUFF_STACK_RES_KEY; // 0x0
	public const String RELIC_BUFF_STACK_RES_CNT_KEY; // 0x0
	public const String RELIC_BUFF_RELIANCE_RELICS; // 0x0
	public static readonly String RELIC_LEVEL_HIDDEN_GROUP_ENABLE; // 0x0
	public static readonly String RELIC_LEVEL_HIDDEN_GROUP_DISABLE; // 0x8
	public static readonly String ROGUE_SPECIAL_FRAGMENT; // 0x10
	public static readonly String RELIC_MISC_ADD_ENV_SYSTEM; // 0x18
	public static readonly String RELIC_GLOBAL_BUFF_NORMAL; // 0x20
	public static readonly String RELIC_GLOBAL_BUFF_STACK; // 0x28
	public static readonly String RELIC_GLOBAL_BUFF_STACK_BASE_ONE; // 0x30
	public static readonly String RELIC_GLOBAL_BUFF_LAYER; // 0x38
	private Dictionary`2 m_relicClasses; // 0x10
	private List`1 m_relics; // 0x18
	private List`1 m_charBuffs; // 0x20
	private List`1 m_enabledHiddenGroups; // 0x28
	private List`1 m_disabledHiddenGroups; // 0x30
	private String m_goldKey; // 0x38
	private Int32 m_gold; // 0x40
	private String m_fragmentKey; // 0x48
	private Int32 m_fragment; // 0x50
	private RoguelikeInput m_input; // 0x58
	private RoguelikeRelicValidator m_validator; // 0x60
	private FP[] m_attributeAdditions; // 0x68
	private FP[] m_attributeMultipliers; // 0x70
	private FP[] m_attributeFinalScalers; // 0x78
	private FP m_lifePointModifierScale; // 0x80
	private BattlePlayerData m_playerData; // 0x88
	private LevelData m_levelData; // 0x90
	private const String CONDITIONKEY; // 0x0
	private const String CONDITIONVALUE; // 0x0
	private static DelegateBridge __Hotfix0_get_attributeAdditons; // 0x40
	private static DelegateBridge __Hotfix0_get_attributeMultipliers; // 0x48
	private static DelegateBridge __Hotfix0_get_attributeFinalScalers; // 0x50
	private static DelegateBridge __Hotfix0_get_lifePointModifierScale; // 0x58
	private static DelegateBridge __Hotfix0_set_lifePointModifierScale; // 0x60
	private static DelegateBridge __Hotfix0_get_enabledHiddenGroups; // 0x68
	private static DelegateBridge __Hotfix0_get_disabledHiddenGroups; // 0x70
	private static DelegateBridge __Hotfix0_get_battlePlayerData; // 0x78
	private static DelegateBridge __Hotfix0_get_levelData; // 0x80
	private static DelegateBridge __Hotfix0_get_relics; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90
	private static DelegateBridge __Hotfix0_Init; // 0x98
	private static DelegateBridge __Hotfix0__RegisterRelicClasses; // 0xa0
	private static DelegateBridge __Hotfix0__Register; // 0xa8
	private static DelegateBridge __Hotfix0__CreateInternal; // 0xb0
	private static DelegateBridge __Hotfix0__CreateRelic; // 0xb8
	private static DelegateBridge __Hotfix0__TryRecalculateStackLayerInBattle; // 0xc0
	private static DelegateBridge __Hotfix0_CheckExtraCondition; // 0xc8
	private static DelegateBridge __Hotfix0__CreateCharBuff; // 0xd0
	private static DelegateBridge __Hotfix0__ApplyFinalAttributes; // 0xd8
	private static DelegateBridge __Hotfix0__ClearAttributeCache; // 0xe0
	private static DelegateBridge __Hotfix0_PreProcessCharacter; // 0xe8
	private static DelegateBridge __Hotfix0_PreprocessDeckCard; // 0xf0
	private static DelegateBridge __Hotfix0_PreprocessEnemy; // 0xf8
	private static DelegateBridge __Hotfix0_PreprocessGlobalBuff; // 0x100
	private static DelegateBridge __Hotfix0_PreprocessEnvSystems; // 0x108
	private static DelegateBridge __Hotfix0_PreprocessLevelOptions; // 0x110
	private static DelegateBridge __Hotfix0_PreprocessLevelPredefines; // 0x118
	private static DelegateBridge __Hotfix0_ContainsCharacterRelic; // 0x120
	private static DelegateBridge __Hotfix0_OnApplyingGlobalModifier; // 0x128
	private static DelegateBridge __Hotfix0__OnModifyLifePoint; // 0x130

	public FP[] attributeAdditons { get; }
	public FP[] attributeMultipliers { get; }
	public FP[] attributeFinalScalers { get; }
	public FP lifePointModifierScale { get; set; }
	public List`1 enabledHiddenGroups { get; }
	public List`1 disabledHiddenGroups { get; }
	public BattlePlayerData battlePlayerData { get; }
	public LevelData levelData { get; }
	public IEnumerable`1 relics { get; }

	// RVA: 0x1d43a68 VA: 0x759435ba68
	public FP[] get_attributeAdditons() { }
	// RVA: 0x1d43ae0 VA: 0x759435bae0
	public FP[] get_attributeMultipliers() { }
	// RVA: 0x1d43b58 VA: 0x759435bb58
	public FP[] get_attributeFinalScalers() { }
	// RVA: 0x1d43bd0 VA: 0x759435bbd0
	public FP get_lifePointModifierScale() { }
	// RVA: 0x1d43c48 VA: 0x759435bc48
	public Void set_lifePointModifierScale(FP value) { }
	// RVA: 0x1d43cd4 VA: 0x759435bcd4
	public List`1 get_enabledHiddenGroups() { }
	// RVA: 0x1d43da8 VA: 0x759435bda8
	public List`1 get_disabledHiddenGroups() { }
	// RVA: 0x1d43e7c VA: 0x759435be7c
	public BattlePlayerData get_battlePlayerData() { }
	// RVA: 0x1d43ef4 VA: 0x759435bef4
	public LevelData get_levelData() { }
	// RVA: 0x1d43f6c VA: 0x759435bf6c
	public IEnumerable`1 get_relics() { }
	// RVA: 0x1d43fe4 VA: 0x759435bfe4
	public Void .ctor() { }
	// RVA: 0x1d44bcc VA: 0x759435cbcc
	public Void Init(RoguelikeInput input, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1d44208 VA: 0x759435c208
	private Void _RegisterRelicClasses() { }
	// RVA: 0x VA: 0x0
	private Void _Register(String key) { }
	// RVA: 0x1d4579c VA: 0x759435d79c
	private BasicRelic _CreateInternal(RoguelikeBuff data, Int32 stackLayer) { }
	// RVA: 0x1d45424 VA: 0x759435d424
	private Void _CreateRelic(RoguelikeBuff data, Int32 stackLayer) { }
	// RVA: 0x1d45ddc VA: 0x759435dddc
	private Int32 _TryRecalculateStackLayerInBattle(RoguelikeBuff data, Int32 stackLayer) { }
	// RVA: 0x1d45a6c VA: 0x759435da6c
	protected Boolean CheckExtraCondition(Blackboard blackboard, out Boolean checkSatisfied) { }
	// RVA: 0x1d45594 VA: 0x759435d594
	private Void _CreateCharBuff(RoguelikeGameCharBuffBattleData charBuffData) { }
	// RVA: 0x1d45fac VA: 0x759435dfac
	private Void _ApplyFinalAttributes(AttributesData attributes) { }
	// RVA: 0x1d45204 VA: 0x759435d204
	private Void _ClearAttributeCache() { }
	// RVA: 0x1d46294 VA: 0x759435e294
	public Void PreProcessCharacter(ref RelicInOut inOut) { }
	// RVA: 0x1d46608 VA: 0x759435e608
	public Void PreprocessDeckCard(ref RelicInOut inOut) { }
	// RVA: 0x1d4682c VA: 0x759435e82c
	public Void PreprocessEnemy(ref RelicInOut inOut) { }
	// RVA: 0x1d4696c VA: 0x759435e96c
	public List`1 PreprocessGlobalBuff() { }
	// RVA: 0x1d46b68 VA: 0x759435eb68
	public List`1 PreprocessEnvSystems() { }
	// RVA: 0x1d46d64 VA: 0x759435ed64
	public Options PreprocessLevelOptions(Options originOptions, Int32 hp, Int32 shield) { }
	// RVA: 0x1d46f40 VA: 0x759435ef40
	public PredefinedData PreprocessLevelPredefines(PredefinedData predefinedData) { }
	// RVA: 0x1d47588 VA: 0x759435f588
	public Boolean ContainsCharacterRelic() { }
	// RVA: 0x1d4769c VA: 0x759435f69c
	public Void OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x1d47774 VA: 0x759435f774
	private Void _OnModifyLifePoint(ref Modifier modifier) { }
	// RVA: 0x1d478ec VA: 0x759435f8ec
	private static Void .cctor() { }
}
```