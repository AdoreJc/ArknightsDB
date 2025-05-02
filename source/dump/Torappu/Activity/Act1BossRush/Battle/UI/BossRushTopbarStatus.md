# BossRushTopbarStatus

**Namespace:** `Torappu.Activity.Act1BossRush.Battle.UI`


## Fields

- `UILifePoint _lifePoint`

- `Text _monsterInfoText`

- `Text _waveMessageText`

- `UILifeLostGroup _lifeLostContainer`

- `Int32 m_cachedFinishedEnemiesCnt`


## Methods

- `Void InitData(BattleController)`

- `Void UpdateData(BattleController, Boolean)`

- `Void _UpdateMonsterInfo(Boolean)`

- `Void OnShowWaveMessage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush.Battle.UI
public class BossRushTopbarStatus : IHotfixable
{
	private UILifePoint _lifePoint; // 0x10
	private Text _monsterInfoText; // 0x18
	private Text _waveMessageText; // 0x20
	private UILifeLostGroup _lifeLostContainer; // 0x28
	private Int32 m_cachedFinishedEnemiesCnt; // 0x30
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0__UpdateMonsterInfo; // 0x10
	private static DelegateBridge __Hotfix0_OnShowWaveMessage; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31968e0 VA: 0x75957ae8e0
	public Void InitData(BattleController controller) { }
	// RVA: 0x3196ce8 VA: 0x75957aece8
	public Void UpdateData(BattleController controller, Boolean force) { }
	// RVA: 0x3199834 VA: 0x75957b1834
	private Void _UpdateMonsterInfo(Boolean force) { }
	// RVA: 0x31999e4 VA: 0x75957b19e4
	public Void OnShowWaveMessage() { }
	// RVA: 0x3199b58 VA: 0x75957b1b58
	public Void .ctor() { }
}
```