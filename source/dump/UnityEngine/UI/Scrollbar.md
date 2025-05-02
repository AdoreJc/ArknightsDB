# Scrollbar

**Namespace:** `UnityEngine.UI`


## Fields

- `RectTransform m_HandleRect`

- `Direction m_Direction`

- `Single m_Value`

- `Single m_Size`

- `Int32 m_NumberOfSteps`

- `ScrollEvent m_OnValueChanged`

- `RectTransform m_ContainerRect`

- `Vector2 m_Offset`

- `DrivenRectTransformTracker m_Tracker`

- `Coroutine m_PointerDownRepeat`

- `Boolean isPointerDownAndNotDragging`

- `Boolean m_DelayedUpdateVisuals`


## Properties

- `RectTransform handleRect`

- `Direction direction`

- `Single value`

- `Single size`

- `Int32 numberOfSteps`

- `ScrollEvent onValueChanged`

- `Single stepSize`

- `Axis axis`

- `Boolean reverseValue`


## Methods

- `RectTransform get_handleRect()`

- `Void set_handleRect(RectTransform)`

- `Direction get_direction()`

- `Void set_direction(Direction)`

- `Single get_value()`

- `Void set_value(Single)`

- `Single get_size()`

- `Void set_size(Single)`

- `Int32 get_numberOfSteps()`

- `Void set_numberOfSteps(Int32)`

- `ScrollEvent get_onValueChanged()`

- `Void set_onValueChanged(ScrollEvent)`

- `Single get_stepSize()`

- `Void UpdateCachedReferences()`

- `Void Set(Single, Boolean)`

- `Axis get_axis()`

- `Boolean get_reverseValue()`

- `Void UpdateVisuals()`

- `Void UpdateDrag(PointerEventData)`

- `Void DoUpdateDrag(Vector2, Single)`

- `Boolean MayDrag(PointerEventData)`

- `IEnumerator ClickRepeat(PointerEventData)`

- `IEnumerator ClickRepeat(Vector2, Camera)`

