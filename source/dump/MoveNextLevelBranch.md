# MoveNextLevelBranch

**Namespace:** ` `


## Fields

- `Boolean _isLoop`

- `String _branchId`

- `Int32 _maxValidEnemyCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MoveNextLevelBranch : ActionNode
{
	private Boolean _isLoop; // 0x10
	private String _branchId; // 0x18
	private Int32 _maxValidEnemyCount; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f95d38 VA: 0x75945add38
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f95da0 VA: 0x75945adda0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f95f3c VA: 0x75945adf3c
	public Void .ctor() { }
}
```