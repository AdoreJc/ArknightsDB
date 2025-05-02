# CheckIsTrackTargetEnemy

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckIsTrackTargetEnemy : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f51d0c VA: 0x7594569d0c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f51d74 VA: 0x7594569d74
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f51ecc VA: 0x7594569ecc
	public Void .ctor() { }
}
```