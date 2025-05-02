# UIBattleStrifeTopBar

**Namespace:** `Torappu.Battle.Strife`


## Fields

- `Text _remainTimeText`

- `Text _curWave`

- `Int32 m_remainTime`


## Methods

- `Void UpdateWaveInfo(Int32, Int32)`

- `Void UpdateRemainingDuration(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Strife
public class UIBattleStrifeTopBar : MonoBehaviour, IHotfixable
{
	private Text _remainTimeText; // 0x18
	private Text _curWave; // 0x20
	private Int32 m_remainTime; // 0x28
	private static DelegateBridge __Hotfix0_UpdateWaveInfo; // 0x0
	private static DelegateBridge __Hotfix0_UpdateRemainingDuration; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1c598d0 VA: 0x75942718d0
	public Void UpdateWaveInfo(Int32 curWave, Int32 totalWave) { }
	// RVA: 0x1c599e8 VA: 0x75942719e8
	public Void UpdateRemainingDuration(Int32 remainingDuration, Int32 totalDuration) { }
	// RVA: 0x1c59b28 VA: 0x7594271b28
	public Void .ctor() { }
}
```