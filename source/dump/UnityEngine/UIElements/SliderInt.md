# SliderInt

**Namespace:** `UnityEngine.UIElements`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class SliderInt : BaseSlider`1
{
	public static readonly String ussClassName; // 0x0
	public static readonly String labelUssClassName; // 0x8
	public static readonly String inputUssClassName; // 0x10

	public override Single pageSize { get; set; }

	// RVA: 0x69c4910 VA: 0x7598fdc910
	public Void .ctor() { }
	// RVA: 0x69c4928 VA: 0x7598fdc928
	public Void .ctor(String label, Int32 start, Int32 end, SliderDirection direction, Single pageSize) { }
	// RVA: 0x69c4a74 VA: 0x7598fdca74
	public override Single get_pageSize() { }
	// RVA: 0x69c4abc VA: 0x7598fdcabc
	public override Void set_pageSize(Single value) { }
	// RVA: 0x69c4bd4 VA: 0x7598fdcbd4
	internal override Int32 SliderLerpUnclamped(Int32 a, Int32 b, Single interpolant) { }
	// RVA: 0x69c4cc0 VA: 0x7598fdccc0
	internal override Single SliderNormalizeValue(Int32 currentValue, Int32 lowerValue, Int32 higherValue) { }
	// RVA: 0x69c4cdc VA: 0x7598fdccdc
	internal override Int32 ParseStringToValue(String stringValue) { }
	// RVA: 0x69c4d08 VA: 0x7598fdcd08
	internal override Void ComputeValueAndDirectionFromClick(Single sliderLength, Single dragElementLength, Single dragElementPos, Single dragElementLastPos) { }
	// RVA: 0x69c5068 VA: 0x7598fdd068
	internal override Void ComputeValueFromKey(SliderKey sliderKey, Boolean isShift) { }
	// RVA: 0x69c5338 VA: 0x7598fdd338
	private static Void .cctor() { }
}
```