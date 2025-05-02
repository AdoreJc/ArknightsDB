# AVGGotoLabel

**Namespace:** `Torappu.AVG`


## Fields

- `GotoLabelController m_gotoLabelController`


## Methods

- `Boolean _ExecuteLabel(Command)`

- `Boolean _ExecuteGoto(Command)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGGotoLabel : ExecutorComponent
{
	private const String PARAM_NAME_NAME; // 0x0
	private const String COMMAND_NAME_LABEL; // 0x0
	private const String COMMAND_NAME_GOTO; // 0x0
	private GotoLabelController m_gotoLabelController; // 0x50
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0__ExecuteLabel; // 0x10
	private static DelegateBridge __Hotfix0__ExecuteGoto; // 0x18
	private static DelegateBridge __Hotfix0_OnFinish; // 0x20
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3e6f2a8 VA: 0x75964872a8
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e6f44c VA: 0x759648744c
	public override Void OnReset() { }
	// RVA: 0x3e6f540 VA: 0x7596487540
	private Boolean _ExecuteLabel(Command command) { }
	// RVA: 0x3e6f5b8 VA: 0x75964875b8
	private Boolean _ExecuteGoto(Command command) { }
	// RVA: 0x3e6f70c VA: 0x759648770c
	protected override Void OnFinish() { }
	// RVA: 0x3e6f778 VA: 0x7596487778
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e6f7dc VA: 0x75964877dc
	public Void .ctor() { }
	// RVA: 0x3e6f918 VA: 0x7596487918
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e6f920 VA: 0x7596487920
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```