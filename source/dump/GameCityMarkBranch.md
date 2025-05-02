# GameCityMarkBranch

**Namespace:** ` `


## Fields

- `String _branchId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GameCityMarkBranch : ActionNode
{
	private String _branchId; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f54db0 VA: 0x759456cdb0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f54e18 VA: 0x759456ce18
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f54fd0 VA: 0x759456cfd0
	public Void .ctor() { }
}
```