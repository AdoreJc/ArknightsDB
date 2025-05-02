# DamageScale

**Namespace:** ` `


## Fields

- `Boolean _filterDamageType`

- `DamageTypeMask _damageMask`

- `Boolean _filterApplyWay`

- `SourceApplyWay _applyWayFilter`

- `Boolean _isOneMinus`

- `Boolean _isStackable`

- `Boolean _isValidStackCnt`

- `String _cachedDeltaValueToBBKey`

- `String _customKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DamageScale : ActionNode
{
	private Boolean _filterDamageType; // 0x10
	private DamageTypeMask _damageMask; // 0x14
	private Boolean _filterApplyWay; // 0x18
	private SourceApplyWay _applyWayFilter; // 0x1c
	private Boolean _isOneMinus; // 0x20
	private Boolean _isStackable; // 0x21
	private Boolean _isValidStackCnt; // 0x22
	private String _cachedDeltaValueToBBKey; // 0x28
	private String _customKey; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f43f0c VA: 0x759455bf0c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f43f74 VA: 0x759455bf74
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f444f0 VA: 0x759455c4f0
	public Void .ctor() { }
}
```