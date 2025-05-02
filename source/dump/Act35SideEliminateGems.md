# Act35SideEliminateGems

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act35SideEliminateGems : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edf154 VA: 0x75944f7154
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edf1bc VA: 0x75944f71bc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edf390 VA: 0x75944f7390
	public Void .ctor() { }
}
```