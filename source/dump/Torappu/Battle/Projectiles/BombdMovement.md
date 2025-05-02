# BombdMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _fallingTime`

- `Single _fallingSpeed`

- `Single m_fallingTime`

- `Vector3 m_fallingDir`


## Methods

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class BombdMovement : AdvancedMovement
{
	private Single _fallingTime; // 0x114
	private Single _fallingSpeed; // 0x118
	private Single m_fallingTime; // 0x11c
	private Vector3 m_fallingDir; // 0x120
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1d9e108 VA: 0x75943b6108
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1d9e3ec VA: 0x75943b63ec
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1d9e55c VA: 0x75943b655c
	public Void .ctor() { }
	// RVA: 0x1d9e5c8 VA: 0x75943b65c8
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1d9e5cc VA: 0x75943b65cc
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```