# Transport

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Boolean _isBidirectional`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Transport : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Boolean _isBidirectional; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd158c VA: 0x75945e958c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd15f4 VA: 0x75945e95f4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd1adc VA: 0x75945e9adc
	public Void .ctor() { }
}
```