# Slider

**Namespace:** `UnityEngine.UI`


## Fields

- `RectTransform m_FillRect`

- `RectTransform m_HandleRect`

- `Direction m_Direction`

- `Single m_MinValue`

- `Single m_MaxValue`

- `Boolean m_WholeNumbers`

- `Single m_Value`

- `SliderEvent m_OnValueChanged`

- `Image m_FillImage`

- `Transform m_FillTransform`

- `RectTransform m_FillContainerRect`

- `Transform m_HandleTransform`

- `RectTransform m_HandleContainerRect`

- `Vector2 m_Offset`

- `DrivenRectTransformTracker m_Tracker`

- `Boolean m_DelayedUpdateVisuals`


## Properties

- `RectTransform fillRect`

- `RectTransform handleRect`

- `Direction direction`

- `Single minValue`

- `Single maxValue`

- `Boolean wholeNumbers`

- `Single normalizedValue`

- `SliderEvent onValueChanged`

- `Single stepSize`

- `Axis axis`

- `Boolean reverseValue`


## Methods

- `RectTransform get_fillRect()`

- `Void set_fillRect(RectTransform)`

- `RectTransform get_handleRect()`

- `Void set_handleRect(RectTransform)`

- `Direction get_direction()`

- `Void set_direction(Direction)`

- `Single get_minValue()`

- `Void set_minValue(Single)`

- `Single get_maxValue()`

- `Void set_maxValue(Single)`

- `Boolean get_wholeNumbers()`

- `Void set_wholeNumbers(Boolean)`

- `Single get_normalizedValue()`

- `Void set_normalizedValue(Single)`

- `SliderEvent get_onValueChanged()`

- `Void set_onValueChanged(SliderEvent)`

- `Single get_stepSize()`

- `Void UpdateCachedReferences()`

- `Single ClampValue(Single)`

- `Axis get_axis()`

- `Boolean get_reverseValue()`

- `Void UpdateVisuals()`

- `Void UpdateDrag(PointerEventData, Camera)`

- `Boolean MayDrag(PointerEventData)`

