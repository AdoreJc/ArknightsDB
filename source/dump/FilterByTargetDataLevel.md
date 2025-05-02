# FilterByTargetDataLevel

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `CompareType _condType`

- `Int32 _level`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByTargetDataLevel : ActionNode
{
	private ActionTargetType _target; // 0x10
	private CompareType _condType; // 0x14
	private Int32 _level; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f20684 VA: 0x7594538684
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f206ec VA: 0x75945386ec
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f20928 VA: 0x7594538928
	public Void .ctor() { }
}
```