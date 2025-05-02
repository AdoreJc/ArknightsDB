# InputTargetOnlySelector

**Namespace:** `Torappu.Battle`


## Fields

- `SideType _targetSide`

- `MotionMask _targetMotion`

- `EntityCategory _targetCategory`

- `Boolean _ignoreTargetFree`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class InputTargetOnlySelector : RangeSelector
{
	private SideType _targetSide; // 0xa0
	private MotionMask _targetMotion; // 0xa4
	private EntityCategory _targetCategory; // 0xa8
	private Boolean _ignoreTargetFree; // 0xac
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x0
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x8
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x10
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x18
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x20
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	public override Boolean ignoreTargetFree { get; }

	// RVA: 0x1bb3440 VA: 0x75941cb440
	public override SideType get_targetSide() { }
	// RVA: 0x1bb34a8 VA: 0x75941cb4a8
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1bb3510 VA: 0x75941cb510
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1bb3578 VA: 0x75941cb578
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1bb35e0 VA: 0x75941cb5e0
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb3860 VA: 0x75941cb860
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb38d8 VA: 0x75941cb8d8
	public Void .ctor() { }
}
```