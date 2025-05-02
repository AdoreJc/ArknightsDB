# CoopRecordDefenceBossStatus

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CoopRecordDefenceBossStatus : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f397a4 VA: 0x75945517a4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3980c VA: 0x759455180c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f39a14 VA: 0x7594551a14
	public Void .ctor() { }
}
```