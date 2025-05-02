# FilterLevelId

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterLevelId : ActionNode
{
	private String[] _levelIds; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f62164 VA: 0x759457a164
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f621cc VA: 0x759457a1cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f622ec VA: 0x759457a2ec
	public Void .ctor() { }
}
```