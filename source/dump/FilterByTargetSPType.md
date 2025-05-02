# FilterByTargetSPType

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `SpType _spType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByTargetSPType : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private SpType _spType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2ebdc VA: 0x7594546bdc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2ec44 VA: 0x7594546c44
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2ed84 VA: 0x7594546d84
	public Void .ctor() { }
}
```