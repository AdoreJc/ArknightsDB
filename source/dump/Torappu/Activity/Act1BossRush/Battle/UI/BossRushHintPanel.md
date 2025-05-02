# BossRushHintPanel

**Namespace:** `Torappu.Activity.Act1BossRush.Battle.UI`


## Fields

- `Transform _panelDangerArea`

- `BossRushCountdownDisplay _bossRushCountdownDisplay`


## Methods

- `Void OnGameInit()`

- `Void HintDangerArea(Object)`

- `Void OnBonusWaveFinished(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush.Battle.UI
public class BossRushHintPanel : MonoBehaviour, IHotfixable
{
	private Transform _panelDangerArea; // 0x18
	private BossRushCountdownDisplay _bossRushCountdownDisplay; // 0x20
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x0
	private static DelegateBridge __Hotfix0_HintDangerArea; // 0x8
	private static DelegateBridge __Hotfix0_OnBonusWaveFinished; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31966e8 VA: 0x75957ae6e8
	public Void OnGameInit() { }
	// RVA: 0x3199460 VA: 0x75957b1460
	public Void HintDangerArea(Object args) { }
	// RVA: 0x31994f4 VA: 0x75957b14f4
	public Void OnBonusWaveFinished(Object args) { }
	// RVA: 0x3199588 VA: 0x75957b1588
	public Void .ctor() { }
}
```