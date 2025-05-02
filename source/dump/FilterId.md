# FilterId

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _filterId`

- `Boolean _isUnset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterId : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _filterId; // 0x18
	private Boolean _isUnset; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1a044 VA: 0x7594532044
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1a0ac VA: 0x75945320ac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1a1ec VA: 0x75945321ec
	public Void .ctor() { }
}
```