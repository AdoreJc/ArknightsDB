# BlemshSleepingFirstSelector

**Namespace:** `Torappu.Battle`


## Fields

- `AbnormalCombo _abnormalComboWithHighPriority`

- `Boolean _selectBlockRadiusSquareWithHighPrior`


## Methods

- `Boolean _CheckEnemyHasAbnormalComboAndInBlockableRange(Entity, Entity, out, out)`

- `Int32 <DoFindTargets_DISPOSE>b__2_0(Entity, Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BlemshSleepingFirstSelector : BlockedOrAdvancedSelector
{
	private AbnormalCombo _abnormalComboWithHighPriority; // 0x100
	private Boolean _selectBlockRadiusSquareWithHighPrior; // 0x104
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x0
	private static DelegateBridge __Hotfix0__CheckEnemyHasAbnormalComboAndInBlockableRange; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1ba0ec8 VA: 0x75941b8ec8
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1ba1b7c VA: 0x75941b9b7c
	private Boolean _CheckEnemyHasAbnormalComboAndInBlockableRange(Entity entity, Entity source, out FP weight, out Int32 volume) { }
	// RVA: 0x1ba1e04 VA: 0x75941b9e04
	public Void .ctor() { }
	// RVA: 0x1ba1ee4 VA: 0x75941b9ee4
	private Int32 <DoFindTargets_DISPOSE>b__2_0(Entity a, Entity b) { }
	// RVA: 0x1ba1f5c VA: 0x75941b9f5c
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
}
```