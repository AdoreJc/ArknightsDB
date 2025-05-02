# ParallelGroupSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _sortAsSelectorOrder`

- `FilterType _postFilter`

- `Boolean _sortByTauntAtLast`

- `Boolean _limitTargetNum`

- `Int32 _maxNum`

- `String _maxNumBlackboardKey`

- `Boolean _fixParentReset`

- `Boolean _excludedIdAtLast`

- `Boolean _onlyResizeWhenFilter`

- `Int32 m_maxTargetNum`


## Properties

- `Boolean limitTargetNum`

- `Boolean excludedIdAtLast`

- `Boolean notSortAsSelectorOrder`


## Methods

- `Boolean get_limitTargetNum()`

- `Boolean get_excludedIdAtLast()`

- `Boolean get_notSortAsSelectorOrder()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnAbilityExtendUpdated(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ParallelGroupSelector : RangeSelector
{
	private TargetSelector[] _selectorGroup; // 0xa0
	private Boolean _sortAsSelectorOrder; // 0xa8
	protected FilterType _postFilter; // 0xac
	protected Boolean _sortByTauntAtLast; // 0xb0
	private Boolean _limitTargetNum; // 0xb1
	private Int32 _maxNum; // 0xb4
	private String _maxNumBlackboardKey; // 0xb8
	private Boolean _fixParentReset; // 0xc0
	private Boolean _excludedIdAtLast; // 0xc1
	private List`1 _excludedIds; // 0xc8
	private Boolean _onlyResizeWhenFilter; // 0xd0
	private Int32 m_maxTargetNum; // 0xd4
	private static DelegateBridge __Hotfix0_get_limitTargetNum; // 0x0
	private static DelegateBridge __Hotfix0_get_excludedIdAtLast; // 0x8
	private static DelegateBridge __Hotfix0_get_notSortAsSelectorOrder; // 0x10
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x18
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x20
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x28
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x30
	private static DelegateBridge __Hotfix0_Reset; // 0x38
	private static DelegateBridge __Hotfix0_SetData; // 0x40
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x48
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x50
	private static DelegateBridge __Hotfix0_OnAbilityExtendUpdated; // 0x58
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	protected Boolean limitTargetNum { get; }
	protected Boolean excludedIdAtLast { get; }
	public Boolean notSortAsSelectorOrder { get; }
	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	public override Boolean ignoreTargetFree { get; }

	// RVA: 0x1bb4ed8 VA: 0x75941cced8
	protected Boolean get_limitTargetNum() { }
	// RVA: 0x1bb4f40 VA: 0x75941ccf40
	protected Boolean get_excludedIdAtLast() { }
	// RVA: 0x1bb4fa8 VA: 0x75941ccfa8
	public Boolean get_notSortAsSelectorOrder() { }
	// RVA: 0x1bb5018 VA: 0x75941cd018
	public override SideType get_targetSide() { }
	// RVA: 0x1bb507c VA: 0x75941cd07c
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1bb50e0 VA: 0x75941cd0e0
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1bb5144 VA: 0x75941cd144
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1bb51a8 VA: 0x75941cd1a8
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bb5354 VA: 0x75941cd354
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1bb54d0 VA: 0x75941cd4d0
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bb5908 VA: 0x75941cd908
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb5c30 VA: 0x75941cdc30
	public override Void OnAbilityExtendUpdated(FP extend) { }
	// RVA: 0x1bb5db0 VA: 0x75941cddb0
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb5e28 VA: 0x75941cde28
	public Void .ctor() { }
	// RVA: 0x1bb5f30 VA: 0x75941cdf30
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1bb5f38 VA: 0x75941cdf38
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1bb5f40 VA: 0x75941cdf40
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
	// RVA: 0x1bb5f48 VA: 0x75941cdf48
	private Void <>xLuaBaseProxy_OnAbilityExtendUpdated(FP P0) { }
}
```