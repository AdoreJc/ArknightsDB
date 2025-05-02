# DamageFixedValueResistance

**Namespace:** ` `


## Fields

- `Boolean _filterDamageType`

- `DamageTypeMask _damageMask`

- `Single _fixedValue`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageFixedValueResistance : ActionNode
{
	private Boolean _filterDamageType; // 0x10
	private DamageTypeMask _damageMask; // 0x14
	private Single _fixedValue; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f452a4 VA: 0x759455d2a4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4530c VA: 0x759455d30c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f45574 VA: 0x759455d574
	public Void .ctor() { }
}
```