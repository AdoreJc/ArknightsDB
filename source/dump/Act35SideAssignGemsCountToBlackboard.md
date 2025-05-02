# Act35SideAssignGemsCountToBlackboard

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`

- `Boolean _excludeLinkGems`

- `String _blackboardKey`

- `String _maxCountKey`

- `Int32 _maxCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act35SideAssignGemsCountToBlackboard : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private Boolean _excludeLinkGems; // 0x1c
	private String _blackboardKey; // 0x20
	private String _maxCountKey; // 0x28
	private Int32 _maxCount; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edf74c VA: 0x75944f774c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edf7b4 VA: 0x75944f77b4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edf9e0 VA: 0x75944f79e0
	public Void .ctor() { }
}
```