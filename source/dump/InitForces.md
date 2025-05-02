# InitForces

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _passBallForceKey`

- `String _slapShotForceKey`

- `String _clearanceForceKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InitForces : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _passBallForceKey; // 0x18
	private String _slapShotForceKey; // 0x20
	private String _clearanceForceKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f50924 VA: 0x7594568924
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5098c VA: 0x759456898c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f50bb0 VA: 0x7594568bb0
	public Void .ctor() { }
}
```