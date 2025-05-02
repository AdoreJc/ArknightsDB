# AtkAdditionUpBeforeCalcDamage

**Namespace:** ` `


## Fields

- `Boolean _filterDamageType`

- `DamageType _damageType`

- `Single _defaultValue`

- `String _atkAdditionKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AtkAdditionUpBeforeCalcDamage : ActionNode
{
	private Boolean _filterDamageType; // 0x10
	private DamageType _damageType; // 0x14
	private Single _defaultValue; // 0x18
	private String _atkAdditionKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f41180 VA: 0x7594559180
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f411e8 VA: 0x75945591e8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f41330 VA: 0x7594559330
	public Void .ctor() { }
}
```