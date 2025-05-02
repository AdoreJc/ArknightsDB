# SetAtkScaleZero

**Namespace:** ` `


## Fields

- `Boolean _filterApplyWay`

- `SourceApplyWay _applyWay`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetAtkScaleZero : ActionNode
{
	private Boolean _filterApplyWay; // 0x10
	private SourceApplyWay _applyWay; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f4a070 VA: 0x7594562070
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4a0d8 VA: 0x75945620d8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4a218 VA: 0x7594562218
	public Void .ctor() { }
}
```