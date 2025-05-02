# Slider

**Namespace:** `UnityEngine.UIElements`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class Slider : BaseSlider`1
{
	public static readonly String ussClassName; // 0x0
	public static readonly String labelUssClassName; // 0x8
	public static readonly String inputUssClassName; // 0x10


	// RVA: 0x69c3b80 VA: 0x7598fdbb80
	public Void .ctor() { }
	// RVA: 0x69bc920 VA: 0x7598fd4920
	public Void .ctor(Single start, Single end, SliderDirection direction, Single pageSize) { }
	// RVA: 0x69c3b98 VA: 0x7598fdbb98
	public Void .ctor(String label, Single start, Single end, SliderDirection direction, Single pageSize) { }
	// RVA: 0x69c3ce4 VA: 0x7598fdbce4
	internal override Single SliderLerpUnclamped(Single a, Single b, Single interpolant) { }
	// RVA: 0x69c3f94 VA: 0x7598fdbf94
	internal override Single SliderNormalizeValue(Single currentValue, Single lowerValue, Single higherValue) { }
	// RVA: 0x69c3fa4 VA: 0x7598fdbfa4
	internal override Single ParseStringToValue(String stringValue) { }
	// RVA: 0x69c4074 VA: 0x7598fdc074
	internal override Void ComputeValueFromKey(SliderKey sliderKey, Boolean isShift) { }
	// RVA: 0x69c4270 VA: 0x7598fdc270
	private static Void .cctor() { }
}
```