- `Void SetDirection(Direction, Boolean)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class Slider : Selectable, IDragHandler, IEventSystemHandler, IInitializePotentialDragHandler, ICanvasElement
{
	private RectTransform m_FillRect; // 0xf8
	private RectTransform m_HandleRect; // 0x100
	private Direction m_Direction; // 0x108
	private Single m_MinValue; // 0x10c
	private Single m_MaxValue; // 0x110
	private Boolean m_WholeNumbers; // 0x114
	protected Single m_Value; // 0x118
	private SliderEvent m_OnValueChanged; // 0x120
	private Image m_FillImage; // 0x128
	private Transform m_FillTransform; // 0x130
	private RectTransform m_FillContainerRect; // 0x138
	private Transform m_HandleTransform; // 0x140
	private RectTransform m_HandleContainerRect; // 0x148
	private Vector2 m_Offset; // 0x150
	private DrivenRectTransformTracker m_Tracker; // 0x158
	private Boolean m_DelayedUpdateVisuals; // 0x159

	public RectTransform fillRect { get; set; }
	public RectTransform handleRect { get; set; }
	public Direction direction { get; set; }
	public Single minValue { get; set; }
	public Single maxValue { get; set; }
	public Boolean wholeNumbers { get; set; }
	public virtual Single value { get; set; }
	public Single normalizedValue { get; set; }
	public SliderEvent onValueChanged { get; set; }
	private Single stepSize { get; }
	private Axis axis { get; }
	private Boolean reverseValue { get; }

	// RVA: 0x6a66c2c VA: 0x759907ec2c
	public RectTransform get_fillRect() { }
	// RVA: 0x6a66c34 VA: 0x759907ec34
	public Void set_fillRect(RectTransform value) { }
	// RVA: 0x6a672c8 VA: 0x759907f2c8
	public RectTransform get_handleRect() { }
	// RVA: 0x6a672d0 VA: 0x759907f2d0
	public Void set_handleRect(RectTransform value) { }
	// RVA: 0x6a6734c VA: 0x759907f34c
	public Direction get_direction() { }
	// RVA: 0x6a67354 VA: 0x759907f354
	public Void set_direction(Direction value) { }
	// RVA: 0x6a673c8 VA: 0x759907f3c8
	public Single get_minValue() { }
	// RVA: 0x6a673d0 VA: 0x759907f3d0
	public Void set_minValue(Single value) { }
	// RVA: 0x6a67460 VA: 0x759907f460
	public Single get_maxValue() { }
	// RVA: 0x6a67468 VA: 0x759907f468
	public Void set_maxValue(Single value) { }
	// RVA: 0x6a674f8 VA: 0x759907f4f8
	public Boolean get_wholeNumbers() { }
	// RVA: 0x6a67500 VA: 0x759907f500
	public Void set_wholeNumbers(Boolean value) { }
	// RVA: 0x6a67590 VA: 0x759907f590
	public virtual Single get_value() { }
	// RVA: 0x6a67630 VA: 0x759907f630
	public virtual Void set_value(Single value) { }
	// RVA: 0x6a67644 VA: 0x759907f644
	public virtual Void SetValueWithoutNotify(Single input) { }
	// RVA: 0x6a67658 VA: 0x759907f658
	public Single get_normalizedValue() { }
	// RVA: 0x6a6773c VA: 0x759907f73c
	public Void set_normalizedValue(Single value) { }
	// RVA: 0x6a67774 VA: 0x759907f774
	public SliderEvent get_onValueChanged() { }
	// RVA: 0x6a6777c VA: 0x759907f77c
	public Void set_onValueChanged(SliderEvent value) { }
	// RVA: 0x6a6778c VA: 0x759907f78c
	private Single get_stepSize() { }
	// RVA: 0x6a677b8 VA: 0x759907f7b8
	protected Void .ctor() { }
	// RVA: 0x6a678d0 VA: 0x759907f8d0
	public virtual Void Rebuild(CanvasUpdate executing) { }
	// RVA: 0x6a678d4 VA: 0x759907f8d4
	public virtual Void LayoutComplete() { }
	// RVA: 0x6a678d8 VA: 0x759907f8d8
	public virtual Void GraphicUpdateComplete() { }
	// RVA: 0x6a678dc VA: 0x759907f8dc
	protected override Void OnEnable() { }
	// RVA: 0x6a67918 VA: 0x759907f918
	protected override Void OnDisable() { }
	// RVA: 0x6a67938 VA: 0x759907f938
	protected virtual Void Update() { }
	// RVA: 0x6a67978 VA: 0x759907f978
	protected override Void OnDidApplyAnimationProperties() { }
	// RVA: 0x6a66cb0 VA: 0x759907ecb0
	private Void UpdateCachedReferences() { }
	// RVA: 0x6a67b60 VA: 0x759907fb60
	private Single ClampValue(Single input) { }
	// RVA: 0x6a67c38 VA: 0x759907fc38
	protected virtual Void Set(Single input, Boolean sendCallback) { }
	// RVA: 0x6a67cfc VA: 0x759907fcfc
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x6a67c28 VA: 0x759907fc28
	private Axis get_axis() { }
	// RVA: 0x6a67c14 VA: 0x759907fc14
	private Boolean get_reverseValue() { }
	// RVA: 0x6a66fe0 VA: 0x759907efe0
	private Void UpdateVisuals() { }
	// RVA: 0x6a67d34 VA: 0x759907fd34
	private Void UpdateDrag(PointerEventData eventData, Camera cam) { }
	// RVA: 0x6a67f6c VA: 0x759907ff6c
	private Boolean MayDrag(PointerEventData eventData) { }
	// RVA: 0x6a67fd0 VA: 0x759907ffd0
	public override Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x6a68188 VA: 0x7599080188
	public virtual Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x6a681d8 VA: 0x75990801d8
	public override Void OnMove(AxisEventData eventData) { }
	// RVA: 0x6a68424 VA: 0x7599080424
	public override Selectable FindSelectableOnLeft() { }
	// RVA: 0x6a68448 VA: 0x7599080448
	public override Selectable FindSelectableOnRight() { }
	// RVA: 0x6a6846c VA: 0x759908046c
	public override Selectable FindSelectableOnUp() { }
	// RVA: 0x6a68490 VA: 0x7599080490
	public override Selectable FindSelectableOnDown() { }
	// RVA: 0x6a684b4 VA: 0x75990804b4
	public virtual Void OnInitializePotentialDrag(PointerEventData eventData) { }
	// RVA: 0x6a684cc VA: 0x75990804cc
	public Void SetDirection(Direction direction, Boolean includeRectLayouts) { }
	// RVA: 0x6a68644 VA: 0x7599080644
	private Transform UnityEngine.UI.ICanvasElement.get_transform() { }
}
```