# ChainedSelectorWithFilter

**Namespace:** `Torappu.Battle`


## Fields

- `SideType _targetSide`

- `MotionMask _targetMotion`

- `EntityCategory _targetCategory`

- `Boolean _ignoreTargetFree`

- `Int32 _maxTarget`

- `FilterType _filterType`

- `Boolean _useChainPrefix`

- `Boolean _useAdditionalTargetCount`

- `Boolean _ignoreHealFree`

- `Boolean _ignoreAllyTargetFree`

- `TargetValidator _freeJumpValidator`

- `TargetValidator _extraValidator`

- `Entity m_lastTarget`

- `Int32 m_maxTarget`

- `Boolean m_validatorInited`


## Properties

- `TargetValidator freeJumpValidator`

- `TargetValidator extraValidator`


## Methods

- `TargetValidator get_freeJumpValidator()`

- `TargetValidator get_extraValidator()`

- `Entity _PickTarget(List`1)`

- `Boolean _IsFreeJump(Entity)`

- `Void _InitValidatorsIfNot()`

- `Boolean <>xLuaBaseProxy_get_ignoreHealFree()`

- `Boolean <>xLuaBaseProxy_get_ignoreAllyTargetFree()`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ChainedSelectorWithFilter : RangeSelector
{
	private SideType _targetSide; // 0xa0
	private MotionMask _targetMotion; // 0xa4
	private EntityCategory _targetCategory; // 0xa8
	private Boolean _ignoreTargetFree; // 0xac
	private Int32 _maxTarget; // 0xb0
	private FilterType _filterType; // 0xb4
	private Boolean _useChainPrefix; // 0xb8
	private Boolean _useAdditionalTargetCount; // 0xb9
	private Boolean _ignoreHealFree; // 0xba
	private Boolean _ignoreAllyTargetFree; // 0xbb
	private TargetValidator _freeJumpValidator; // 0xc0
	private TargetValidator _extraValidator; // 0xc8
	private List`1 m_targets; // 0xd0
	private Entity m_lastTarget; // 0xd8
	private Int32 m_maxTarget; // 0xe0
	private Boolean m_validatorInited; // 0xe4
	private static DelegateBridge __Hotfix0_get_freeJumpValidator; // 0x0
	private static DelegateBridge __Hotfix0_get_extraValidator; // 0x8
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x10
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x18
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x20
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x28
	private static DelegateBridge __Hotfix0_get_ignoreHealFree; // 0x30
	private static DelegateBridge __Hotfix0_get_ignoreAllyTargetFree; // 0x38
	private static DelegateBridge __Hotfix0_SetData; // 0x40
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x48
	private static DelegateBridge __Hotfix0__PickTarget; // 0x50
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x58
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x60
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x68
	private static DelegateBridge __Hotfix0__IsFreeJump; // 0x70
	private static DelegateBridge __Hotfix0__InitValidatorsIfNot; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	private TargetValidator freeJumpValidator { get; }
	private TargetValidator extraValidator { get; }
	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	public override Boolean ignoreTargetFree { get; }
	protected override Boolean ignoreHealFree { get; }
	protected override Boolean ignoreAllyTargetFree { get; }

	// RVA: 0x1ba7e0c VA: 0x75941bfe0c
	private TargetValidator get_freeJumpValidator() { }
	// RVA: 0x1ba7ffc VA: 0x75941bfffc
	private TargetValidator get_extraValidator() { }
	// RVA: 0x1ba806c VA: 0x75941c006c
	public override SideType get_targetSide() { }
	// RVA: 0x1ba80d4 VA: 0x75941c00d4
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1ba813c VA: 0x75941c013c
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1ba81a4 VA: 0x75941c01a4
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1ba820c VA: 0x75941c020c
	protected override Boolean get_ignoreHealFree() { }
	// RVA: 0x1ba8274 VA: 0x75941c0274
	protected override Boolean get_ignoreAllyTargetFree() { }
	// RVA: 0x1ba82dc VA: 0x75941c02dc
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ba8440 VA: 0x75941c0440
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1ba8b64 VA: 0x75941c0b64
	private Entity _PickTarget(List`1 targets) { }
	// RVA: 0x1ba8c80 VA: 0x75941c0c80
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1ba8db0 VA: 0x75941c0db0
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1ba8e28 VA: 0x75941c0e28
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1ba8a80 VA: 0x75941c0a80
	private Boolean _IsFreeJump(Entity target) { }
	// RVA: 0x1ba7e7c VA: 0x75941bfe7c
	private Void _InitValidatorsIfNot() { }
	// RVA: 0x1ba8ea0 VA: 0x75941c0ea0
	public Void .ctor() { }
	// RVA: 0x1ba8f64 VA: 0x75941c0f64
	private Boolean <>xLuaBaseProxy_get_ignoreHealFree() { }
	// RVA: 0x1ba8f6c VA: 0x75941c0f6c
	private Boolean <>xLuaBaseProxy_get_ignoreAllyTargetFree() { }
	// RVA: 0x1ba8f74 VA: 0x75941c0f74
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ba8f7c VA: 0x75941c0f7c
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
	// RVA: 0x1ba8f84 VA: 0x75941c0f84
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```