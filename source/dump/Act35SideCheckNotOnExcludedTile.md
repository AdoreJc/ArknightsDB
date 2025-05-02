# Act35SideCheckNotOnExcludedTile

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act35SideCheckNotOnExcludedTile : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edfe34 VA: 0x75944f7e34
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edfe9c VA: 0x75944f7e9c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee0074 VA: 0x75944f8074
	public Void .ctor() { }
}
```