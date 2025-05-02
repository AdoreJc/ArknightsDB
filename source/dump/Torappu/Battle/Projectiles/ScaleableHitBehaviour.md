# ScaleableHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Boolean _applyExtraAtkScale`

- `Single _atkScale`

- `String _checkValidViaBBKey`

- `Boolean _applyAtkScaleTraceTgt`

- `String _atkScaleKeyTraceTgt`

- `Single m_atkScale`

- `Single m_atkScaleToTraceTgt`

- `Boolean m_isValid`


## Methods

- `Void OnBeforeHitTarget(Entity)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_DealHitTarget(Entity, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ScaleableHitBehaviour : HitBehaviour
{
	private Boolean _applyExtraAtkScale; // 0xa8
	private Single _atkScale; // 0xac
	private String _checkValidViaBBKey; // 0xb0
	private Boolean _applyAtkScaleTraceTgt; // 0xb8
	private String _atkScaleKeyTraceTgt; // 0xc0
	private Single m_atkScale; // 0xc8
	private Single m_atkScaleToTraceTgt; // 0xcc
	private Boolean m_isValid; // 0xd0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_DealHitTarget; // 0x8
	private static DelegateBridge __Hotfix0_OnBeforeHitTarget; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d7090c VA: 0x759438890c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d70b10 VA: 0x7594388b10
	protected override Void DealHitTarget(Entity target, Boolean force) { }
	// RVA: 0x1d70bc0 VA: 0x7594388bc0
	protected Void OnBeforeHitTarget(Entity target) { }
	// RVA: 0x1d70d64 VA: 0x7594388d64
	public Void .ctor() { }
	// RVA: 0x1d70e60 VA: 0x7594388e60
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d70e64 VA: 0x7594388e64
	private Void <>xLuaBaseProxy_DealHitTarget(Entity P0, Boolean P1) { }
}
```