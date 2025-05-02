# Scroller

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Slider <slider>k__BackingField`

- `RepeatButton <lowButton>k__BackingField`

- `RepeatButton <highButton>k__BackingField`


## Properties

- `Slider slider`

- `RepeatButton lowButton`

- `RepeatButton highButton`

- `Single value`

- `Single lowValue`

- `Single highValue`

- `SliderDirection direction`


## Methods

- `Void add_valueChanged(Action`1)`

- `Void remove_valueChanged(Action`1)`

- `Slider get_slider()`

- `Void set_slider(Slider)`

- `RepeatButton get_lowButton()`

- `Void set_lowButton(RepeatButton)`

- `RepeatButton get_highButton()`

- `Void set_highButton(RepeatButton)`

- `Single get_value()`

- `Void set_value(Single)`

- `Single get_lowValue()`

- `Void set_lowValue(Single)`

- `Single get_highValue()`

- `Void set_highValue(Single)`

- `Void set_direction(SliderDirection)`

- `Void Adjust(Single)`

- `Void OnSliderValueChange(ChangeEvent`1)`

- `Void ScrollPageUp()`

- `Void ScrollPageDown()`

- `Void ScrollPageUp(Single)`

- `Void ScrollPageDown(Single)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class Scroller : VisualElement
{
	private Action`1 valueChanged; // 0x3b0
	private Slider <slider>k__BackingField; // 0x3b8
	private RepeatButton <lowButton>k__BackingField; // 0x3c0
	private RepeatButton <highButton>k__BackingField; // 0x3c8
	public static readonly String ussClassName; // 0x0
	public static readonly String horizontalVariantUssClassName; // 0x8
	public static readonly String verticalVariantUssClassName; // 0x10
	public static readonly String sliderUssClassName; // 0x18
	public static readonly String lowButtonUssClassName; // 0x20
	public static readonly String highButtonUssClassName; // 0x28

	public Slider slider { get; set; }
	public RepeatButton lowButton { get; set; }
	public RepeatButton highButton { get; set; }
	public Single value { get; set; }
	public Single lowValue { get; set; }
	public Single highValue { get; set; }
	public SliderDirection direction { set; }

	// RVA: 0x69bbfd4 VA: 0x7598fd3fd4
	public Void add_valueChanged(Action`1 value) { }
	// RVA: 0x69bc088 VA: 0x7598fd4088
	public Void remove_valueChanged(Action`1 value) { }
	// RVA: 0x69bc13c VA: 0x7598fd413c
	public Slider get_slider() { }
	// RVA: 0x69bc144 VA: 0x7598fd4144
	private Void set_slider(Slider value) { }
	// RVA: 0x69bc154 VA: 0x7598fd4154
	public RepeatButton get_lowButton() { }
	// RVA: 0x69bc15c VA: 0x7598fd415c
	private Void set_lowButton(RepeatButton value) { }
	// RVA: 0x69bc16c VA: 0x7598fd416c
	public RepeatButton get_highButton() { }
	// RVA: 0x69bc174 VA: 0x7598fd4174
	private Void set_highButton(RepeatButton value) { }
	// RVA: 0x69bc184 VA: 0x7598fd4184
	public Single get_value() { }
	// RVA: 0x69bc1a8 VA: 0x7598fd41a8
	public Void set_value(Single value) { }
	// RVA: 0x69bc1cc VA: 0x7598fd41cc
	public Single get_lowValue() { }
	// RVA: 0x69bc21c VA: 0x7598fd421c
	public Void set_lowValue(Single value) { }
	// RVA: 0x69bc27c VA: 0x7598fd427c
	public Single get_highValue() { }
	// RVA: 0x69bc2cc VA: 0x7598fd42cc
	public Void set_highValue(Single value) { }
	// RVA: 0x69bc32c VA: 0x7598fd432c
	public Void set_direction(SliderDirection value) { }
	// RVA: 0x69bc528 VA: 0x7598fd4528
	public Void .ctor() { }
	// RVA: 0x69bc53c VA: 0x7598fd453c
	public Void .ctor(Single lowValue, Single highValue, Action`1 valueChanged, SliderDirection direction) { }
	// RVA: 0x69bc92c VA: 0x7598fd492c
	public Void Adjust(Single factor) { }
	// RVA: 0x69bc9a4 VA: 0x7598fd49a4
	private Void OnSliderValueChange(ChangeEvent`1 evt) { }
	// RVA: 0x69bca40 VA: 0x7598fd4a40
	public Void ScrollPageUp() { }
	// RVA: 0x69bcb40 VA: 0x7598fd4b40
	public Void ScrollPageDown() { }
	// RVA: 0x69bca48 VA: 0x7598fd4a48
	public Void ScrollPageUp(Single factor) { }
	// RVA: 0x69bcb48 VA: 0x7598fd4b48
	public Void ScrollPageDown(Single factor) { }
	// RVA: 0x69bcc40 VA: 0x7598fd4c40
	private static Void .cctor() { }
}
```