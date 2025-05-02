# FootballPlayerForceSearchTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isActive`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FootballPlayerForceSearchTarget : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _isActive; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f506d0 VA: 0x75945686d0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f50738 VA: 0x7594568738
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f508ac VA: 0x75945688ac
	public Void .ctor() { }
}
```