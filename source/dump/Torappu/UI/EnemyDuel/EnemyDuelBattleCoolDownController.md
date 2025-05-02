# EnemyDuelBattleCoolDownController

**Namespace:** `Torappu.UI.EnemyDuel`


## Methods

- `Void Trigger(CoolDownType, Single)`

- `Single GetCooldown(CoolDownType)`

- `Boolean IsCooldownEnd(CoolDownType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBattleCoolDownController : PageSingleComponent
{
	private CountDownStopWatch[] m_timestampInfo; // 0x20
	private static DelegateBridge __Hotfix0_Trigger; // 0x0
	private static DelegateBridge __Hotfix0_GetCooldown; // 0x8
	private static DelegateBridge __Hotfix0_IsCooldownEnd; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x297e63c VA: 0x7594f9663c
	public Void Trigger(CoolDownType coolDownType, Single cooldown) { }
	// RVA: 0x297f0f0 VA: 0x7594f970f0
	public Single GetCooldown(CoolDownType coolDownType) { }
	// RVA: 0x297e324 VA: 0x7594f96324
	public Boolean IsCooldownEnd(CoolDownType coolDownType) { }
	// RVA: 0x2985d78 VA: 0x7594f9dd78
	public Void .ctor() { }
}
```