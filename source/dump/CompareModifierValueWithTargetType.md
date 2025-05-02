# CompareModifierValueWithTargetType

**Namespace:** ` `


## Fields

- `ActionTargetType _modifierTarget`

- `CompareType _condType`

- `TargetType _targetType`

- `Boolean _ignoreEs`

- `Boolean _useMaxRatio`

- `Single _ratio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CompareModifierValueWithTargetType : ActionNode
{
	private ActionTargetType _modifierTarget; // 0x10
	private CompareType _condType; // 0x14
	private TargetType _targetType; // 0x18
	private Boolean _ignoreEs; // 0x1c
	private Boolean _useMaxRatio; // 0x1d
	private Single _ratio; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f73660 VA: 0x759458b660
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f736c8 VA: 0x759458b6c8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f73a54 VA: 0x759458ba54
	public Void .ctor() { }
}
```