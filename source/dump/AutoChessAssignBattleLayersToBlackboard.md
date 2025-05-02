# AutoChessAssignBattleLayersToBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKeys`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessAssignBattleLayersToBlackboard : ActionNode
{
	private String _blackboardKeys; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee6930 VA: 0x75944fe930
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee6998 VA: 0x75944fe998
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee6b30 VA: 0x75944feb30
	public Void .ctor() { }
}
```