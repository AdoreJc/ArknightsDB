# BoomberangTrait

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _skinKey`

- `Int32 m_maxProjectileCnt`

- `Int32 m_defaultMaxProjectileCnt`

- `Int32 m_currentProjectileCnt`

- `Int32 m_emitedProjectileCnt`

- `Int32 m_cacheMaxProjectileCnt`


## Properties

- `Int32 maxProjectileCnt`

- `Boolean hasValidProjectile`


## Methods

- `Void set_maxProjectileCnt(Int32)`

- `Int32 get_maxProjectileCnt()`

- `Boolean get_hasValidProjectile()`

- `Void OnAttackCastStart()`

- `Void OnCreateProjectile(Object)`

- `Void OnProjectileReached(Object)`

- `Void _OnProjectileComeBack(Projectile)`

- `Void ResetMaxProjectileCnt()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BoomberangTrait : PassiveBuffAbility
{
	public String _skinKey; // 0x110
	private BuffData[] _activeBuffsWhenProjectileComeback; // 0x118
	private Int32 m_maxProjectileCnt; // 0x120
	private Int32 m_defaultMaxProjectileCnt; // 0x124
	private Int32 m_currentProjectileCnt; // 0x128
	private Int32 m_emitedProjectileCnt; // 0x12c
	private Int32 m_cacheMaxProjectileCnt; // 0x130
	private const String DEFAULT_SKIN_KEY; // 0x0
	private HashSet`1 m_cacheProjectiles; // 0x138
	private static DelegateBridge __Hotfix0_set_maxProjectileCnt; // 0x0
	private static DelegateBridge __Hotfix0_get_maxProjectileCnt; // 0x8
	private static DelegateBridge __Hotfix0_get_hasValidProjectile; // 0x10
	private static DelegateBridge __Hotfix0_DoSetData; // 0x18
	private static DelegateBridge __Hotfix0_DoAttach; // 0x20
	private static DelegateBridge __Hotfix0_DoDetach; // 0x28
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x30
	private static DelegateBridge __Hotfix0_OnAttackCastStart; // 0x38
	private static DelegateBridge __Hotfix0_OnCreateProjectile; // 0x40
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x48
	private static DelegateBridge __Hotfix0__OnProjectileComeBack; // 0x50
	private static DelegateBridge __Hotfix0_ResetMaxProjectileCnt; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Int32 maxProjectileCnt { get; set; }
	public Boolean hasValidProjectile { get; }

	// RVA: 0x1e6aa88 VA: 0x7594482a88
	public Void set_maxProjectileCnt(Int32 value) { }
	// RVA: 0x1e6ab30 VA: 0x7594482b30
	public Int32 get_maxProjectileCnt() { }
	// RVA: 0x1e6ab98 VA: 0x7594482b98
	public Boolean get_hasValidProjectile() { }
	// RVA: 0x1e6ac08 VA: 0x7594482c08
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e6ad94 VA: 0x7594482d94
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e6af14 VA: 0x7594482f14
	protected override Void DoDetach() { }
	// RVA: 0x1e6b090 VA: 0x7594483090
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e6b178 VA: 0x7594483178
	public Void OnAttackCastStart() { }
	// RVA: 0x1e6b244 VA: 0x7594483244
	public Void OnCreateProjectile(Object args) { }
	// RVA: 0x1e6b41c VA: 0x759448341c
	public Void OnProjectileReached(Object args) { }
	// RVA: 0x1e6b548 VA: 0x7594483548
	private Void _OnProjectileComeBack(Projectile projectile) { }
	// RVA: 0x1e6b75c VA: 0x759448375c
	public Void ResetMaxProjectileCnt() { }
	// RVA: 0x1e6b7c8 VA: 0x75944837c8
	public Void .ctor() { }
	// RVA: 0x1e6b8d0 VA: 0x75944838d0
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e6b8f8 VA: 0x75944838f8
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e6b900 VA: 0x7594483900
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e6b908 VA: 0x7594483908
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```