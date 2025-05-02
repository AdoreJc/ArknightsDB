# StringPlugin

**Namespace:** `DG.Tweening.Plugins`


## Methods

- `StringBuilder Append(String, Int32, Int32, Boolean)`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Plugins
public class StringPlugin : ABSTweenPlugin`3
{
	private static readonly StringBuilder _Buffer; // 0x0
	private static readonly List`1 _OpenedTags; // 0x8


	// RVA: 0x418f910 VA: 0x75967a7910
	public override Void SetFrom(TweenerCore`3 t, Boolean isRelative) { }
	// RVA: 0x418f98c VA: 0x75967a798c
	public override Void SetFrom(TweenerCore`3 t, String fromValue, Boolean setImmediately, Boolean isRelative) { }
	// RVA: 0x418fa74 VA: 0x75967a7a74
	public override Void Reset(TweenerCore`3 t) { }
	// RVA: 0x418faec VA: 0x75967a7aec
	public override String ConvertToStartValue(TweenerCore`3 t, String value) { }
	// RVA: 0x418faf4 VA: 0x75967a7af4
	public override Void SetRelativeEndValue(TweenerCore`3 t) { }
	// RVA: 0x418faf8 VA: 0x75967a7af8
	public override Void SetChangeValue(TweenerCore`3 t) { }
	// RVA: 0x418fd70 VA: 0x75967a7d70
	public override Single GetSpeedBasedDuration(StringOptions options, Single unitsXSecond, String changeValue) { }
	// RVA: 0x418fdb0 VA: 0x75967a7db0
	public override Void EvaluateAndApply(StringOptions options, Tween t, Boolean isRelative, DOGetter`1 getter, DOSetter`1 setter, Single elapsed, String startValue, String changeValue, Single duration, Boolean usingInversePosition, Int32 newCompletedSteps, UpdateNotice updateNotice) { }
	// RVA: 0x4190250 VA: 0x75967a8250
	private StringBuilder Append(String value, Int32 startIndex, Int32 length, Boolean richTextEnabled) { }
	// RVA: 0x4190918 VA: 0x75967a8918
	private Char[] ScrambledCharsToUse(StringOptions options) { }
	// RVA: 0x4190b2c VA: 0x75967a8b2c
	public Void .ctor() { }
	// RVA: 0x4190b74 VA: 0x75967a8b74
	private static Void .cctor() { }
}
```