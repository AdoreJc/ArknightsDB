# RegisterMagicCircuitSpAffect

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isTwoEntriesOnly`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RegisterMagicCircuitSpAffect : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _isTwoEntriesOnly; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6d678 VA: 0x7594585678
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6d6e0 VA: 0x75945856e0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6d8dc VA: 0x75945858dc
	public Void .ctor() { }
}
```