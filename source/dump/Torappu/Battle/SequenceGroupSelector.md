# SequenceGroupSelector

**Namespace:** `Torappu.Battle`


## Fields

- `RangeSelector _firstOrderSelector`

- `RangeSelector _appendOrderSelector`

- `Boolean _limitTargetNum`

- `Int32 _maxNum`

- `String _maxNumBlackboardKey`

- `Int32 m_maxTargetNum`


## Properties

- `Boolean limitTargetNum`


## Methods

- `Boolean get_limitTargetNum()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SequenceGroupSelector : RangeSelector
{
	private RangeSelector _firstOrderSelector; // 0xa0
	private RangeSelector _appendOrderSelector; // 0xa8
	private Boolean _limitTargetNum; // 0xb0
	private Int32 _maxNum; // 0xb4
	private String _maxNumBlackboardKey; // 0xb8
	private Int32 m_maxTargetNum; // 0xc0
	private static DelegateBridge __Hotfix0_get_limitTargetNum; // 0x0
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x8
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x10
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x18
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge __Hotfix0_SetData; // 0x30
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x38
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x40
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	protected Boolean limitTargetNum { get; }
	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	public override Boolean ignoreTargetFree { get; }

	// RVA: 0x1bbb008 VA: 0x75941d3008
	protected Boolean get_limitTargetNum() { }
	// RVA: 0x1bbb070 VA: 0x75941d3070
	public override SideType get_targetSide() { }
	// RVA: 0x1bbb0d4 VA: 0x75941d30d4
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1bbb138 VA: 0x75941d3138
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1bbb19c VA: 0x75941d319c
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1bbb200 VA: 0x75941d3200
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bbb34c VA: 0x75941d334c
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1bbb4a0 VA: 0x75941d34a0
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bbbaf0 VA: 0x75941d3af0
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bbbba8 VA: 0x75941d3ba8
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bbbc20 VA: 0x75941d3c20
	public Void .ctor() { }
	// RVA: 0x1bbbcc8 VA: 0x75941d3cc8
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1bbbccc VA: 0x75941d3ccc
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1bbbcd0 VA: 0x75941d3cd0
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
}
```