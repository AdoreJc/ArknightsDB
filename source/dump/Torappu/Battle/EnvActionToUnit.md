# EnvActionToUnit

**Namespace:** `Torappu.Battle`


## Fields

- `TargetOptions _options`

- `ActionArray _actions`


## Methods

- `Void RunActionsOnTarget(Entity)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnEnvChanged(String, Entity, Entity)`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvActionToUnit : EnvEventExecutor
{
	public List`1 _envStatus; // 0x28
	protected TargetOptions _options; // 0x30
	private ActionArray _actions; // 0x90
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x8
	private static DelegateBridge __Hotfix0_RunActionsOnTarget; // 0x10
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x401e890 VA: 0x7596636890
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x401e94c VA: 0x759663694c
	public override Void OnEnvChanged(String status, Entity target, Entity sourceNullable) { }
	// RVA: 0x401ea68 VA: 0x7596636a68
	public Void RunActionsOnTarget(Entity entity) { }
	// RVA: 0x401eca0 VA: 0x7596636ca0
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x401ed44 VA: 0x7596636d44
	public Void .ctor() { }
	// RVA: 0x401edf4 VA: 0x7596636df4
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x401edfc VA: 0x7596636dfc
	private Void <>xLuaBaseProxy_OnEnvChanged(String P0, Entity P1, Entity P2) { }
	// RVA: 0x401ee04 VA: 0x7596636e04
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```