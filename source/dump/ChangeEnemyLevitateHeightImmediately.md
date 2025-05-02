# ChangeEnemyLevitateHeightImmediately

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ChangeEnemyLevitateHeightImmediately : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc4fbc VA: 0x75945dcfbc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc5024 VA: 0x75945dd024
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc51b4 VA: 0x75945dd1b4
	public Void .ctor() { }
}
```