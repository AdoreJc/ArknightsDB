# BattleStats

**Namespace:** ` `


## Fields

- `Int32 killedEnemiesCnt`

- `Int32 unnatrualRecoveredCost`

- `Int64 beginTs`

- `Int64 endTs`

- `String access`

- `String hash`

- `String packageName`

- `Boolean checkKilledCnt`

- `Int32 leftHp`

- `Single totalHeal`

- `Single totalDamage`

- `Int64 fixedPlayTime`

- `Boolean autoReplayCancelled`


## Methods

- `Void ClearAll()`

- `CharAdvancedStats TouchCharAdvancedStats(String)`

- `EnemyAdvancedStats TouchEnemyAdvancedStats(String)`

- `BattleStats TakeSnapShot(BattleController, BattleLogger)`

- `Void _FilterBattleInfoStats(ListDict`2)`

- `Void LogExtraBattleInfo(ExtraLogType, String, Int32, Boolean)`

- `Void _GenerateCharList(BattleStats, BattleLogger, ListDict`2, List`1)`

- `Void _GenerateLegionCharList(BattleStats, List`1, KeyValuePair`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BattleStats : IHotfixable
{
	public Int32 killedEnemiesCnt; // 0x10
	public Int32 unnatrualRecoveredCost; // 0x14
	public ListCounterPool`1 charStats; // 0x18
	public ListCounterPool`1 enemyStats; // 0x20
	public ListCounterPool`1 skillTrigStats; // 0x28
	public ListDict`2 charAdvancedStats; // 0x30
	public ListDict`2 enemyAdvancedStats; // 0x38
	public List`1 runeAdvancedStats; // 0x40
	public List`1 rlBuffAdvancedStats; // 0x48
	public ListDict`2 extraBattleInfoStats; // 0x50
	public List`1 extraBattleInfoSubStats; // 0x58
	private List`1 m_extraBattleLogTmpIds; // 0x60
	public ListDict`2 charList; // 0x68
	public ListDict`2 enemyList; // 0x70
	public List`1 runeList; // 0x78
	public List`1 rlBuffList; // 0x80
	public Int64 beginTs; // 0x88
	public Int64 endTs; // 0x90
	public String access; // 0x98
	public String hash; // 0xa0
	public String packageName; // 0xa8
	public Boolean checkKilledCnt; // 0xb0
	public Int32 leftHp; // 0xb4
	public Single totalHeal; // 0xb8
	public Single totalDamage; // 0xbc
	public Int64 fixedPlayTime; // 0xc0
	public List`1 restartCompleteTimeList; // 0xc8
	public Dictionary`2 extraInfo; // 0xd0
	public ListDict`2 extraBattleInfo; // 0xd8
	public ListDict`2 clientAntiCheatLog; // 0xe0
	public List`1 idList; // 0xe8
	public List`1 packedRuneDataList; // 0xf0
	public List`1 sixStarRuneList; // 0xf8
	public Boolean autoReplayCancelled; // 0x100
	private static DelegateBridge __Hotfix0_ClearAll; // 0x0
	private static DelegateBridge __Hotfix0_TouchCharAdvancedStats; // 0x8
	private static DelegateBridge __Hotfix0_TouchEnemyAdvancedStats; // 0x10
	private static DelegateBridge __Hotfix0_TakeSnapShot; // 0x18
	private static DelegateBridge __Hotfix0__FilterBattleInfoStats; // 0x20
	private static DelegateBridge __Hotfix0_LogExtraBattleInfo; // 0x28
	private static DelegateBridge __Hotfix0__GenerateCharList; // 0x30
	private static DelegateBridge __Hotfix0__GenerateLegionCharList; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3fdeec4 VA: 0x75965f6ec4
	public Void ClearAll() { }
	// RVA: 0x3fdc72c VA: 0x75965f472c
	public CharAdvancedStats TouchCharAdvancedStats(String charId) { }
	// RVA: 0x3fdd1dc VA: 0x75965f51dc
	public EnemyAdvancedStats TouchEnemyAdvancedStats(String enemyId) { }
	// RVA: 0x3fdf2fc VA: 0x75965f72fc
	public BattleStats TakeSnapShot(BattleController controller, BattleLogger logger) { }
	// RVA: 0x3fe1c1c VA: 0x75965f9c1c
	private Void _FilterBattleInfoStats(ListDict`2 advChars) { }
	// RVA: 0x3fe20cc VA: 0x75965fa0cc
	public Void LogExtraBattleInfo(ExtraLogType type, String extraKey, Int32 value, Boolean useMax) { }
	// RVA: 0x3fe0f78 VA: 0x75965f8f78
	private Void _GenerateCharList(BattleStats snapShot, BattleLogger logger, ListDict`2 advChars, List`1 squad) { }
	// RVA: 0x3fe2994 VA: 0x75965fa994
	private Void _GenerateLegionCharList(BattleStats snapShot, List`1 squad, KeyValuePair`2 advChar) { }
	// RVA: 0x3fdaf74 VA: 0x75965f2f74
	public Void .ctor() { }
}
```