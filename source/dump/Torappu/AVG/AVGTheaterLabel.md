# AVGTheaterLabel

**Namespace:** `Torappu.AVG`


## Fields

- `AVGController _avgController`


## Methods

- `Boolean _ExecuteTheaterNode(Command)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGTheaterLabel : ExecutorComponent
{
	private const String COMMAND_NAME_THREATER_MODE; // 0x0
	private AVGController _avgController; // 0x50
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0__ExecuteTheaterNode; // 0x8
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3e75958 VA: 0x759648d958
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e75a94 VA: 0x759648da94
	private Boolean _ExecuteTheaterNode(Command command) { }
	// RVA: 0x3e75bb0 VA: 0x759648dbb0
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e75c14 VA: 0x759648dc14
	public Void .ctor() { }
}
```