# CheckAbnormalFlag

**Namespace:** ` `


## Fields

- `AbnormalFlag _abnormalFlag`

- `ActionTargetType _targetType`

- `Boolean _isUnset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckAbnormalFlag : ActionNode
{
	private AbnormalFlag _abnormalFlag; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Boolean _isUnset; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f18a5c VA: 0x7594530a5c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f18ac4 VA: 0x7594530ac4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f18c0c VA: 0x7594530c0c
	public Void .ctor() { }
}
```