# LassoProjectile

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _keepWhenRallyPointLikeSwitch`


## Methods

- `Boolean _ValidForLassoProjectile()`

- `Void _OnRallyPointLikeSwitch(Object)`

- `IEnumerator <>n__0(Entity)`

- `IEnumerator <>xLuaBaseProxy_DoLink(Entity)`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class LassoProjectile : LinkProjectile
{
	private Boolean _keepWhenRallyPointLikeSwitch; // 0x1c8
	private static DelegateBridge __Hotfix0_DoLink; // 0x0
	private static DelegateBridge __Hotfix0__ValidForLassoProjectile; // 0x8
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x18
	private static DelegateBridge __Hotfix0__OnRallyPointLikeSwitch; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x40a6f44 VA: 0x75966bef44
	protected override IEnumerator DoLink(Entity target) { }
	// RVA: 0x40a703c VA: 0x75966bf03c
	private Boolean _ValidForLassoProjectile() { }
	// RVA: 0x40a7220 VA: 0x75966bf220
	protected override Void OnHitTarget(Entity target) { }
	// RVA: 0x40a7368 VA: 0x75966bf368
	protected override Void OnProjectileStop() { }
	// RVA: 0x40a7494 VA: 0x75966bf494
	private Void _OnRallyPointLikeSwitch(Object arg) { }
	// RVA: 0x40a7660 VA: 0x75966bf660
	public Void .ctor() { }
	// RVA: 0x40a76cc VA: 0x75966bf6cc
	private IEnumerator <>n__0(Entity target) { }
	// RVA: 0x40a76d0 VA: 0x75966bf6d0
	private IEnumerator <>xLuaBaseProxy_DoLink(Entity P0) { }
	// RVA: 0x40a76d4 VA: 0x75966bf6d4
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
	// RVA: 0x40a76d8 VA: 0x75966bf6d8
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```