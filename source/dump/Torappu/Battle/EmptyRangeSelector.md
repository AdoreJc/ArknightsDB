# EmptyRangeSelector

**Namespace:** `Torappu.Battle`


## Properties

- `Boolean limitTargetNum`

- `Int32 maxTargetNum`


## Methods

- `Boolean get_limitTargetNum()`

- `Int32 get_maxTargetNum()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EmptyRangeSelector : RangeSelector
{
	private static DelegateBridge __Hotfix0_get_limitTargetNum; // 0x0
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x8
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x10
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x18
	private static DelegateBridge __Hotfix0_get_maxTargetNum; // 0x20
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x28
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x30
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean limitTargetNum { get; }
	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	protected Int32 maxTargetNum { get; }
	public override Boolean ignoreTargetFree { get; }

	// RVA: 0x1ba8f8c VA: 0x75941c0f8c
	public Boolean get_limitTargetNum() { }
	// RVA: 0x1ba8ff0 VA: 0x75941c0ff0
	public override SideType get_targetSide() { }
	// RVA: 0x1ba9054 VA: 0x75941c1054
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1ba90b8 VA: 0x75941c10b8
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1ba911c VA: 0x75941c111c
	protected Int32 get_maxTargetNum() { }
	// RVA: 0x1ba9180 VA: 0x75941c1180
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1ba91e4 VA: 0x75941c11e4
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1ba925c VA: 0x75941c125c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1ba92d4 VA: 0x75941c12d4
	public Void .ctor() { }
}
```