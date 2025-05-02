# GlobalUniqueBuffToTargetsBySelectorAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `BuffData _uniqueBuff`

- `Boolean _removeBuffWhenCastEnd`

- `String _markOnTargetSignal`

- `Boolean m_startCheck`


## Methods

- `Void _DoUpdateTarget()`

- `Void _DoAddBuff(Entity)`

- `Void _DoRemoveAllBuffs()`

- `SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource()`

- `Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Boolean <>xLuaBaseProxy_OnSpellStart()`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class GlobalUniqueBuffToTargetsBySelectorAbility : AbstractAnimatedAbility, IBuffSource
{
	private const String ABILITY_MARK_STRING; // 0x0
	private const String ABILITY_MARK_ON_STRING; // 0x0
	protected BuffData _uniqueBuff; // 0x1c0
	protected Boolean _removeBuffWhenCastEnd; // 0x1c8
	private String _markOnTargetSignal; // 0x1d0
	private ListDict`2 m_targets; // 0x1d8
	private Boolean m_startCheck; // 0x1e0
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x0
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x8
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x10
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x18
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x20
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x28
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x30
	private static DelegateBridge __Hotfix0_OnSpellStart; // 0x38
	private static DelegateBridge __Hotfix0_Reset; // 0x40
	private static DelegateBridge __Hotfix0_OnDetached; // 0x48
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x50
	private static DelegateBridge __Hotfix0_OnTick; // 0x58
	private static DelegateBridge __Hotfix0__DoUpdateTarget; // 0x60
	private static DelegateBridge __Hotfix0__DoAddBuff; // 0x68
	private static DelegateBridge __Hotfix0__DoRemoveAllBuffs; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e5320c VA: 0x759446b20c
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e53274 VA: 0x759446b274
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e532d8 VA: 0x759446b2d8
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e53350 VA: 0x759446b350
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e533d0 VA: 0x759446b3d0
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e53434 VA: 0x759446b434
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e53498 VA: 0x759446b498
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e535b0 VA: 0x759446b5b0
	protected override Boolean OnSpellStart() { }
	// RVA: 0x1e53634 VA: 0x759446b634
	protected override Void Reset() { }
	// RVA: 0x1e536ec VA: 0x759446b6ec
	protected override Void OnDetached() { }
	// RVA: 0x1e539e8 VA: 0x759446b9e8
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e53a90 VA: 0x759446ba90
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e53b34 VA: 0x759446bb34
	private Void _DoUpdateTarget() { }
	// RVA: 0x1e543ec VA: 0x759446c3ec
	private Void _DoAddBuff(Entity target) { }
	// RVA: 0x1e53760 VA: 0x759446b760
	private Void _DoRemoveAllBuffs() { }
	// RVA: 0x1e54634 VA: 0x759446c634
	public Void .ctor() { }
	// RVA: 0x1e54738 VA: 0x759446c738
	private SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource() { }
	// RVA: 0x1e54740 VA: 0x759446c740
	private Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget() { }
	// RVA: 0x1e54748 VA: 0x759446c748
	private IList`1 <>xLuaBaseProxy_GetPassiveBuffs() { }
	// RVA: 0x1e54750 VA: 0x759446c750
	private IList`1 <>xLuaBaseProxy_GetActiveBuffs() { }
	// RVA: 0x1e54758 VA: 0x759446c758
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e54760 VA: 0x759446c760
	private Boolean <>xLuaBaseProxy_OnSpellStart() { }
	// RVA: 0x1e54768 VA: 0x759446c768
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e54770 VA: 0x759446c770
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e54778 VA: 0x759446c778
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e54780 VA: 0x759446c780
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```