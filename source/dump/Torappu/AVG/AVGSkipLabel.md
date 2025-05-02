# AVGSkipLabel

**Namespace:** `Torappu.AVG`


## Fields

- `AVGController _avgController`

- `SkipLabelController m_skipLabelController`


## Methods

- `Boolean _ExecuteSkipNode(Command)`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGSkipLabel : ExecutorComponent
{
	public const String PARAM_NAME_SKIP_MODE; // 0x0
	public const String COMMAND_NAME_SKIP_NODE; // 0x0
	public const String MODE_NAME_FIRST_CANNOT_SKIP; // 0x0
	public const String MODE_NAME_CAN_SKIP; // 0x0
	private AVGController _avgController; // 0x50
	private SkipLabelController m_skipLabelController; // 0x58
	private static DelegateBridge __Hotfix0_OnReset; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0__ExecuteSkipNode; // 0x10
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3e73f80 VA: 0x759648bf80
	public override Void OnReset() { }
	// RVA: 0x3e74004 VA: 0x759648c004
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e74140 VA: 0x759648c140
	private Boolean _ExecuteSkipNode(Command command) { }
	// RVA: 0x3e74394 VA: 0x759648c394
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e743f8 VA: 0x759648c3f8
	public Void .ctor() { }
	// RVA: 0x3e744b0 VA: 0x759648c4b0
	private Void <>xLuaBaseProxy_OnReset() { }
}
```