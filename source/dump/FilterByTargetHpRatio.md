# FilterByTargetHpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `CompareType _condType`

- `Single _value`

- `Boolean _useSourceHpRatio`

- `ActionTargetType _sourceType`

- `String _blackboardPrefix`


## Properties

- `Boolean useSourceHpRatio`


## Methods

- `Boolean get_useSourceHpRatio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByTargetHpRatio : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private CompareType _condType; // 0x14
	private Single _value; // 0x18
	private Boolean _useSourceHpRatio; // 0x1c
	private ActionTargetType _sourceType; // 0x20
	private String _blackboardPrefix; // 0x28
	private static DelegateBridge __Hotfix0_get_useSourceHpRatio; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Boolean useSourceHpRatio { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f16b70 VA: 0x759452eb70
	private Boolean get_useSourceHpRatio() { }
	// RVA: 0x1f16bd8 VA: 0x759452ebd8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f16c40 VA: 0x759452ec40
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f16f08 VA: 0x759452ef08
	public Void .ctor() { }
}
```