# PathPlugin

**Namespace:** `DG.Tweening.Plugins`


## Methods

- `Void SetOrientation(PathOptions, Tween, Path, Single, Vector3, UpdateNotice)`

- `Vector3 DivideVectorByVector(Vector3, Vector3)`

- `Vector3 MultiplyVectorByVector(Vector3, Vector3)`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Plugins
public class PathPlugin : ABSTweenPlugin`3
{
	public const Single MinLookAhead; // 0x0


	// RVA: 0x4188730 VA: 0x75967a0730
	public override Void Reset(TweenerCore`3 t) { }
	// RVA: 0x41888e4 VA: 0x75967a08e4
	public override Void SetFrom(TweenerCore`3 t, Boolean isRelative) { }
	// RVA: 0x41888e8 VA: 0x75967a08e8
	public override Void SetFrom(TweenerCore`3 t, Path fromValue, Boolean setImmediately, Boolean isRelative) { }
	// RVA: 0x41888ec VA: 0x75967a08ec
	public static ABSTweenPlugin`3 Get() { }
	// RVA: 0x418892c VA: 0x75967a092c
	public override Path ConvertToStartValue(TweenerCore`3 t, Vector3 value) { }
	// RVA: 0x4188944 VA: 0x75967a0944
	public override Void SetRelativeEndValue(TweenerCore`3 t) { }
	// RVA: 0x41889fc VA: 0x75967a09fc
	public override Void SetChangeValue(TweenerCore`3 t) { }
	// RVA: 0x4188f48 VA: 0x75967a0f48
	public override Single GetSpeedBasedDuration(PathOptions options, Single unitsXSecond, Path changeValue) { }
	// RVA: 0x4188f64 VA: 0x75967a0f64
	public override Void EvaluateAndApply(PathOptions options, Tween t, Boolean isRelative, DOGetter`1 getter, DOSetter`1 setter, Single elapsed, Path startValue, Path changeValue, Single duration, Boolean usingInversePosition, Int32 newCompletedSteps, UpdateNotice updateNotice) { }
	// RVA: 0x4189898 VA: 0x75967a1898
	public Void SetOrientation(PathOptions options, Tween t, Path path, Single pathPerc, Vector3 tPos, UpdateNotice updateNotice) { }
	// RVA: 0x418a268 VA: 0x75967a2268
	private Vector3 DivideVectorByVector(Vector3 vector, Vector3 byVector) { }
	// RVA: 0x418a278 VA: 0x75967a2278
	private Vector3 MultiplyVectorByVector(Vector3 vector, Vector3 byVector) { }
	// RVA: 0x418a288 VA: 0x75967a2288
	public Void .ctor() { }
}
```