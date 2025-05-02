# Act35SideCheckIfOnGemsTile

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`

- `Boolean _excludeLinkGems`

- `Boolean _checkNotOn`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act35SideCheckIfOnGemsTile : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private Boolean _excludeLinkGems; // 0x1c
	private Boolean _checkNotOn; // 0x1d
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edfae8 VA: 0x75944f7ae8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edfb50 VA: 0x75944f7b50
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edfd8c VA: 0x75944f7d8c
	public Void .ctor() { }
}
```