# ExchangeHpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Boolean _isUndeadable`

- `Boolean _isSkipEvent`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ExchangeHpRatio : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Boolean _isUndeadable; // 0x18
	private Boolean _isSkipEvent; // 0x19
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fccf90 VA: 0x75945e4f90
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fccff8 VA: 0x75945e4ff8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcd338 VA: 0x75945e5338
	public Void .ctor() { }
}
```