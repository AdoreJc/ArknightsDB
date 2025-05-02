# SectorFarthestPointMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Vector3 rotateOffset`

- `Boolean _hasInitRotation`


## Methods

- `Void _SetTargetPosAndDirection(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class SectorFarthestPointMovement : FarthestPointMovement
{
	private Vector3 rotateOffset; // 0x124
	private Boolean _hasInitRotation; // 0x130
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__SetTargetPosAndDirection; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1dabee4 VA: 0x75943c3ee4
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1dac3cc VA: 0x75943c43cc
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1dabf8c VA: 0x75943c3f8c
	private Void _SetTargetPosAndDirection(ILocatable start, ILocatable target) { }
	// RVA: 0x1dacc34 VA: 0x75943c4c34
	public Void .ctor() { }
	// RVA: 0x1dacca4 VA: 0x75943c4ca4
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1daccac VA: 0x75943c4cac
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```