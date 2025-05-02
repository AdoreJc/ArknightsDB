# FilterDamageModifer

**Namespace:** ` `


## Fields

- `Boolean _filterAttackType`

- `SourceAttackType _attackTypeFilter`

- `Boolean _filterDamageType`

- `DamageTypeMask _damageMask`

- `Boolean _filterSharedMask`

- `SharedFlagIndex _sharedFlag`

- `Boolean _filterModifierSource`

- `ActionTargetType _source`

- `Boolean _filterBySourceId`

- `String _sourceId`

- `Boolean _checkHasScource`

- `Boolean _isNoSource`

- `Boolean _filterModifierCancelled`


## Properties

- `Boolean filterModifierSource`

- `Boolean filterModifierSourceAndFilterBySourceId`


## Methods

- `Boolean get_filterModifierSource()`

- `Boolean get_filterModifierSourceAndFilterBySourceId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterDamageModifer : ActionNode
{
	private Boolean _filterAttackType; // 0x10
	private SourceAttackType _attackTypeFilter; // 0x14
	private Boolean _filterDamageType; // 0x18
	private DamageTypeMask _damageMask; // 0x1c
	private Boolean _filterSharedMask; // 0x20
	private SharedFlagIndex _sharedFlag; // 0x22
	private Boolean _filterModifierSource; // 0x24
	private ActionTargetType _source; // 0x28
	private Boolean _filterBySourceId; // 0x2c
	private String _sourceId; // 0x30
	private Boolean _checkHasScource; // 0x38
	private Boolean _isNoSource; // 0x39
	private Boolean _filterModifierCancelled; // 0x3a
	private static DelegateBridge __Hotfix0_get_filterModifierSource; // 0x0
	private static DelegateBridge __Hotfix0_get_filterModifierSourceAndFilterBySourceId; // 0x8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean filterModifierSource { get; }
	protected Boolean filterModifierSourceAndFilterBySourceId { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f20f3c VA: 0x7594538f3c
	public Boolean get_filterModifierSource() { }
	// RVA: 0x1f20fa4 VA: 0x7594538fa4
	protected Boolean get_filterModifierSourceAndFilterBySourceId() { }
	// RVA: 0x1f21024 VA: 0x7594539024
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2108c VA: 0x759453908c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f213e8 VA: 0x75945393e8
	public Void .ctor() { }
}
```