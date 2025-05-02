# CheckCost

**Namespace:** ` `


## Fields

- `CompareType _compareType`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCost : ActionNode
{
	private CompareType _compareType; // 0x10
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f21460 VA: 0x7594539460
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f214c8 VA: 0x75945394c8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f21750 VA: 0x7594539750
	public Void .ctor() { }
}
```