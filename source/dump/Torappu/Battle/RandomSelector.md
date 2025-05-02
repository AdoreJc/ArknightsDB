# RandomSelector

**Namespace:** `Torappu.Battle`


## Fields

- `SideType _targetSide`

- `MotionMask _targetMotion`

- `EntityCategory _targetCategory`

- `Int32 _selectNum`

- `Boolean _excludeSelf`

- `Boolean _alwaysAppendSelf`

- `Boolean _ignoreTargetFree`

- `Boolean _ignoreHealFree`

- `Boolean _needProfessionMask`

- `ProfessionCategory _professionMask`

- `Int32 m_selectNum`


## Properties

- `Boolean limitTargetNum`

- `Boolean excludeSelf`

- `Int32 selectNum`

- `Boolean alwaysAppendSelf`

- `Boolean needProfessionMask`


## Methods

- `Boolean get_limitTargetNum()`

- `Boolean get_excludeSelf()`

- `Int32 get_selectNum()`

- `Boolean get_alwaysAppendSelf()`

- `Boolean get_needProfessionMask()`

- `Boolean <>xLuaBaseProxy_get_ignoreHealFree()`

- `ProfessionCategory <>xLuaBaseProxy_get_professionMask()`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RandomSelector : RangeSelector
{
	private SideType _targetSide; // 0xa0
	private MotionMask _targetMotion; // 0xa4
	private EntityCategory _targetCategory; // 0xa8
	private Int32 _selectNum; // 0xac
	private Boolean _excludeSelf; // 0xb0
	private Boolean _alwaysAppendSelf; // 0xb1
	private Boolean _ignoreTargetFree; // 0xb2
	private Boolean _ignoreHealFree; // 0xb3
	private Boolean _needProfessionMask; // 0xb4
	public ProfessionCategory _professionMask; // 0xb8
	private Int32 m_selectNum; // 0xbc
	private static DelegateBridge __Hotfix0_get_limitTargetNum; // 0x0
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x8
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x10
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x18
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x20
	private static DelegateBridge __Hotfix0_get_ignoreHealFree; // 0x28
	private static DelegateBridge __Hotfix0_get_professionMask; // 0x30
	private static DelegateBridge __Hotfix0_get_excludeSelf; // 0x38
	private static DelegateBridge __Hotfix0_get_selectNum; // 0x40
	private static DelegateBridge __Hotfix0_get_alwaysAppendSelf; // 0x48
	private static DelegateBridge __Hotfix0_get_needProfessionMask; // 0x50
	private static DelegateBridge __Hotfix0_SetData; // 0x58
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x60
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Boolean limitTargetNum { get; }
	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	public override Boolean ignoreTargetFree { get; }
	protected override Boolean ignoreHealFree { get; }
	protected override ProfessionCategory professionMask { get; }
	protected Boolean excludeSelf { get; }
	protected Int32 selectNum { get; }
	protected Boolean alwaysAppendSelf { get; }
	protected Boolean needProfessionMask { get; }

	// RVA: 0x1bb7994 VA: 0x75941cf994
	public Boolean get_limitTargetNum() { }
	// RVA: 0x1bb79f8 VA: 0x75941cf9f8
	public override SideType get_targetSide() { }
	// RVA: 0x1bb7a60 VA: 0x75941cfa60
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1bb7ac8 VA: 0x75941cfac8
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1bb7b30 VA: 0x75941cfb30
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1bb7b98 VA: 0x75941cfb98
	protected override Boolean get_ignoreHealFree() { }
	// RVA: 0x1bb7c00 VA: 0x75941cfc00
	protected override ProfessionCategory get_professionMask() { }
	// RVA: 0x1bb7ce4 VA: 0x75941cfce4
	protected Boolean get_excludeSelf() { }
	// RVA: 0x1bb7d4c VA: 0x75941cfd4c
	protected Int32 get_selectNum() { }
	// RVA: 0x1bb7db4 VA: 0x75941cfdb4
	protected Boolean get_alwaysAppendSelf() { }
	// RVA: 0x1bb7c7c VA: 0x75941cfc7c
	protected Boolean get_needProfessionMask() { }
	// RVA: 0x1bb7e1c VA: 0x75941cfe1c
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1bb7f64 VA: 0x75941cff64
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb825c VA: 0x75941d025c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb82d4 VA: 0x75941d02d4
	public Void .ctor() { }
	// RVA: 0x1bb840c VA: 0x75941d040c
	private Boolean <>xLuaBaseProxy_get_ignoreHealFree() { }
	// RVA: 0x1bb8474 VA: 0x75941d0474
	private ProfessionCategory <>xLuaBaseProxy_get_professionMask() { }
	// RVA: 0x1bb84dc VA: 0x75941d04dc
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
}
```