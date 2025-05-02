# Act31SideCheckInPolluteArea

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act31SideCheckInPolluteArea : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edbb80 VA: 0x75944f3b80
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edbbe8 VA: 0x75944f3be8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edbe14 VA: 0x75944f3e14
	public Void .ctor() { }
}
```