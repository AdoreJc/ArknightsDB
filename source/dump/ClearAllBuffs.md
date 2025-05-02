# ClearAllBuffs

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _alsoRemoveDurableBuff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ClearAllBuffs : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private List`1 _retainedBuffsWhenClear; // 0x18
	private Boolean _alsoRemoveDurableBuff; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f01640 VA: 0x7594519640
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f016a8 VA: 0x75945196a8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0183c VA: 0x759451983c
	public Void .ctor() { }
}
```