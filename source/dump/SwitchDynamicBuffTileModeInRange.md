# SwitchDynamicBuffTileModeInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Operation _operation`

- `Boolean _requireCharacterNotOn`

- `Int32 _modeIndex`

- `String _decBbKey`

- `String _rangeId`

- `String _effectKeyOnTile`

- `Boolean _useRangeRadius`

- `Single _rangeRadius`

- `String _rangeRadiusKey`

- `Boolean _assignChangedCountToBb`

- `String _countBbKey`


## Properties

- `Boolean assignChangedCountToBb`


## Methods

- `Boolean get_assignChangedCountToBb()`

- `Void GatherEffects(List`1)`

- `Int32 <Execute>b__18_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchDynamicBuffTileModeInRange : ActionNode, IEffectSource
{
	private ActionTargetType _sourceType; // 0x10
	private Operation _operation; // 0x14
	private Boolean _requireCharacterNotOn; // 0x18
	private Int32 _modeIndex; // 0x1c
	private String _decBbKey; // 0x20
	private String _rangeId; // 0x28
	private String _effectKeyOnTile; // 0x30
	private Boolean _useRangeRadius; // 0x38
	private Single _rangeRadius; // 0x3c
	private String _rangeRadiusKey; // 0x40
	private Boolean _assignChangedCountToBb; // 0x48
	private String _countBbKey; // 0x50
	private static DelegateBridge __Hotfix0_get_assignChangedCountToBb; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean assignChangedCountToBb { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fe2314 VA: 0x75945fa314
	public Boolean get_assignChangedCountToBb() { }
	// RVA: 0x1fe237c VA: 0x75945fa37c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1fe2490 VA: 0x75945fa490
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe24f8 VA: 0x75945fa4f8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe2b50 VA: 0x75945fab50
	public Void .ctor() { }
	// RVA: 0x1fe2c84 VA: 0x75945fac84
	private Int32 <Execute>b__18_1(Int32 modeIndex) { }
}
```