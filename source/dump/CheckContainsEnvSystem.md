# CheckContainsEnvSystem

**Namespace:** ` `


## Fields

- `String _envSysKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckContainsEnvSystem : ActionNode
{
	private String _envSysKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2f4ac VA: 0x75945474ac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2f514 VA: 0x7594547514
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2f648 VA: 0x7594547648
	public Void .ctor() { }
}
```