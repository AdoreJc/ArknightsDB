# ChainedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `SideType _targetSide`

- `MotionMask _targetMotion`

- `EntityCategory _targetCategory`

- `Boolean _ignoreTargetFree`

- `Int32 _maxTarget`

- `Boolean _excludeOwner`

- `Boolean _useChainPrefix`

- `Int32 m_maxTarget`


## Properties

- `Boolean isAlly`


## Methods

- `Boolean get_isAlly()`

- `Entity FindNearestTarget(List`1, Vector2)`

- `Int32 _GetNearestTargetIndex(List`1, Vector2)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ChainedSelector : RangeSelector
{
	private SideType _targetSide; // 0xa0
	private MotionMask _targetMotion; // 0xa4
	private EntityCategory _targetCategory; // 0xa8
	private Boolean _ignoreTargetFree; // 0xac
	private Int32 _maxTarget; // 0xb0
	protected Boolean _excludeOwner; // 0xb4
	private Boolean _useChainPrefix; // 0xb5
	private List`1 m_targets; // 0xb8
	private Int32 m_maxTarget; // 0xc0
	private static DelegateBridge __Hotfix0_get_isAlly; // 0x0
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x8
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x10
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x18
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x20
	private static DelegateBridge __Hotfix0_SetData; // 0x28
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x30
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x38
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x40
	private static DelegateBridge __Hotfix0_FindNearestTarget; // 0x48
	private static DelegateBridge __Hotfix0__GetNearestTargetIndex; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private Boolean isAlly { get; }
	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	public override Boolean ignoreTargetFree { get; }

	// RVA: 0x1ba6e20 VA: 0x75941bee20
	private Boolean get_isAlly() { }
	// RVA: 0x1ba6e90 VA: 0x75941bee90
	public override SideType get_targetSide() { }
	// RVA: 0x1ba6ef8 VA: 0x75941beef8
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1ba6f60 VA: 0x75941bef60
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1ba6fc8 VA: 0x75941befc8
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1ba7030 VA: 0x75941bf030
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ba712c VA: 0x75941bf12c
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1ba78c8 VA: 0x75941bf8c8
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1ba7940 VA: 0x75941bf940
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1ba77b4 VA: 0x75941bf7b4
	private Entity FindNearestTarget(List`1 targets, Vector2 pos) { }
	// RVA: 0x1ba79b8 VA: 0x75941bf9b8
	private Int32 _GetNearestTargetIndex(List`1 targets, Vector2 center) { }
	// RVA: 0x1ba7d38 VA: 0x75941bfd38
	public Void .ctor() { }
	// RVA: 0x1ba7dfc VA: 0x75941bfdfc
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ba7e04 VA: 0x75941bfe04
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
}
```