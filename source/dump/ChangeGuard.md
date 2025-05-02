# ChangeGuard

**Namespace:** ` `


## Fields

- `Context m_context`


## Properties

- `Context context`

- `Entity source`

- `Entity target`

- `Buff buff`

- `Ability ability`

- `Modifier modifier`

- `Projectile projectile`

- `Tile tile`

- `AttackInfo atkInfo`

- `Entity mainTarget`

- `Buff mainBuff`


## Methods

- `Context get_context()`

- `Entity get_source()`

- `Void set_source(Entity)`

- `Entity get_target()`

- `Void set_target(Entity)`

- `Buff get_buff()`

- `Void set_buff(Buff)`

- `Ability get_ability()`

- `Void set_ability(Ability)`

- `Modifier get_modifier()`

- `Void set_modifier(Modifier)`

- `Projectile get_projectile()`

- `Void set_projectile(Projectile)`

- `Tile get_tile()`

- `Void set_tile(Tile)`

- `AttackInfo get_atkInfo()`

- `Void set_atkInfo(AttackInfo)`

- `Entity get_mainTarget()`

- `Void set_mainTarget(Entity)`

- `Buff get_mainBuff()`

- `Void set_mainBuff(Buff)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ChangeGuard : IDisposable
{
	private Context m_context; // 0x10

	public Context context { get; }
	public Entity source { get; set; }
	public Entity target { get; set; }
	public Buff buff { get; set; }
	public Ability ability { get; set; }
	public Modifier modifier { get; set; }
	public Projectile projectile { get; set; }
	public Tile tile { get; set; }
	public AttackInfo atkInfo { get; set; }
	public Entity mainTarget { get; set; }
	public Buff mainBuff { get; set; }

	// RVA: 0x3fa77e0 VA: 0x75965bf7e0
	public Context get_context() { }
	// RVA: 0x3fa6ee0 VA: 0x75965beee0
	public Void .ctor(Context context) { }
	// RVA: 0x3fa77e8 VA: 0x75965bf7e8
	public Entity get_source() { }
	// RVA: 0x3fa7840 VA: 0x75965bf840
	public Void set_source(Entity value) { }
	// RVA: 0x3fa78cc VA: 0x75965bf8cc
	public Entity get_target() { }
	// RVA: 0x3fa7924 VA: 0x75965bf924
	public Void set_target(Entity value) { }
	// RVA: 0x3fa79b0 VA: 0x75965bf9b0
	public Buff get_buff() { }
	// RVA: 0x3fa7a08 VA: 0x75965bfa08
	public Void set_buff(Buff value) { }
	// RVA: 0x3fa7a94 VA: 0x75965bfa94
	public Ability get_ability() { }
	// RVA: 0x3fa7aec VA: 0x75965bfaec
	public Void set_ability(Ability value) { }
	// RVA: 0x3fa7b78 VA: 0x75965bfb78
	public Modifier get_modifier() { }
	// RVA: 0x3fa7bf4 VA: 0x75965bfbf4
	public Void set_modifier(Modifier value) { }
	// RVA: 0x3fa7cc0 VA: 0x75965bfcc0
	public Projectile get_projectile() { }
	// RVA: 0x3fa7d18 VA: 0x75965bfd18
	public Void set_projectile(Projectile value) { }
	// RVA: 0x3fa7da4 VA: 0x75965bfda4
	public Tile get_tile() { }
	// RVA: 0x3fa7dfc VA: 0x75965bfdfc
	public Void set_tile(Tile value) { }
	// RVA: 0x3fa7e88 VA: 0x75965bfe88
	public AttackInfo get_atkInfo() { }
	// RVA: 0x3fa7f08 VA: 0x75965bff08
	public Void set_atkInfo(AttackInfo value) { }
	// RVA: 0x3fa7fc4 VA: 0x75965bffc4
	public Entity get_mainTarget() { }
	// RVA: 0x3fa801c VA: 0x75965c001c
	public Void set_mainTarget(Entity value) { }
	// RVA: 0x3fa80a8 VA: 0x75965c00a8
	public Buff get_mainBuff() { }
	// RVA: 0x3fa8100 VA: 0x75965c0100
	public Void set_mainBuff(Buff value) { }
	// RVA: 0x3fa818c VA: 0x75965c018c
	public Void Dispose() { }
}
```