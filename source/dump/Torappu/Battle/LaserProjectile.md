# LaserProjectile

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _unlimitedAlreadyHit`

- `Boolean _ignoreTargetDead`

- `Boolean _hitIgnoreAttached`


## Methods

- `IEnumerator <>n__0(Entity)`

- `IEnumerator <>xLuaBaseProxy_DoLink(Entity)`

- `Int32 <>xLuaBaseProxy_GetMaxHitNum()`

- `Boolean <>xLuaBaseProxy_CheckTargetAlreadyHitAndUpdate(Entity)`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class LaserProjectile : LinkProjectile
{
	private Boolean _unlimitedAlreadyHit; // 0x1c8
	private Boolean _ignoreTargetDead; // 0x1c9
	private Boolean _hitIgnoreAttached; // 0x1ca
	private static DelegateBridge __Hotfix0_DoLink; // 0x0
	private static DelegateBridge __Hotfix0_GetMaxHitNum; // 0x8
	private static DelegateBridge __Hotfix0_CheckTargetAlreadyHitAndUpdate; // 0x10
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x40a631c VA: 0x75966be31c
	protected override IEnumerator DoLink(Entity target) { }
	// RVA: 0x40a6414 VA: 0x75966be414
	public override Int32 GetMaxHitNum() { }
	// RVA: 0x40a647c VA: 0x75966be47c
	protected override Boolean CheckTargetAlreadyHitAndUpdate(Entity target) { }
	// RVA: 0x40a6518 VA: 0x75966be518
	protected override Void OnHitTarget(Entity target) { }
	// RVA: 0x40a6a5c VA: 0x75966bea5c
	public Void .ctor() { }
	// RVA: 0x40a6ac8 VA: 0x75966beac8
	private IEnumerator <>n__0(Entity target) { }
	// RVA: 0x40a6acc VA: 0x75966beacc
	private IEnumerator <>xLuaBaseProxy_DoLink(Entity P0) { }
	// RVA: 0x40a6ad0 VA: 0x75966bead0
	private Int32 <>xLuaBaseProxy_GetMaxHitNum() { }
	// RVA: 0x40a6b3c VA: 0x75966beb3c
	private Boolean <>xLuaBaseProxy_CheckTargetAlreadyHitAndUpdate(Entity P0) { }
	// RVA: 0x40a6b40 VA: 0x75966beb40
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
}
```