# CheckFilterTag

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _filterTag`

- `String _bbKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckFilterTag : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _filterTag; // 0x18
	private String _bbKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f19870 VA: 0x7594531870
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f198d8 VA: 0x75945318d8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f19a40 VA: 0x7594531a40
	public Void .ctor() { }
}
```