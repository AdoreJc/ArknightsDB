# FilterEPBreakRecoveryType

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ElementType _recoveryType`

- `Boolean _skipInEPBreakRecoveryCheck`


## Methods

- `Boolean _IsNotInBreakRecoveryCheck(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterEPBreakRecoveryType : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ElementType _recoveryType; // 0x14
	private Boolean _skipInEPBreakRecoveryCheck; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0__IsNotInBreakRecoveryCheck; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f31684 VA: 0x7594549684
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f316ec VA: 0x75945496ec
	private Boolean _IsNotInBreakRecoveryCheck(Entity target) { }
	// RVA: 0x1f317f0 VA: 0x75945497f0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f318f8 VA: 0x75945498f8
	public Void .ctor() { }
}
```