# EmpgrdTalentSelector

**Namespace:** `Torappu.Battle`


## Fields

- `String _damageRecorderBuffKey`

- `String _lowPriorityBuffKey`

- `Int32 _maxTargetNum`


## Methods

- `String _GetSafeKey(Entity)`

- `FP _CalculateDamageWeight(Entity, Buff)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EmpgrdTalentSelector : RangeSelector
{
	private String _damageRecorderBuffKey; // 0xa0
	private String _lowPriorityBuffKey; // 0xa8
	private Int32 _maxTargetNum; // 0xb0
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x0
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x8
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x10
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x18
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x20
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x28
	private static DelegateBridge __Hotfix0__GetSafeKey; // 0x30
	private static DelegateBridge __Hotfix0__CalculateDamageWeight; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	public override Boolean ignoreTargetFree { get; }

	// RVA: 0x1bbf7e4 VA: 0x75941d77e4
	public override SideType get_targetSide() { }
	// RVA: 0x1bbf84c VA: 0x75941d784c
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1bbf8b4 VA: 0x75941d78b4
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1bbf91c VA: 0x75941d791c
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1bbf980 VA: 0x75941d7980
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bbfc88 VA: 0x75941d7c88
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bbfd00 VA: 0x75941d7d00
	private String _GetSafeKey(Entity entity) { }
	// RVA: 0x1bbfe1c VA: 0x75941d7e1c
	private FP _CalculateDamageWeight(Entity entity, Buff recorderBuff) { }
	// RVA: 0x1bbff24 VA: 0x75941d7f24
	public Void .ctor() { }
}
```