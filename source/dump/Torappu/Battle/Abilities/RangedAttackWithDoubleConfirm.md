# RangedAttackWithDoubleConfirm

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean m_hasFirstConfirm`

- `Boolean _checkCanUseAbilityFlag`

- `Boolean _useCachedPositionForced`


## Methods

- `Void _ResetDoubleConfirm()`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Vector2 <>xLuaBaseProxy_GetCastDirectlyMapPosition()`

- `Void <>xLuaBaseProxy_Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RangedAttackWithDoubleConfirm : RangedAttack
{
	private Boolean m_hasFirstConfirm; // 0x25c
	private Nullable`1 m_cachedPosition; // 0x260
	private Boolean _checkCanUseAbilityFlag; // 0x26c
	private Boolean _useCachedPositionForced; // 0x26d
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x0
	private static DelegateBridge __Hotfix0_GetCastDirectlyMapPosition; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0__ResetDoubleConfirm; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e184c4 VA: 0x75944304c4
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e186ec VA: 0x75944306ec
	protected override Vector2 GetCastDirectlyMapPosition() { }
	// RVA: 0x1e18784 VA: 0x7594430784
	protected override Void Reset() { }
	// RVA: 0x1e1867c VA: 0x759443067c
	private Void _ResetDoubleConfirm() { }
	// RVA: 0x1e187f4 VA: 0x75944307f4
	public Void .ctor() { }
	// RVA: 0x1e18860 VA: 0x7594430860
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e1886c VA: 0x759443086c
	private Vector2 <>xLuaBaseProxy_GetCastDirectlyMapPosition() { }
	// RVA: 0x1e18874 VA: 0x7594430874
	private Void <>xLuaBaseProxy_Reset() { }
}
```