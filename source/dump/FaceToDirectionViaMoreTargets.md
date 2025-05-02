# FaceToDirectionViaMoreTargets

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `TargetOptions _targetOptions`

- `String _rangeId`

- `Boolean _checkBuildableType`

- `BuildableType _buildableType`


## Methods

- `Boolean <Execute>b__7_0(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FaceToDirectionViaMoreTargets : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private TargetOptions _targetOptions; // 0x18
	private String _rangeId; // 0x78
	private Boolean _checkBuildableType; // 0x80
	private BuildableType _buildableType; // 0x84
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc7ccc VA: 0x75945dfccc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc7d34 VA: 0x75945dfd34
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc8070 VA: 0x75945e0070
	public Void .ctor() { }
	// RVA: 0x1fc80e8 VA: 0x75945e00e8
	private Boolean <Execute>b__7_0(Entity entity) { }
}
```