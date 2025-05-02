# DuelSyncChosenInfoToGameMode

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _rangeId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DuelSyncChosenInfoToGameMode : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _rangeId; // 0x18
	private String[] _excludeIds; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f81764 VA: 0x7594599764
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f817cc VA: 0x75945997cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f81f7c VA: 0x7594599f7c
	public Void .ctor() { }
}
```