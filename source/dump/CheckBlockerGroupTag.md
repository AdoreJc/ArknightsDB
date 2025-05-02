# CheckBlockerGroupTag

**Namespace:** ` `


## Fields

- `String _tag`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckBlockerGroupTag : ActionNode
{
	private String _tag; // 0x10
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f15ee4 VA: 0x759452dee4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f15f4c VA: 0x759452df4c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1615c VA: 0x759452e15c
	public Void .ctor() { }
}
```