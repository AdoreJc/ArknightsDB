# GroupSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _limitTargetNum`

- `Int32 _maxNum`

- `String _maxNumBlackboardKey`

- `RangeSelector _overrideSelector`

- `Boolean _selectable`

- `Int32 m_maxTargetNum`


## Properties

- `Boolean limitTargetNum`


## Methods

- `Boolean get_limitTargetNum()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Boolean <>xLuaBaseProxy_VerifyTarget(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GroupSelector : RangeSelector
{
	private List`1 _rangeSelectorsList; // 0xa0
	private Boolean _limitTargetNum; // 0xa8
	private Int32 _maxNum; // 0xac
	private String _maxNumBlackboardKey; // 0xb0
	private RangeSelector _overrideSelector; // 0xb8
	private Boolean _selectable; // 0xc0
	private Int32 m_maxTargetNum; // 0xc4
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
	private static DelegateBridge __Hotfix0_VerifyTarget; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	protected Boolean limitTargetNum { get; }
	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	public override Boolean ignoreTargetFree { get; }

	// RVA: 0x1bb25ec VA: 0x75941ca5ec
	protected Boolean get_limitTargetNum() { }
	// RVA: 0x1bb2654 VA: 0x75941ca654
	public override SideType get_targetSide() { }
	// RVA: 0x1bb271c VA: 0x75941ca71c
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1bb27e4 VA: 0x75941ca7e4
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1bb28ac VA: 0x75941ca8ac
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1bb2974 VA: 0x75941ca974
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bb2b78 VA: 0x75941cab78
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1bb2dbc VA: 0x75941cadbc
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bb314c VA: 0x75941cb14c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb3204 VA: 0x75941cb204
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb32bc VA: 0x75941cb2bc
	public override Boolean VerifyTarget(List`1 candidates) { }
	// RVA: 0x1bb3374 VA: 0x75941cb374
	public Void .ctor() { }
	// RVA: 0x1bb3420 VA: 0x75941cb420
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1bb3428 VA: 0x75941cb428
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1bb3430 VA: 0x75941cb430
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
	// RVA: 0x1bb3438 VA: 0x75941cb438
	private Boolean <>xLuaBaseProxy_VerifyTarget(List`1 P0) { }
}
```