# EnemyOnlyBlockedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _filterById`

- `String _filterId`

- `Enemy m_enemy`


## Methods

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnemyOnlyBlockedSelector : TargetSelector
{
	public Boolean _filterById; // 0x30
	public String _filterId; // 0x38
	private Enemy m_enemy; // 0x40
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x0
	private static DelegateBridge __Hotfix0_get_ignoreAllyTargetFree; // 0x8
	private static DelegateBridge __Hotfix0_get_ignoreHealFree; // 0x10
	private static DelegateBridge __Hotfix0_get_onlyIgnoreSomeOfTargetFreeCase; // 0x18
	private static DelegateBridge __Hotfix0_get_abnormalFlag; // 0x20
	private static DelegateBridge __Hotfix0_get_abnormalCombo; // 0x28
	private static DelegateBridge __Hotfix0_Reset; // 0x30
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x38
	private static DelegateBridge __Hotfix0_FindTiles; // 0x40
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x48
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	protected virtual Boolean ignoreTargetFree { get; }
	protected virtual Boolean ignoreAllyTargetFree { get; }
	protected virtual Boolean ignoreHealFree { get; }
	protected virtual Boolean onlyIgnoreSomeOfTargetFreeCase { get; }
	protected virtual AbnormalFlag abnormalFlag { get; }
	protected virtual AbnormalCombo abnormalCombo { get; }

	// RVA: 0x1ba9ef8 VA: 0x75941c1ef8
	protected virtual Boolean get_ignoreTargetFree() { }
	// RVA: 0x1ba9f60 VA: 0x75941c1f60
	protected virtual Boolean get_ignoreAllyTargetFree() { }
	// RVA: 0x1ba9fc4 VA: 0x75941c1fc4
	protected virtual Boolean get_ignoreHealFree() { }
	// RVA: 0x1baa028 VA: 0x75941c2028
	protected virtual Boolean get_onlyIgnoreSomeOfTargetFreeCase() { }
	// RVA: 0x1baa08c VA: 0x75941c208c
	protected virtual AbnormalFlag get_abnormalFlag() { }
	// RVA: 0x1baa0f4 VA: 0x75941c20f4
	protected virtual AbnormalCombo get_abnormalCombo() { }
	// RVA: 0x1baa15c VA: 0x75941c215c
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1baa294 VA: 0x75941c2294
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1baa4a0 VA: 0x75941c24a0
	public override List`1 FindTiles(Vector2 pos) { }
	// RVA: 0x1baa520 VA: 0x75941c2520
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1baa668 VA: 0x75941c2668
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1baa734 VA: 0x75941c2734
	public Void .ctor() { }
	// RVA: 0x1baa7a4 VA: 0x75941c27a4
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1baa7ac VA: 0x75941c27ac
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```