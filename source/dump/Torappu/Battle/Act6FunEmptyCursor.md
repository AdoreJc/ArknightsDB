# Act6FunEmptyCursor

**Namespace:** `Torappu.Battle`


## Fields

- `Act6FunUIPlugin m_uiPlugin`


## Properties

- `Act6FunUIPlugin uiPlugin`


## Methods

- `Act6FunUIPlugin get_uiPlugin()`

- `Single <>xLuaBaseProxy_get_distToExit()`

- `Single <>xLuaBaseProxy_get_distToExitPrecise()`

- `Vector2 <>xLuaBaseProxy_GetContDirectionAfterEnd()`

- `Boolean <>xLuaBaseProxy_CheckReached()`

- `Vector2 <>xLuaBaseProxy_GetNextDirection()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act6FunEmptyCursor : DirectionCursor
{
	private Act6FunUIPlugin m_uiPlugin; // 0x80
	private static DelegateBridge __Hotfix0_get_uiPlugin; // 0x0
	private static DelegateBridge __Hotfix0_get_distToExit; // 0x8
	private static DelegateBridge __Hotfix0_get_distToExitPrecise; // 0x10
	private static DelegateBridge __Hotfix0_GetContDirectionAfterEnd; // 0x18
	private static DelegateBridge __Hotfix0_CheckReached; // 0x20
	private static DelegateBridge __Hotfix0_GetNextDirection; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Act6FunUIPlugin uiPlugin { get; }
	public override Single distToExit { get; }
	public override Single distToExitPrecise { get; }

	// RVA: 0x407a1e0 VA: 0x75966921e0
	private Act6FunUIPlugin get_uiPlugin() { }
	// RVA: 0x407a340 VA: 0x7596692340
	public override Single get_distToExit() { }
	// RVA: 0x407a3a8 VA: 0x75966923a8
	public override Single get_distToExitPrecise() { }
	// RVA: 0x407a410 VA: 0x7596692410
	public override Vector2 GetContDirectionAfterEnd() { }
	// RVA: 0x407a6a4 VA: 0x75966926a4
	public override Boolean CheckReached() { }
	// RVA: 0x407a7bc VA: 0x75966927bc
	public override Vector2 GetNextDirection() { }
	// RVA: 0x407a9d4 VA: 0x75966929d4
	public Void .ctor(Route route, SchedulerSnapshot snapshot, Vector2 offset, BObject obj, Boolean ignoreAllButMoveCp, Boolean visitEveryTileCenter, Boolean visitEveryNodeCenter) { }
	// RVA: 0x407ac28 VA: 0x7596692c28
	private Single <>xLuaBaseProxy_get_distToExit() { }
	// RVA: 0x407ad80 VA: 0x7596692d80
	private Single <>xLuaBaseProxy_get_distToExitPrecise() { }
	// RVA: 0x407b0f4 VA: 0x75966930f4
	private Vector2 <>xLuaBaseProxy_GetContDirectionAfterEnd() { }
	// RVA: 0x407b170 VA: 0x7596693170
	private Boolean <>xLuaBaseProxy_CheckReached() { }
	// RVA: 0x407b240 VA: 0x7596693240
	private Vector2 <>xLuaBaseProxy_GetNextDirection() { }
}
```