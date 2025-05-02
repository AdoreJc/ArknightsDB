# PureQuaternionPlugin

**Namespace:** `DG.Tweening.CustomPlugins`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.CustomPlugins
public class PureQuaternionPlugin : ABSTweenPlugin`3
{
	private static PureQuaternionPlugin _plug; // 0x0


	// RVA: 0x4195198 VA: 0x75967ad198
	public static PureQuaternionPlugin Plug() { }
	// RVA: 0x419526c VA: 0x75967ad26c
	public override Void Reset(TweenerCore`3 t) { }
	// RVA: 0x4195270 VA: 0x75967ad270
	public override Void SetFrom(TweenerCore`3 t, Boolean isRelative) { }
	// RVA: 0x4195384 VA: 0x75967ad384
	public override Void SetFrom(TweenerCore`3 t, Quaternion fromValue, Boolean setImmediately, Boolean isRelative) { }
	// RVA: 0x4195538 VA: 0x75967ad538
	public override Quaternion ConvertToStartValue(TweenerCore`3 t, Quaternion value) { }
	// RVA: 0x419553c VA: 0x75967ad53c
	public override Void SetRelativeEndValue(TweenerCore`3 t) { }
	// RVA: 0x41955f0 VA: 0x75967ad5f0
	public override Void SetChangeValue(TweenerCore`3 t) { }
	// RVA: 0x4195614 VA: 0x75967ad614
	public override Single GetSpeedBasedDuration(NoOptions options, Single unitsXSecond, Quaternion changeValue) { }
	// RVA: 0x41956c8 VA: 0x75967ad6c8
	public override Void EvaluateAndApply(NoOptions options, Tween t, Boolean isRelative, DOGetter`1 getter, DOSetter`1 setter, Single elapsed, Quaternion startValue, Quaternion changeValue, Single duration, Boolean usingInversePosition, Int32 newCompletedSteps, UpdateNotice updateNotice) { }
	// RVA: 0x4195224 VA: 0x75967ad224
	public Void .ctor() { }
}
```