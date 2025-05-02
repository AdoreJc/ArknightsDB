# AdvancedMovementWithRandomBodyOffset

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Vector3 _randomRange`

- `Vector3 m_randomTargetOffset`

- `Vector3 m_bodyMapPosition`

- `Vector3 m_bodyDirection`


## Properties

- `Boolean isValid`


## Methods

- `Boolean get_isValid()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class AdvancedMovementWithRandomBodyOffset : AdvancedMovement
{
	private Vector3 _randomRange; // 0x114
	private Vector3 m_randomTargetOffset; // 0x120
	private Vector3 m_bodyMapPosition; // 0x12c
	private Vector3 m_bodyDirection; // 0x138
	private static DelegateBridge __Hotfix0_get_isValid; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isValid { get; }

	// RVA: 0x1d9ac20 VA: 0x75943b2c20
	public Boolean get_isValid() { }
	// RVA: 0x1d9acf8 VA: 0x75943b2cf8
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d9ae40 VA: 0x75943b2e40
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1d9af00 VA: 0x75943b2f00
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1d9b240 VA: 0x75943b3240
	public Void .ctor() { }
	// RVA: 0x1d9b2f0 VA: 0x75943b32f0
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d9b2f4 VA: 0x75943b32f4
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1d9b2f8 VA: 0x75943b32f8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```