# RoguelikeBattleExpManager

**Namespace:** `Torappu.Battle.Roguelike`


## Fields

- `RoguelikeInput m_input`

- `Int32 m_totalExp`

- `String m_totalExpLogKey`

- `Boolean m_initialized`


## Properties

- `Int32 totalExp`


## Methods

- `Int32 get_totalExp()`

- `Void Init(RoguelikeInput)`

- `Void LogEnemyKilled(Enemy)`

- `Void LogTrapGainedExp(String, Int32)`

- `Void _LogEnemyKilledCnt(Int32)`

- `Void _AddToTotalExpAndLog(Int32)`

- `Void _LogTrapExp(String, Int32)`

- `Boolean _CheckValidEnemyKill(Enemy)`

- `Void _InitLogStrs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike
public class RoguelikeBattleExpManager : IHotfixable
{
	private const String ROGUELIKE_BATTLE_EXP_HEAD; // 0x0
	private const String ROGUELIKE_BATTLE_EXP_ENEMY_KILLED; // 0x0
	private const String ROGUELIKE_BATTLE_EXP_TRAP_EXP; // 0x0
	private const String ROGUELIKE_BATTLE_EXP_SUM; // 0x0
	private RoguelikeInput m_input; // 0x10
	private Int32[] m_enemyExpPattern; // 0x18
	private Int32 m_totalExp; // 0x20
	private String[] m_enemyKillCntLogKeys; // 0x28
	private Dictionary`2 m_trapExpLogStrs; // 0x30
	private String m_totalExpLogKey; // 0x38
	private Boolean m_initialized; // 0x40
	private static DelegateBridge __Hotfix0_get_totalExp; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_LogEnemyKilled; // 0x10
	private static DelegateBridge __Hotfix0_LogTrapGainedExp; // 0x18
	private static DelegateBridge __Hotfix0__LogEnemyKilledCnt; // 0x20
	private static DelegateBridge __Hotfix0__AddToTotalExpAndLog; // 0x28
	private static DelegateBridge __Hotfix0__LogTrapExp; // 0x30
	private static DelegateBridge __Hotfix0__CheckValidEnemyKill; // 0x38
	private static DelegateBridge __Hotfix0__InitLogStrs; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int32 totalExp { get; }

	// RVA: 0x1d42d44 VA: 0x759435ad44
	public Int32 get_totalExp() { }
	// RVA: 0x1d42dac VA: 0x759435adac
	public Void Init(RoguelikeInput input) { }
	// RVA: 0x1d432e0 VA: 0x759435b2e0
	public Void LogEnemyKilled(Enemy enemy) { }
	// RVA: 0x1d4362c VA: 0x759435b62c
	public Void LogTrapGainedExp(String trapId, Int32 exp) { }
	// RVA: 0x1d4349c VA: 0x759435b49c
	private Void _LogEnemyKilledCnt(Int32 levelType) { }
	// RVA: 0x1d4356c VA: 0x759435b56c
	private Void _AddToTotalExpAndLog(Int32 exp) { }
	// RVA: 0x1d436dc VA: 0x759435b6dc
	private Void _LogTrapExp(String trapId, Int32 exp) { }
	// RVA: 0x1d433d0 VA: 0x759435b3d0
	private Boolean _CheckValidEnemyKill(Enemy enemy) { }
	// RVA: 0x1d43100 VA: 0x759435b100
	private Void _InitLogStrs() { }
	// RVA: 0x1d43854 VA: 0x759435b854
	public Void .ctor() { }
}
```