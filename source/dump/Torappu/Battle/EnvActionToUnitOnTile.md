# EnvActionToUnitOnTile

**Namespace:** `Torappu.Battle`


## Fields

- `TargetOptions _options`

- `ActionArray _actions`


## Properties

- `Context context`


## Methods

- `Context get_context()`

- `Void RunActionsOnTarget(Entity)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnEnvChanged(Tile, String)`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvActionToUnitOnTile : EnvEventExecutor
{
	public List`1 _envStatus; // 0x28
	protected TargetOptions _options; // 0x30
	protected List`1 _blackboardPairs; // 0x90
	private ActionArray _actions; // 0x98
	private static DelegateBridge __Hotfix0_get_context; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x10
	private static DelegateBridge __Hotfix0_RunActionsOnTarget; // 0x18
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Context context { get; }

	// RVA: 0x401ee0c VA: 0x7596636e0c
	public Context get_context() { }
	// RVA: 0x401ee98 VA: 0x7596636e98
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x401ef54 VA: 0x7596636f54
	public override Void OnEnvChanged(Tile tile, String status) { }
	// RVA: 0x401f26c VA: 0x759663726c
	public Void RunActionsOnTarget(Entity entity) { }
	// RVA: 0x401f50c VA: 0x759663750c
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x401f5b0 VA: 0x75966375b0
	public Void .ctor() { }
	// RVA: 0x401f660 VA: 0x7596637660
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x401f668 VA: 0x7596637668
	private Void <>xLuaBaseProxy_OnEnvChanged(Tile P0, String P1) { }
	// RVA: 0x401f670 VA: 0x7596637670
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```