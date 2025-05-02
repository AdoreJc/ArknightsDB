# RelicTargetSelector

**Namespace:** ` `


## Fields

- `ProfessionCategory m_professionCategory`

- `BuildableType m_buildableMask`

- `RarityRankMask m_rarityRankMask`

- `BossFilterOption m_bossOption`

- `EnemyLevelMask m_enemyLevelMask`

- `SideType m_sideType`


## Properties

- `Boolean hasExtraFilterForCharGlobalBuff`

- `Boolean hasExtraFilterForEnemyGlobalBuff`


## Methods

- `Boolean get_hasExtraFilterForCharGlobalBuff()`

- `Boolean get_hasExtraFilterForEnemyGlobalBuff()`

- `Boolean Verify(BattleCharacterData)`

- `Boolean _VerifyExtraProfession(BattleCharacterData)`

- `Boolean Verify(Character)`

- `Boolean Verify(Card)`

- `Boolean Verify(Unit)`

- `Boolean VerifyProfession(ProfessionCategory)`

- `Boolean Verify(EnemyData)`

- `Void PreprocessGlobalBuffData(GlobalBuffData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RelicTargetSelector : IHotfixable
{
	private const String SELECTOR_PREFIX; // 0x0
	private const String BOSS_OPTION_KEY; // 0x0
	private const String BOSS_ONLY_KEY; // 0x0
	public const String BOSS_EXCLUDE_KEY; // 0x0
	private ProfessionCategory m_professionCategory; // 0x10
	private List`1 m_subProfessions; // 0x18
	private BuildableType m_buildableMask; // 0x20
	private RarityRankMask m_rarityRankMask; // 0x24
	private List`1 m_charIds; // 0x28
	private BossFilterOption m_bossOption; // 0x30
	private List`1 m_enemyTags; // 0x38
	private List`1 m_enemyIds; // 0x40
	private List`1 m_enemyExcludeIds; // 0x48
	private EnemyLevelMask m_enemyLevelMask; // 0x50
	private SideType m_sideType; // 0x54
	private static DelegateBridge __Hotfix0_get_hasExtraFilterForCharGlobalBuff; // 0x0
	private static DelegateBridge __Hotfix0_get_hasExtraFilterForEnemyGlobalBuff; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_Verify; // 0x18
	private static DelegateBridge __Hotfix0__VerifyExtraProfession; // 0x20
	private static DelegateBridge __Hotfix1_Verify; // 0x28
	private static DelegateBridge __Hotfix2_Verify; // 0x30
	private static DelegateBridge __Hotfix3_Verify; // 0x38
	private static DelegateBridge __Hotfix0_VerifyProfession; // 0x40
	private static DelegateBridge __Hotfix4_Verify; // 0x48
	private static DelegateBridge __Hotfix0_PreprocessGlobalBuffData; // 0x50

	private Boolean hasExtraFilterForCharGlobalBuff { get; }
	private Boolean hasExtraFilterForEnemyGlobalBuff { get; }

	// RVA: 0x1d49930 VA: 0x7594361930
	private Boolean get_hasExtraFilterForCharGlobalBuff() { }
	// RVA: 0x1d499f0 VA: 0x75943619f0
	private Boolean get_hasExtraFilterForEnemyGlobalBuff() { }
	// RVA: 0x1d48814 VA: 0x7594360814
	public Void .ctor(Blackboard blackboard) { }
	// RVA: 0x1d49ab4 VA: 0x7594361ab4
	public Boolean Verify(BattleCharacterData data) { }
	// RVA: 0x1d49c5c VA: 0x7594361c5c
	private Boolean _VerifyExtraProfession(BattleCharacterData data) { }
	// RVA: 0x1d49d00 VA: 0x7594361d00
	public Boolean Verify(Character character) { }
	// RVA: 0x1d49d94 VA: 0x7594361d94
	public Boolean Verify(Card card) { }
	// RVA: 0x1d49e28 VA: 0x7594361e28
	public Boolean Verify(Unit unit) { }
	// RVA: 0x1d4a158 VA: 0x7594362158
	public Boolean VerifyProfession(ProfessionCategory profession) { }
	// RVA: 0x1d49f68 VA: 0x7594361f68
	public Boolean Verify(EnemyData enemyData) { }
	// RVA: 0x1d4a1dc VA: 0x75943621dc
	public Void PreprocessGlobalBuffData(GlobalBuffData globalBuffData) { }
}
```