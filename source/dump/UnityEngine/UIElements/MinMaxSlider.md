# MinMaxSlider

**Namespace:** `UnityEngine.UIElements`


## Fields

- `VisualElement <dragElement>k__BackingField`

- `VisualElement <dragMinThumb>k__BackingField`

- `VisualElement <dragMaxThumb>k__BackingField`

- `Vector2 m_DragElementStartPos`

- `Vector2 m_ValueStartPos`

- `Rect m_DragMinThumbRect`

- `Rect m_DragMaxThumbRect`

- `DragState m_DragState`

- `Single m_MinLimit`

- `Single m_MaxLimit`


## Properties

- `Single minValue`

- `Single maxValue`

- `Single lowLimit`

- `Single highLimit`


## Methods

- `Void set_dragElement(VisualElement)`

- `Void set_dragMinThumb(VisualElement)`

- `Void set_dragMaxThumb(VisualElement)`

- `Void set_clampedDragger(ClampedDragger`1)`

- `Single get_minValue()`

- `Void set_minValue(Single)`

- `Single get_maxValue()`

- `Void set_maxValue(Single)`

- `Single get_lowLimit()`

- `Void set_lowLimit(Single)`

- `Single get_highLimit()`

- `Void set_highLimit(Single)`

- `Vector2 ClampValues(Vector2)`

- `Void UpdateDragElementPosition(GeometryChangedEvent)`

- `Void UpdateDragElementPosition()`

- `Single ComputeValueFromPosition(Single)`

- `Void SetSliderValueFromDrag()`

- `Void SetSliderValueFromClick()`

- `Void ComputeValueDragStateNoThumb(Single, Single, Single)`

- `Void ComputeValueFromDraggingThumb(Single, Single)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class MinMaxSlider : BaseField`1
{
	private VisualElement <dragElement>k__BackingField; // 0x408
	private VisualElement <dragMinThumb>k__BackingField; // 0x410
	private VisualElement <dragMaxThumb>k__BackingField; // 0x418
	private ClampedDragger`1 <clampedDragger>k__BackingField; // 0x420
	private Vector2 m_DragElementStartPos; // 0x428
	private Vector2 m_ValueStartPos; // 0x430
	private Rect m_DragMinThumbRect; // 0x438
	private Rect m_DragMaxThumbRect; // 0x448
	private DragState m_DragState; // 0x458
	private Single m_MinLimit; // 0x45c
	private Single m_MaxLimit; // 0x460
	public static readonly String ussClassName; // 0x0
	public static readonly String labelUssClassName; // 0x8
	public static readonly String inputUssClassName; // 0x10
	public static readonly String trackerUssClassName; // 0x18
	public static readonly String draggerUssClassName; // 0x20
	public static readonly String minThumbUssClassName; // 0x28
	public static readonly String maxThumbUssClassName; // 0x30

	internal VisualElement dragElement { get; set; }
	internal VisualElement dragMinThumb { get; set; }
	internal VisualElement dragMaxThumb { get; set; }
	internal ClampedDragger`1 clampedDragger { get; set; }
	public Single minValue { get; set; }
	public Single maxValue { get; set; }
	public override Vector2 value { get; set; }
	public Single lowLimit { get; set; }
	public Single highLimit { get; set; }

	// RVA: 0x69b6340 VA: 0x7598fce340
	internal VisualElement get_dragElement() { }
	// RVA: 0x69b6348 VA: 0x7598fce348
	private Void set_dragElement(VisualElement value) { }
	// RVA: 0x69b6358 VA: 0x7598fce358
	internal VisualElement get_dragMinThumb() { }
	// RVA: 0x69b6360 VA: 0x7598fce360
	private Void set_dragMinThumb(VisualElement value) { }
	// RVA: 0x69b6370 VA: 0x7598fce370
	internal VisualElement get_dragMaxThumb() { }
	// RVA: 0x69b6378 VA: 0x7598fce378
	private Void set_dragMaxThumb(VisualElement value) { }
	// RVA: 0x69b6388 VA: 0x7598fce388
	internal ClampedDragger`1 get_clampedDragger() { }
	// RVA: 0x69b6390 VA: 0x7598fce390
	private Void set_clampedDragger(ClampedDragger`1 value) { }
	// RVA: 0x69b63a0 VA: 0x7598fce3a0
	public Single get_minValue() { }
	// RVA: 0x69b63b0 VA: 0x7598fce3b0
	public Void set_minValue(Single value) { }
	// RVA: 0x69b6490 VA: 0x7598fce490
	public Single get_maxValue() { }
	// RVA: 0x69b64b0 VA: 0x7598fce4b0
	public Void set_maxValue(Single value) { }
	// RVA: 0x69b6558 VA: 0x7598fce558
	public override Vector2 get_value() { }
	// RVA: 0x69b65a0 VA: 0x7598fce5a0
	public override Void set_value(Vector2 value) { }
	// RVA: 0x69b662c VA: 0x7598fce62c
	public override Void SetValueWithoutNotify(Vector2 newValue) { }
	// RVA: 0x69b7b9c VA: 0x7598fcfb9c
	public Single get_lowLimit() { }
	// RVA: 0x69b7ba4 VA: 0x7598fcfba4
	public Void set_lowLimit(Single value) { }
	// RVA: 0x69b7d14 VA: 0x7598fcfd14
	public Single get_highLimit() { }
	// RVA: 0x69b7d1c VA: 0x7598fcfd1c
	public Void set_highLimit(Single value) { }
	// RVA: 0x69b7e8c VA: 0x7598fcfe8c
	public Void .ctor() { }
	// RVA: 0x69b7eac VA: 0x7598fcfeac
	public Void .ctor(String label, Single minValue, Single maxValue, Single minLimit, Single maxLimit) { }
	// RVA: 0x69b6458 VA: 0x7598fce458
	private Vector2 ClampValues(Vector2 valueToClamp) { }
	// RVA: 0x69b8424 VA: 0x7598fd0424
	private Void UpdateDragElementPosition(GeometryChangedEvent evt) { }
	// RVA: 0x69b66c0 VA: 0x7598fce6c0
	private Void UpdateDragElementPosition() { }
	// RVA: 0x69b84c8 VA: 0x7598fd04c8
	internal Single SliderLerpUnclamped(Single a, Single b, Single interpolant) { }
	// RVA: 0x69b84b8 VA: 0x7598fd04b8
	internal Single SliderNormalizeValue(Single currentValue, Single lowerValue, Single higherValue) { }
	// RVA: 0x69b84d8 VA: 0x7598fd04d8
	private Single ComputeValueFromPosition(Single positionToConvert) { }
	// RVA: 0x69b8698 VA: 0x7598fd0698
	protected override Void ExecuteDefaultAction(EventBase evt) { }
	// RVA: 0x69b87a4 VA: 0x7598fd07a4
	private Void SetSliderValueFromDrag() { }
	// RVA: 0x69b89dc VA: 0x7598fd09dc
	private Void SetSliderValueFromClick() { }
	// RVA: 0x69b8d30 VA: 0x7598fd0d30
	private Void ComputeValueDragStateNoThumb(Single lowLimitPosition, Single highLimitPosition, Single dragElementPos) { }
	// RVA: 0x69b8838 VA: 0x7598fd0838
	private Void ComputeValueFromDraggingThumb(Single dragElementStartPos, Single dragElementEndPos) { }
	// RVA: 0x69b8dd0 VA: 0x7598fd0dd0
	protected override Void UpdateMixedValueContent() { }
	// RVA: 0x69b8dd4 VA: 0x7598fd0dd4
	private static Void .cctor() { }
}
```