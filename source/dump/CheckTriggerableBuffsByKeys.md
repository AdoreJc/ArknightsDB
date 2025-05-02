# CheckTriggerableBuffsByKeys

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _excludeThisBuff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTriggerableBuffsByKeys : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _excludeThisBuff; // 0x14
	private String[] _buffKeys; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1effccc VA: 0x7594517ccc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1effd34 VA: 0x7594517d34
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1effeac VA: 0x7594517eac
	public Void .ctor() { }
}
```