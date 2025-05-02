# CheckEntitySuicide

**Namespace:** ` `


## Fields

- `ActionTargetType _entity`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEntitySuicide : ActionNode
{
	private ActionTargetType _entity; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2013c VA: 0x759453813c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f201a4 VA: 0x75945381a4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f202d8 VA: 0x75945382d8
	public Void .ctor() { }
}
```