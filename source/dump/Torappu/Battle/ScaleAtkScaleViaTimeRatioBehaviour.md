# ScaleAtkScaleViaTimeRatioBehaviour

**Namespace:** `Torappu.Battle`


## Fields

- `String _minKey`

- `String _maxKey`

- `AnimationCurve _scaleCurve`


## Methods

- `Void _UpdateScaledValue()`

- `Void _AssignDynamicValue(FP)`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ScaleAtkScaleViaTimeRatioBehaviour : Behaviour
{
	public String _minKey; // 0x28
	public String _maxKey; // 0x30
	public AnimationCurve _scaleCurve; // 0x38
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x0
	private static DelegateBridge __Hotfix0__UpdateScaledValue; // 0x8
	private static DelegateBridge __Hotfix0__AssignDynamicValue; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x40a39bc VA: 0x75966bb9bc
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x40a3a48 VA: 0x75966bba48
	private Void _UpdateScaledValue() { }
	// RVA: 0x40a3d18 VA: 0x75966bbd18
	private Void _AssignDynamicValue(FP dynamicValue) { }
	// RVA: 0x40a4124 VA: 0x75966bc124
	public Void .ctor() { }
	// RVA: 0x40a4194 VA: 0x75966bc194
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
}
```