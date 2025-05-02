# DanmakuGameMode

**Namespace:** ` `


## Methods

- `Boolean IsSchedulerNeedPreprocess(out)`

- `Void <>xLuaBaseProxy_PostprocessMap(Map)`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Tile <>xLuaBaseProxy_Hook_MapGetTileFromScreenPos(Vector2, out)`

- `Boolean <>xLuaBaseProxy_IsHook_MapGetTileFromScreenPos()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DanmakuGameMode : DefaultGameMode
{
	public const String DANMAKU_UI_PLUGIN_PATH; // 0x0
	private static DelegateBridge __Hotfix0_PostprocessMap; // 0x0
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x8
	private static DelegateBridge __Hotfix0_Hook_MapGetTileFromScreenPos; // 0x10
	private static DelegateBridge __Hotfix0_IsHook_MapGetTileFromScreenPos; // 0x18
	private static DelegateBridge __Hotfix0_IsSchedulerNeedPreprocess; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override GameModeType gameModeType { get; }

	// RVA: 0x1cca39c VA: 0x75942e239c
	public override Void PostprocessMap(Map map) { }
	// RVA: 0x1cca43c VA: 0x75942e243c
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1cca4a4 VA: 0x75942e24a4
	public override Tile Hook_MapGetTileFromScreenPos(Vector2 screenPos, out Vector2 mapPos) { }
	// RVA: 0x1cca56c VA: 0x75942e256c
	public override Boolean IsHook_MapGetTileFromScreenPos() { }
	// RVA: 0x1cca5d4 VA: 0x75942e25d4
	public Boolean IsSchedulerNeedPreprocess(out Boolean retainMimicEnemy) { }
	// RVA: 0x1cca650 VA: 0x75942e2650
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1cca6d8 VA: 0x75942e26d8
	private Void <>xLuaBaseProxy_PostprocessMap(Map P0) { }
	// RVA: 0x1cca6e0 VA: 0x75942e26e0
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cca6e8 VA: 0x75942e26e8
	private Tile <>xLuaBaseProxy_Hook_MapGetTileFromScreenPos(Vector2 P0, out Vector2 P1) { }
	// RVA: 0x1cca6f0 VA: 0x75942e26f0
	private Boolean <>xLuaBaseProxy_IsHook_MapGetTileFromScreenPos() { }
}
```