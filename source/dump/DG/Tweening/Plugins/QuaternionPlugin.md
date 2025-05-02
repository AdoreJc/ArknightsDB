# QuaternionPlugin

**Namespace:** `DG.Tweening.Plugins`


## Methods

- `Vector3 GetEulerValForCalculations(TweenerCore`3, Vector3, Vector3)`

- `Vector3 FlipEulerAngles(Vector3)`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Plugins
public class QuaternionPlugin : ABSTweenPlugin`3
{


	// RVA: 0x418aa44 VA: 0x75967a2a44
	public override Void Reset(TweenerCore`3 t) { }
	// RVA: 0x418aa48 VA: 0x75967a2a48
	public override Void SetFrom(TweenerCore`3 t, Boolean isRelative) { }
	// RVA: 0x418b0a4 VA: 0x75967a30a4
	public override Void SetFrom(TweenerCore`3 t, Vector3 fromValue, Boolean setImmediately, Boolean isRelative) { }
	// RVA: 0x418b1d0 VA: 0x75967a31d0
	public override Vector3 ConvertToStartValue(TweenerCore`3 t, Quaternion value) { }
	// RVA: 0x418b1fc VA: 0x75967a31fc
	public override Void SetRelativeEndValue(TweenerCore`3 t) { }
	// RVA: 0x418b234 VA: 0x75967a3234
	public override Void SetChangeValue(TweenerCore`3 t) { }
	// RVA: 0x418b434 VA: 0x75967a3434
	public override Single GetSpeedBasedDuration(QuaternionOptions options, Single unitsXSecond, Vector3 changeValue) { }
	// RVA: 0x418b4b4 VA: 0x75967a34b4
	public override Void EvaluateAndApply(QuaternionOptions options, Tween t, Boolean isRelative, DOGetter`1 getter, DOSetter`1 setter, Single elapsed, Vector3 startValue, Vector3 changeValue, Single duration, Boolean usingInversePosition, Int32 newCompletedSteps, UpdateNotice updateNotice) { }
	// RVA: 0x418ae18 VA: 0x75967a2e18
	private Vector3 GetEulerValForCalculations(TweenerCore`3 t, Vector3 val, Vector3 counterVal) { }
	// RVA: 0x418bae8 VA: 0x75967a3ae8
	private Vector3 FlipEulerAngles(Vector3 euler) { }
	// RVA: 0x418bb00 VA: 0x75967a3b00
	public Void .ctor() { }
}
```