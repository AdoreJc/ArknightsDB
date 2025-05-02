# RuneManager

**Namespace:** `Torappu.Battle.Runes`


## Fields

- `RuneTarget m_targetMask`


## Methods

- `Boolean IsRuneKeyValid(String)`

- `Void Clear()`

- `Rune CreateRune(RuneData)`

- `Rune CreateLegacyRune(LegacyInLevelRuneData)`

- `Boolean ContainsAnyRune(RuneTarget)`

- `Void PreprocessRuneData()`

- `Void RemoveInvalidRunes()`

- `Void PreprocessBattlePlayerData(List`1)`

- `Options PreprocessLevelOptions(Options)`

- `RuneLevelExtraOutput PreprocessLevelData(LevelData, MapData)`

- `CharacterInOut PreprocessCharacter(CharacterInOut, Character)`

- `EnemyData PreprocessEnemy(EnemyData, Enemy)`

- `TileData PreprocessTile(TileData, GridPosition, Tile)`

- `Void PreprocessCardBuff(IList`1)`

- `Void PreprocessDeckData(Deck)`

- `Void _RegisterRuneClasses()`

- `Void _Register(String)`

- `Void Register(String)`

- `Rune _CreateInternal(RuneData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Runes
public class RuneManager : IHotfixable
{
	public static readonly String[] RUNE_EXCLUDED_FROM_BATTLE; // 0x0
	public static readonly String RUNE_SQUAD_NUM_LIMIT; // 0x8
	public static readonly String RUNE_SQUAD_NUM_MODIFY; // 0x10
	public static readonly String RUNE_LEVEL_HIDDEN_GROUP_ENABLE; // 0x18
	public static readonly String RUNE_LEVEL_HIDDEN_GROUP_DISABLE; // 0x20
	public static readonly String CHAR_GROUP_TAG_ADD; // 0x28
	public static readonly String GLOBAL_PLACEABLE_CHAR_NUM_ADD; // 0x30
	private RuneTarget m_targetMask; // 0x10
	private Dictionary`2 m_runeClasses; // 0x18
	private PriorityQueue`1 m_runes; // 0x20
	private static DelegateBridge __Hotfix0_get_runes; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40
	private static DelegateBridge __Hotfix0_IsRuneKeyValid; // 0x48
	private static DelegateBridge __Hotfix0_Clear; // 0x50
	private static DelegateBridge __Hotfix0_CreateRune; // 0x58
	private static DelegateBridge __Hotfix0_CreateLegacyRune; // 0x60
	private static DelegateBridge __Hotfix0_ContainsAnyRune; // 0x68
	private static DelegateBridge __Hotfix0_PreprocessRuneData; // 0x70
	private static DelegateBridge __Hotfix0_RemoveInvalidRunes; // 0x78
	private static DelegateBridge __Hotfix0_PreprocessBattlePlayerData; // 0x80
	private static DelegateBridge __Hotfix0_PreprocessLevelOptions; // 0x88
	private static DelegateBridge __Hotfix0_PreprocessLevelData; // 0x90
	private static DelegateBridge __Hotfix0_PreprocessCharacter; // 0x98
	private static DelegateBridge __Hotfix0_PreprocessEnemy; // 0xa0
	private static DelegateBridge __Hotfix0_PreprocessTile; // 0xa8
	private static DelegateBridge __Hotfix0_PreprocessCardBuff; // 0xb0
	private static DelegateBridge __Hotfix0_PreprocessDeckData; // 0xb8
	private static DelegateBridge __Hotfix0__RegisterRuneClasses; // 0xc0
	private static DelegateBridge __Hotfix0__Register; // 0xc8
	private static DelegateBridge __Hotfix0_Register; // 0xd0
	private static DelegateBridge __Hotfix0__CreateInternal; // 0xd8

	public IEnumerable`1 runes { get; }

	// RVA: 0x1d39e28 VA: 0x7594351e28
	public IEnumerable`1 get_runes() { }
	// RVA: 0x1d39ea0 VA: 0x7594351ea0
	public Void .ctor() { }
	// RVA: 0x1d3b358 VA: 0x7594353358
	public Boolean IsRuneKeyValid(String runeKey) { }
	// RVA: 0x1d3b408 VA: 0x7594353408
	public Void Clear() { }
	// RVA: 0x1d3b4a8 VA: 0x75943534a8
	public Rune CreateRune(RuneData data) { }
	// RVA: 0x1d3b788 VA: 0x7594353788
	public Rune CreateLegacyRune(LegacyInLevelRuneData legacyData) { }
	// RVA: 0x1d3b824 VA: 0x7594353824
	public Boolean ContainsAnyRune(RuneTarget target) { }
	// RVA: 0x1d3b93c VA: 0x759435393c
	public Void PreprocessRuneData() { }
	// RVA: 0x1d3bd14 VA: 0x7594353d14
	public Void RemoveInvalidRunes() { }
	// RVA: 0x1d3be28 VA: 0x7594353e28
	public Void PreprocessBattlePlayerData(List`1 playerDataList) { }
	// RVA: 0x1d3c0cc VA: 0x75943540cc
	public Options PreprocessLevelOptions(Options options) { }
	// RVA: 0x1d3c274 VA: 0x7594354274
	public RuneLevelExtraOutput PreprocessLevelData(LevelData levelData, MapData mapData) { }
	// RVA: 0x1d3c418 VA: 0x7594354418
	public CharacterInOut PreprocessCharacter(CharacterInOut inOut, Character character) { }
	// RVA: 0x1d3c5a0 VA: 0x75943545a0
	public EnemyData PreprocessEnemy(EnemyData enemyData, Enemy enemy) { }
	// RVA: 0x1d3c6fc VA: 0x75943546fc
	public TileData PreprocessTile(TileData tileData, GridPosition pos, Tile tile) { }
	// RVA: 0x1d3c8bc VA: 0x75943548bc
	public Void PreprocessCardBuff(IList`1 cards) { }
	// RVA: 0x1d3ca14 VA: 0x7594354a14
	public Void PreprocessDeckData(Deck deck) { }
	// RVA: 0x1d39fd0 VA: 0x7594351fd0
	private Void _RegisterRuneClasses() { }
	// RVA: 0x VA: 0x0
	private Void _Register(String key) { }
	// RVA: 0x VA: 0x0
	public Void Register(String key) { }
	// RVA: 0x1d3b5e8 VA: 0x75943535e8
	private Rune _CreateInternal(RuneData data) { }
	// RVA: 0x1d3cb84 VA: 0x7594354b84
	private static Void .cctor() { }
}
```