# EnvActionToGlobal

**Namespace:** `Torappu.Battle`


## Fields

- `ActionArray _actions`


## Methods

- `Void RunActions()`

- `Void <>xLuaBaseProxy_OnEnvChanged(String)`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvActionToGlobal : EnvEventExecutor
{
	public List`1 _envStatus; // 0x28
	private ActionArray _actions; // 0x30
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x0
	private static DelegateBridge __Hotfix0_RunActions; // 0x8
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x401e06c VA: 0x759663606c
	public override Void OnEnvChanged(String status) { }
	// RVA: 0x401e15c VA: 0x759663615c
	public Void RunActions() { }
	// RVA: 0x401e20c VA: 0x759663620c
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x401e2b0 VA: 0x75966362b0
	public Void .ctor() { }
	// RVA: 0x401e360 VA: 0x7596636360
	private Void <>xLuaBaseProxy_OnEnvChanged(String P0) { }
	// RVA: 0x401e368 VA: 0x7596636368
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```