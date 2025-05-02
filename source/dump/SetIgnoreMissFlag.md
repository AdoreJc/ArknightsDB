# SetIgnoreMissFlag

**Namespace:** ` `


## Fields

- `DamageTypeMask _ignoreMissFlag`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetIgnoreMissFlag : ActionNode
{
	private DamageTypeMask _ignoreMissFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f73c80 VA: 0x759458bc80
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f73ce8 VA: 0x759458bce8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f73dc0 VA: 0x759458bdc0
	public Void .ctor() { }
}
```