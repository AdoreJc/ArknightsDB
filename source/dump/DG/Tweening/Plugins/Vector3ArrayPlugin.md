# Vector3ArrayPlugin

**Namespace:** `DG.Tweening.Plugins`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Plugins
public class Vector3ArrayPlugin : ABSTweenPlugin`3
{


	// RVA: 0x4187ac0 VA: 0x759679fac0
	public override Void Reset(TweenerCore`3 t) { }
	// RVA: 0x4187b04 VA: 0x759679fb04
	public override Void SetFrom(TweenerCore`3 t, Boolean isRelative) { }
	// RVA: 0x4187b08 VA: 0x759679fb08
	public override Void SetFrom(TweenerCore`3 t, Vector3[] fromValue, Boolean setImmediately, Boolean isRelative) { }
	// RVA: 0x4187b0c VA: 0x759679fb0c
	public override Vector3[] ConvertToStartValue(TweenerCore`3 t, Vector3 value) { }
	// RVA: 0x4187c0c VA: 0x759679fc0c
	public override Void SetRelativeEndValue(TweenerCore`3 t) { }
	// RVA: 0x4187cf4 VA: 0x759679fcf4
	public override Void SetChangeValue(TweenerCore`3 t) { }
	// RVA: 0x4187df4 VA: 0x759679fdf4
	public override Single GetSpeedBasedDuration(Vector3ArrayOptions options, Single unitsXSecond, Vector3[] changeValue) { }
	// RVA: 0x4187f04 VA: 0x759679ff04
	public override Void EvaluateAndApply(Vector3ArrayOptions options, Tween t, Boolean isRelative, DOGetter`1 getter, DOSetter`1 setter, Single elapsed, Vector3[] startValue, Vector3[] changeValue, Single duration, Boolean usingInversePosition, Int32 newCompletedSteps, UpdateNotice updateNotice) { }
	// RVA: 0x41886e8 VA: 0x75967a06e8
	public Void .ctor() { }
}
```