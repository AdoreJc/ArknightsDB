# CirclePlugin

**Namespace:** `DG.Tweening.Plugins`


## Methods

- `Vector2 GetPositionOnCircle(CircleOptions, Single)`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Plugins
public class CirclePlugin : ABSTweenPlugin`3
{


	// RVA: 0x417c658 VA: 0x7596794658
	public override Void Reset(TweenerCore`3 t) { }
	// RVA: 0x417c65c VA: 0x759679465c
	public override Void SetFrom(TweenerCore`3 t, Boolean isRelative) { }
	// RVA: 0x417c8b4 VA: 0x75967948b4
	public override Void SetFrom(TweenerCore`3 t, Vector2 fromValue, Boolean setImmediately, Boolean isRelative) { }
	// RVA: 0x417c9ac VA: 0x75967949ac
	public static ABSTweenPlugin`3 Get() { }
	// RVA: 0x417c9ec VA: 0x75967949ec
	public override Vector2 ConvertToStartValue(TweenerCore`3 t, Vector2 value) { }
	// RVA: 0x417c9f0 VA: 0x75967949f0
	public override Void SetRelativeEndValue(TweenerCore`3 t) { }
	// RVA: 0x417ca38 VA: 0x7596794a38
	public override Void SetChangeValue(TweenerCore`3 t) { }
	// RVA: 0x417ca84 VA: 0x7596794a84
	public override Single GetSpeedBasedDuration(CircleOptions options, Single unitsXSecond, Vector2 changeValue) { }
	// RVA: 0x417ca8c VA: 0x7596794a8c
	public override Void EvaluateAndApply(CircleOptions options, Tween t, Boolean isRelative, DOGetter`1 getter, DOSetter`1 setter, Single elapsed, Vector2 startValue, Vector2 changeValue, Single duration, Boolean usingInversePosition, Int32 newCompletedSteps, UpdateNotice updateNotice) { }
	// RVA: 0x417c718 VA: 0x7596794718
	public Vector2 GetPositionOnCircle(CircleOptions options, Single degrees) { }
	// RVA: 0x417cb84 VA: 0x7596794b84
	public Void .ctor() { }
}
```