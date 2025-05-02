# EnemyDuelPerformViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String actId`

- `EnemyDuelModeType gameMode`

- `EnemyDuelChoiceSide currChoiceSide`

- `EnemyDuelChoiceType currChoiceType`

- `Boolean isCurrSurvive`

- `Boolean isAutoChoose`

- `Boolean showWaitForOthers`

- `EnemyDuelTopBarViewModel topBarViewModel`

- `Int32 operationStreakNum`


## Methods

- `Void LoadData()`

- `Void _LoadPlayerModels(Dictionary`2)`

- `Void _LoadOperationData(ActivityEnemyDuelData)`

- `Void SetEmoticonDisabledStatus(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPerformViewModel : IHotfixable
{
	public String actId; // 0x10
	public EnemyDuelModeType gameMode; // 0x18
	public List`1 leftSide; // 0x20
	public List`1 rightSide; // 0x28
	public EnemyDuelChoiceSide currChoiceSide; // 0x30
	public EnemyDuelChoiceType currChoiceType; // 0x34
	public Boolean isCurrSurvive; // 0x38
	public Boolean isAutoChoose; // 0x39
	public Boolean showWaitForOthers; // 0x3a
	public EnemyDuelTopBarViewModel topBarViewModel; // 0x40
	public Int32 operationStreakNum; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadPlayerModels; // 0x8
	private static DelegateBridge __Hotfix0__LoadOperationData; // 0x10
	private static DelegateBridge __Hotfix0_SetEmoticonDisabledStatus; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x298bb3c VA: 0x7594fa3b3c
	public Void LoadData() { }
	// RVA: 0x298bcd8 VA: 0x7594fa3cd8
	private Void _LoadPlayerModels(Dictionary`2 playerDict) { }
	// RVA: 0x298c0d4 VA: 0x7594fa40d4
	private Void _LoadOperationData(ActivityEnemyDuelData actData) { }
	// RVA: 0x298c160 VA: 0x7594fa4160
	public Void SetEmoticonDisabledStatus(Boolean isEmoticonDisabled) { }
	// RVA: 0x298c1ec VA: 0x7594fa41ec
	public Void .ctor() { }
}
```