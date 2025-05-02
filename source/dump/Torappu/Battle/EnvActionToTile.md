# EnvActionToTile

**Namespace:** `Torappu.Battle`


## Fields

- `ActionArray _actions`


## Properties

- `Context context`


## Methods

- `Context get_context()`

- `Void RunActionsOnTarget(Tile)`

- `Void <>xLuaBaseProxy_OnEnvChanged(Tile, String)`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvActionToTile : EnvEventExecutor
{
	private List`1 _envStatus; // 0x28
	private List`1 _blackboardPairs; // 0x30
	private ActionArray _actions; // 0x38
	private static DelegateBridge __Hotfix0_get_context; // 0x0
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x8
	private static DelegateBridge __Hotfix0_RunActionsOnTarget; // 0x10
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Context context { get; }

	// RVA: 0x401e370 VA: 0x7596636370
	public Context get_context() { }
	// RVA: 0x401e3fc VA: 0x75966363fc
	public override Void OnEnvChanged(Tile tile, String status) { }
	// RVA: 0x401e4d8 VA: 0x75966364d8
	public Void RunActionsOnTarget(Tile tile) { }
	// RVA: 0x401e72c VA: 0x759663672c
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x401e7d0 VA: 0x75966367d0
	public Void .ctor() { }
	// RVA: 0x401e880 VA: 0x7596636880
	private Void <>xLuaBaseProxy_OnEnvChanged(Tile P0, String P1) { }
	// RVA: 0x401e888 VA: 0x7596636888
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```