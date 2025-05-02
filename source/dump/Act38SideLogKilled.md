# Act38SideLogKilled

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`

- `Boolean _isKilledByBoss`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act38SideLogKilled : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private Boolean _isKilledByBoss; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee0ff4 VA: 0x75944f8ff4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee105c VA: 0x75944f905c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee11f8 VA: 0x75944f91f8
	public Void .ctor() { }
}
```