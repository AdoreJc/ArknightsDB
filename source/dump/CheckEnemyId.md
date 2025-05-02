# CheckEnemyId

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isUnset`

- `Boolean _loadIdFromBb`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyId : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String[] _filterIds; // 0x18
	private Boolean _isUnset; // 0x20
	private Boolean _loadIdFromBb; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f19ae0 VA: 0x7594531ae0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f19b48 VA: 0x7594531b48
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f19d78 VA: 0x7594531d78
	public Void .ctor() { }
}
```