- `Void SetDirection(Direction, Boolean)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class Scrollbar : Selectable, IBeginDragHandler, IEventSystemHandler, IDragHandler, IInitializePotentialDragHandler, ICanvasElement
{
	private RectTransform m_HandleRect; // 0xf8
	private Direction m_Direction; // 0x100
	private Single m_Value; // 0x104
	private Single m_Size; // 0x108
	private Int32 m_NumberOfSteps; // 0x10c
	private ScrollEvent m_OnValueChanged; // 0x110
	private RectTransform m_ContainerRect; // 0x118
	private Vector2 m_Offset; // 0x120
	private DrivenRectTransformTracker m_Tracker; // 0x128
	private Coroutine m_PointerDownRepeat; // 0x130
	private Boolean isPointerDownAndNotDragging; // 0x138
	private Boolean m_DelayedUpdateVisuals; // 0x139

	public RectTransform handleRect { get; set; }
	public Direction direction { get; set; }
	public Single value { get; set; }
	public Single size { get; set; }
	public Int32 numberOfSteps { get; set; }
	public ScrollEvent onValueChanged { get; set; }
	private Single stepSize { get; }
	private Axis axis { get; }
	private Boolean reverseValue { get; }

	// RVA: 0x6a5f358 VA: 0x7599077358
	public RectTransform get_handleRect() { }
	// RVA: 0x6a5f360 VA: 0x7599077360
	public Void set_handleRect(RectTransform value) { }
	// RVA: 0x6a5f664 VA: 0x7599077664
	public Direction get_direction() { }
	// RVA: 0x6a5f66c VA: 0x759907766c
	public Void set_direction(Direction value) { }
	// RVA: 0x6a5f6e0 VA: 0x75990776e0
	protected Void .ctor() { }
	// RVA: 0x6a5f948 VA: 0x7599077948
	public Single get_value() { }
	// RVA: 0x6a5fa00 VA: 0x7599077a00
	public Void set_value(Single value) { }
	// RVA: 0x6a5facc VA: 0x7599077acc
	public virtual Void SetValueWithoutNotify(Single input) { }
	// RVA: 0x6a5fad4 VA: 0x7599077ad4
	public Single get_size() { }
	// RVA: 0x6a5fadc VA: 0x7599077adc
	public Void set_size(Single value) { }
	// RVA: 0x6a5fb60 VA: 0x7599077b60
	public Int32 get_numberOfSteps() { }
	// RVA: 0x6a5fb68 VA: 0x7599077b68
	public Void set_numberOfSteps(Int32 value) { }
	// RVA: 0x6a5fbec VA: 0x7599077bec
	public ScrollEvent get_onValueChanged() { }
	// RVA: 0x6a5fbf4 VA: 0x7599077bf4
	public Void set_onValueChanged(ScrollEvent value) { }
	// RVA: 0x6a5fc04 VA: 0x7599077c04
	private Single get_stepSize() { }
	// RVA: 0x6a5fc30 VA: 0x7599077c30
	public virtual Void Rebuild(CanvasUpdate executing) { }
	// RVA: 0x6a5fc34 VA: 0x7599077c34
	public virtual Void LayoutComplete() { }
	// RVA: 0x6a5fc38 VA: 0x7599077c38
	public virtual Void GraphicUpdateComplete() { }
	// RVA: 0x6a5fc3c VA: 0x7599077c3c
	protected override Void OnEnable() { }
	// RVA: 0x6a5ff3c VA: 0x7599077f3c
	protected override Void OnDisable() { }
	// RVA: 0x6a60094 VA: 0x7599078094
	protected virtual Void Update() { }
	// RVA: 0x6a5f3dc VA: 0x75990773dc
	private Void UpdateCachedReferences() { }
	// RVA: 0x6a5fa08 VA: 0x7599077a08
	private Void Set(Single input, Boolean sendCallback) { }
	// RVA: 0x6a600a8 VA: 0x75990780a8
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x6a600e0 VA: 0x75990780e0
	private Axis get_axis() { }
	// RVA: 0x6a600f0 VA: 0x75990780f0
	private Boolean get_reverseValue() { }
	// RVA: 0x6a5f4cc VA: 0x75990774cc
	private Void UpdateVisuals() { }
	// RVA: 0x6a60104 VA: 0x7599078104
	private Void UpdateDrag(PointerEventData eventData) { }
	// RVA: 0x6a60368 VA: 0x7599078368
	private Void DoUpdateDrag(Vector2 handleCorner, Single remainingSize) { }
	// RVA: 0x6a603cc VA: 0x75990783cc
	private Boolean MayDrag(PointerEventData eventData) { }
	// RVA: 0x6a60430 VA: 0x7599078430
	public virtual Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x6a605ec VA: 0x75990785ec
	public virtual Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x6a6067c VA: 0x759907867c
	public override Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x6a608e8 VA: 0x75990788e8
	protected IEnumerator ClickRepeat(PointerEventData eventData) { }
	// RVA: 0x6a60844 VA: 0x7599078844
	protected IEnumerator ClickRepeat(Vector2 screenPosition, Camera camera) { }
	// RVA: 0x6a60950 VA: 0x7599078950
	public override Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x6a60990 VA: 0x7599078990
	public override Void OnMove(AxisEventData eventData) { }
	// RVA: 0x6a60ce0 VA: 0x7599078ce0
	public override Selectable FindSelectableOnLeft() { }
	// RVA: 0x6a60ddc VA: 0x7599078ddc
	public override Selectable FindSelectableOnRight() { }
	// RVA: 0x6a60ed8 VA: 0x7599078ed8
	public override Selectable FindSelectableOnUp() { }
	// RVA: 0x6a60fd4 VA: 0x7599078fd4
	public override Selectable FindSelectableOnDown() { }
	// RVA: 0x6a610d0 VA: 0x75990790d0
	public virtual Void OnInitializePotentialDrag(PointerEventData eventData) { }
	// RVA: 0x6a610e8 VA: 0x75990790e8
	public Void SetDirection(Direction direction, Boolean includeRectLayouts) { }
	// RVA: 0x6a61260 VA: 0x7599079260
	private Transform UnityEngine.UI.ICanvasElement.get_transform() { }
}
```