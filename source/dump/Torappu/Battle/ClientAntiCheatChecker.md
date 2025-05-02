# ClientAntiCheatChecker

**Namespace:** `Torappu.Battle`


## Fields

- `ObscuredFloat m_moveMultiplier`

- `ObscuredFP m_costIncreaseTime`

- `PeriodicTimer m_checkTimer`

- `ObscuredInt m_checkTimes`

- `ObscuredBool m_isValidBattle`


## Methods

- `Void Init(Single, FP)`

- `Boolean _CheckEnemyMoveSpeed(Enemy)`

- `Boolean _CheckCostIncreaseTime()`

- `Boolean _CheckCharacterAttackTime(Character)`

- `Void _DoCheck()`

- `Void _ResetTimer()`

- `Void OnFixedUpdate(FP)`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ClientAntiCheatChecker : IHotfixable
{
	private static readonly ObscuredVector2 RANDOM_TIME_RANGE; // 0x0
	private static readonly ObscuredInt MAX_CHECK_TIMES; // 0x1c
	private ObscuredFloat m_moveMultiplier; // 0x10
	private ObscuredFP m_costIncreaseTime; // 0x28
	private PeriodicTimer m_checkTimer; // 0x50
	private ObscuredInt m_checkTimes; // 0x58
	private ObscuredBool m_isValidBattle; // 0x6c
	private ListDict`2 m_errorLog; // 0x78
	private static DelegateBridge __Hotfix0_get_errorLog; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x38
	private static DelegateBridge __Hotfix0__CheckEnemyMoveSpeed; // 0x40
	private static DelegateBridge __Hotfix0__CheckCostIncreaseTime; // 0x48
	private static DelegateBridge __Hotfix0__CheckCharacterAttackTime; // 0x50
	private static DelegateBridge __Hotfix0__DoCheck; // 0x58
	private static DelegateBridge __Hotfix0__ResetTimer; // 0x60
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x68
	private static DelegateBridge __Hotfix0_Clear; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public ListDict`2 errorLog { get; }

	// RVA: 0x3f60794 VA: 0x7596578794
	public ListDict`2 get_errorLog() { }
	// RVA: 0x3f6080c VA: 0x759657880c
	public Void Init(Single moveMultiplier, FP costIncreaseTime) { }
	// RVA: 0x3f60b38 VA: 0x7596578b38
	private Boolean _CheckEnemyMoveSpeed(Enemy enemy) { }
	// RVA: 0x3f61010 VA: 0x7596579010
	private Boolean _CheckCostIncreaseTime() { }
	// RVA: 0x3f61418 VA: 0x7596579418
	private Boolean _CheckCharacterAttackTime(Character character) { }
	// RVA: 0x3f61a40 VA: 0x7596579a40
	private Void _DoCheck() { }
	// RVA: 0x3f609b8 VA: 0x75965789b8
	private Void _ResetTimer() { }
	// RVA: 0x3f61ec8 VA: 0x7596579ec8
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x3f62118 VA: 0x759657a118
	public Void Clear() { }
	// RVA: 0x3f622ac VA: 0x759657a2ac
	public Void .ctor() { }
	// RVA: 0x3f62468 VA: 0x759657a468
	private static Void .cctor() { }
}
```