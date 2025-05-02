# LrtsiaProjectileWrapper

**Namespace:** ` `


## Fields

- `CoolDownAfterHitBehaviour m_coolDownHitBehaviour`

- `Single m_radius`


## Properties

- `Boolean isActive`

- `Single radius`


## Methods

- `Boolean get_isActive()`

- `Single get_radius()`

- `Void SetRadius(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LrtsiaProjectileWrapper : ProjectileWrapper
{
	private CoolDownAfterHitBehaviour m_coolDownHitBehaviour; // 0x20
	private Single m_radius; // 0x28

	public Boolean isActive { get; }
	public Single radius { get; }

	// RVA: 0x1e19cc8 VA: 0x7594431cc8
	public Boolean get_isActive() { }
	// RVA: 0x1e19d50 VA: 0x7594431d50
	public Single get_radius() { }
	// RVA: 0x1e19d58 VA: 0x7594431d58
	public override Projectile GetGraphicProjectile() { }
	// RVA: 0x1e19d60 VA: 0x7594431d60
	public override Projectile GetProjectile() { }
	// RVA: 0x1e19d68 VA: 0x7594431d68
	public override Void SetGraphicProjectile(Projectile projectile) { }
	// RVA: 0x1e19d70 VA: 0x7594431d70
	public override Void SetProjectile(Projectile projectile) { }
	// RVA: 0x1e19e3c VA: 0x7594431e3c
	public Void SetRadius(Single radius) { }
	// RVA: 0x1e198ec VA: 0x75944318ec
	public Void .ctor() { }
}
```