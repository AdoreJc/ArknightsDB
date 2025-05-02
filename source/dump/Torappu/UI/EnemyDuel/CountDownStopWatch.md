# CountDownStopWatch

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Single m_countdownRemainTime`

- `ScaledStopwatch m_stopWatch`


## Methods

- `Void Reset(Single)`

- `Single GetCurrRemainTime()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class CountDownStopWatch : IHotfixable
{
	private Single m_countdownRemainTime; // 0x10
	private ScaledStopwatch m_stopWatch; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_GetCurrRemainTime; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x297fb74 VA: 0x7594f97b74
	public Void Reset(Single countdownRemainTime) { }
	// RVA: 0x297fbfc VA: 0x7594f97bfc
	public Single GetCurrRemainTime() { }
	// RVA: 0x297fc94 VA: 0x7594f97c94
	public Void .ctor() { }
}
```