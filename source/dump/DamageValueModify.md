# DamageValueModify

**Namespace:** ` `


## Fields

- `Boolean _filterDamageType`

- `DamageTypeMask _damageMask`

- `Boolean _filterApplyWay`

- `SourceApplyWay _applyWayFilter`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageValueModify : ActionNode
{
	private Boolean _filterDamageType; // 0x10
	private DamageTypeMask _damageMask; // 0x14
	private Boolean _filterApplyWay; // 0x18
	private SourceApplyWay _applyWayFilter; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f445b0 VA: 0x759455c5b0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f44618 VA: 0x759455c618
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f44850 VA: 0x759455c850
	public Void .ctor() { }
}
```