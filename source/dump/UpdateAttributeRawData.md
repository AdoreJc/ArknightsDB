# UpdateAttributeRawData

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `AttributeType _attributeType`

- `String _valueKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UpdateAttributeRawData : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private AttributeType _attributeType; // 0x14
	private String _valueKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f35d70 VA: 0x759454dd70
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f35dd8 VA: 0x759454ddd8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f35f8c VA: 0x759454df8c
	public Void .ctor() { }
}
```