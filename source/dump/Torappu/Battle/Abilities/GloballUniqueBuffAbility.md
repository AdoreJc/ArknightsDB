# GloballUniqueBuffAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `BuffData _uniqueBuff`

- `Boolean _interruptible`

- `Boolean _removeBuffsIfNoValidTarget`

- `Boolean m_startCheck`


## Methods

- `Void _DoUpdateTarget()`

- `Void _DoAddBuff(Entity)`

- `Void _DoRemoveBuff()`

- `SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource()`

- `Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Boolean <>xLuaBaseProxy_OnSpellStart()`

- `Void <>xLuaBaseProxy_Reset()`

- `Boolean <>xLuaBaseProxy_InterruptIfNot()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class GloballUniqueBuffAbility : AbstractAnimatedAbility, IBuffSource
{
	protected BuffData _uniqueBuff; // 0x1c0
	protected Boolean _interruptible; // 0x1c8
	private Boolean _removeBuffsIfNoValidTarget; // 0x1c9
	private ObjectPtr`1 m_target; // 0x1d0
	private ObjectPtr`1 m_buff; // 0x1e0
	private Boolean m_startCheck; // 0x1f0
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x0
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x8
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x10
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x18
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x20
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x28
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x30
	private static DelegateBridge __Hotfix0_OnSpellStart; // 0x38
	private static DelegateBridge __Hotfix0_Reset; // 0x40
	private static DelegateBridge __Hotfix0_InterruptIfNot; // 0x48
	private static DelegateBridge __Hotfix0_OnDetached; // 0x50
	private static DelegateBridge __Hotfix0_OnTick; // 0x58
	private static DelegateBridge __Hotfix0__DoUpdateTarget; // 0x60
	private static DelegateBridge __Hotfix0__DoAddBuff; // 0x68
	private static DelegateBridge __Hotfix0__DoRemoveBuff; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e52458 VA: 0x759446a458
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e524c0 VA: 0x759446a4c0
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e52524 VA: 0x759446a524
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e5259c VA: 0x759446a59c
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e5261c VA: 0x759446a61c
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e52680 VA: 0x759446a680
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e526e4 VA: 0x759446a6e4
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e527fc VA: 0x759446a7fc
	protected override Boolean OnSpellStart() { }
	// RVA: 0x1e52880 VA: 0x759446a880
	protected override Void Reset() { }
	// RVA: 0x1e52958 VA: 0x759446a958
	public override Boolean InterruptIfNot() { }
	// RVA: 0x1e52ba8 VA: 0x759446aba8
	protected override Void OnDetached() { }
	// RVA: 0x1e52c1c VA: 0x759446ac1c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e52cc0 VA: 0x759446acc0
	private Void _DoUpdateTarget() { }
	// RVA: 0x1e53014 VA: 0x759446b014
	private Void _DoAddBuff(Entity target) { }
	// RVA: 0x1e529d8 VA: 0x759446a9d8
	private Void _DoRemoveBuff() { }
	// RVA: 0x1e5314c VA: 0x759446b14c
	public Void .ctor() { }
	// RVA: 0x1e531bc VA: 0x759446b1bc
	private SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource() { }
	// RVA: 0x1e531c4 VA: 0x759446b1c4
	private Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget() { }
	// RVA: 0x1e531cc VA: 0x759446b1cc
	private IList`1 <>xLuaBaseProxy_GetPassiveBuffs() { }
	// RVA: 0x1e531d4 VA: 0x759446b1d4
	private IList`1 <>xLuaBaseProxy_GetActiveBuffs() { }
	// RVA: 0x1e531dc VA: 0x759446b1dc
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e531e4 VA: 0x759446b1e4
	private Boolean <>xLuaBaseProxy_OnSpellStart() { }
	// RVA: 0x1e531ec VA: 0x759446b1ec
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e531f4 VA: 0x759446b1f4
	private Boolean <>xLuaBaseProxy_InterruptIfNot() { }
	// RVA: 0x1e531fc VA: 0x759446b1fc
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e53204 VA: 0x759446b204
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```