# AutochessCheckTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _checkTargetIsBlackboardInstID`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutochessCheckTarget : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _checkTargetIsBlackboardInstID; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee3898 VA: 0x75944fb898
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee3900 VA: 0x75944fb900
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee3b40 VA: 0x75944fbb40
	public Void .ctor() { }
}
```