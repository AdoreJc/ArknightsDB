# NearestRangeSelector

**Namespace:** `Torappu.Battle`


## Fields

- `SideType _targetSide`

- `MotionMask _targetMotion`

- `EntityCategory _targetCategory`

- `Boolean _ignoreTargetFree`

- `Boolean _limitTargetNum`

- `Int32 _maxTargetNum`

- `Int32 m_maxTargetNum`


## Properties

- `Boolean IsLimitTargetNum`


## Methods

- `Boolean get_IsLimitTargetNum()`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class NearestRangeSelector : RangeSelector
{
	private SideType _targetSide; // 0xa0
	private MotionMask _targetMotion; // 0xa4
	private EntityCategory _targetCategory; // 0xa8
	private Boolean _ignoreTargetFree; // 0xac
	private Boolean _limitTargetNum; // 0xad
	private Int32 _maxTargetNum; // 0xb0
	private Int32 m_maxTargetNum; // 0xb4
	private static DelegateBridge __Hotfix0_get_IsLimitTargetNum; // 0x0
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x8
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x10
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x18
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x20
	private static DelegateBridge __Hotfix0_SetData; // 0x28
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x30
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x38
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Boolean IsLimitTargetNum { get; }
	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	public override Boolean ignoreTargetFree { get; }

	// RVA: 0x1bb395c VA: 0x75941cb95c
	private Boolean get_IsLimitTargetNum() { }
	// RVA: 0x1bb39c4 VA: 0x75941cb9c4
	public override SideType get_targetSide() { }
	// RVA: 0x1bb3a2c VA: 0x75941cba2c
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1bb3a94 VA: 0x75941cba94
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1bb3afc VA: 0x75941cbafc
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1bb3b64 VA: 0x75941cbb64
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1bb3c40 VA: 0x75941cbc40
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bb3e50 VA: 0x75941cbe50
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb3ec8 VA: 0x75941cbec8
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb3f40 VA: 0x75941cbf40
	public Void .ctor() { }
	// RVA: 0x1bb3fbc VA: 0x75941cbfbc
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1bb3fc4 VA: 0x75941cbfc4
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
}
```