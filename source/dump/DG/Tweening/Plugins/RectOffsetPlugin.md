# RectOffsetPlugin

**Namespace:** `DG.Tweening.Plugins`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Plugins
public class RectOffsetPlugin : ABSTweenPlugin`3
{
	private static RectOffset _r; // 0x0


	// RVA: 0x418bb48 VA: 0x75967a3b48
	public override Void Reset(TweenerCore`3 t) { }
	// RVA: 0x418bb8c VA: 0x75967a3b8c
	public override Void SetFrom(TweenerCore`3 t, Boolean isRelative) { }
	// RVA: 0x418bd08 VA: 0x75967a3d08
	public override Void SetFrom(TweenerCore`3 t, RectOffset fromValue, Boolean setImmediately, Boolean isRelative) { }
	// RVA: 0x418bf30 VA: 0x75967a3f30
	public override RectOffset ConvertToStartValue(TweenerCore`3 t, RectOffset value) { }
	// RVA: 0x418bff0 VA: 0x75967a3ff0
	public override Void SetRelativeEndValue(TweenerCore`3 t) { }
	// RVA: 0x418c0fc VA: 0x75967a40fc
	public override Void SetChangeValue(TweenerCore`3 t) { }
	// RVA: 0x418c258 VA: 0x75967a4258
	public override Single GetSpeedBasedDuration(NoOptions options, Single unitsXSecond, RectOffset changeValue) { }
	// RVA: 0x418c314 VA: 0x75967a4314
	public override Void EvaluateAndApply(NoOptions options, Tween t, Boolean isRelative, DOGetter`1 getter, DOSetter`1 setter, Single elapsed, RectOffset startValue, RectOffset changeValue, Single duration, Boolean usingInversePosition, Int32 newCompletedSteps, UpdateNotice updateNotice) { }
	// RVA: 0x418ca40 VA: 0x75967a4a40
	public Void .ctor() { }
	// RVA: 0x418ca88 VA: 0x75967a4a88
	private static Void .cctor() { }
}
```