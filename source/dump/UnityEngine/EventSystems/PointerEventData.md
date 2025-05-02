# PointerEventData

**Namespace:** `UnityEngine.EventSystems`


## Fields

- `GameObject <pointerEnter>k__BackingField`

- `GameObject m_PointerPress`

- `GameObject <lastPress>k__BackingField`

- `GameObject <rawPointerPress>k__BackingField`

- `GameObject <pointerDrag>k__BackingField`

- `GameObject <pointerClick>k__BackingField`

- `RaycastResult <pointerCurrentRaycast>k__BackingField`

- `RaycastResult <pointerPressRaycast>k__BackingField`

- `Boolean <eligibleForClick>k__BackingField`

- `Int32 <pointerId>k__BackingField`

- `Vector2 <position>k__BackingField`

- `Vector2 <delta>k__BackingField`

- `Vector2 <pressPosition>k__BackingField`

- `Vector3 <worldPosition>k__BackingField`

- `Vector3 <worldNormal>k__BackingField`

- `Single <clickTime>k__BackingField`

- `Int32 <clickCount>k__BackingField`

- `Vector2 <scrollDelta>k__BackingField`

- `Boolean <useDragThreshold>k__BackingField`

- `Boolean <dragging>k__BackingField`

- `InputButton <button>k__BackingField`

- `Single <pressure>k__BackingField`

- `Single <tangentialPressure>k__BackingField`

- `Single <altitudeAngle>k__BackingField`

- `Single <azimuthAngle>k__BackingField`

- `Single <twist>k__BackingField`

- `Vector2 <radius>k__BackingField`

- `Vector2 <radiusVariance>k__BackingField`

- `Boolean <fullyExited>k__BackingField`

- `Boolean <reentered>k__BackingField`


## Properties

- `GameObject pointerEnter`

- `GameObject lastPress`

- `GameObject rawPointerPress`

- `GameObject pointerDrag`

- `GameObject pointerClick`

- `RaycastResult pointerCurrentRaycast`

- `RaycastResult pointerPressRaycast`

- `Boolean eligibleForClick`

- `Int32 pointerId`

- `Vector2 position`

- `Vector2 delta`

- `Vector2 pressPosition`

- `Vector3 worldPosition`

- `Vector3 worldNormal`

- `Single clickTime`

- `Int32 clickCount`

- `Vector2 scrollDelta`

- `Boolean useDragThreshold`

- `Boolean dragging`

- `InputButton button`

- `Single pressure`

- `Single tangentialPressure`

- `Single altitudeAngle`

- `Single azimuthAngle`

- `Single twist`

- `Vector2 radius`

- `Vector2 radiusVariance`

- `Boolean fullyExited`

- `Boolean reentered`

- `Camera enterEventCamera`

- `Camera pressEventCamera`

- `GameObject pointerPress`


## Methods

- `GameObject get_pointerEnter()`

- `Void set_pointerEnter(GameObject)`

- `GameObject get_lastPress()`

- `Void set_lastPress(GameObject)`

- `GameObject get_rawPointerPress()`

- `Void set_rawPointerPress(GameObject)`

- `GameObject get_pointerDrag()`

- `Void set_pointerDrag(GameObject)`

- `GameObject get_pointerClick()`

- `Void set_pointerClick(GameObject)`

- `RaycastResult get_pointerCurrentRaycast()`

- `Void set_pointerCurrentRaycast(RaycastResult)`

- `RaycastResult get_pointerPressRaycast()`

- `Void set_pointerPressRaycast(RaycastResult)`

- `Boolean get_eligibleForClick()`

- `Void set_eligibleForClick(Boolean)`

- `Int32 get_pointerId()`

- `Void set_pointerId(Int32)`

- `Vector2 get_position()`

- `Void set_position(Vector2)`

- `Vector2 get_delta()`

- `Void set_delta(Vector2)`

- `Vector2 get_pressPosition()`

- `Void set_pressPosition(Vector2)`

- `Vector3 get_worldPosition()`

- `Void set_worldPosition(Vector3)`

- `Vector3 get_worldNormal()`

- `Void set_worldNormal(Vector3)`

- `Single get_clickTime()`

- `Void set_clickTime(Single)`

- `Int32 get_clickCount()`

- `Void set_clickCount(Int32)`

- `Vector2 get_scrollDelta()`

- `Void set_scrollDelta(Vector2)`

- `Boolean get_useDragThreshold()`

- `Void set_useDragThreshold(Boolean)`

- `Boolean get_dragging()`

- `Void set_dragging(Boolean)`

- `InputButton get_button()`

- `Void set_button(InputButton)`

- `Single get_pressure()`

- `Void set_pressure(Single)`

- `Single get_tangentialPressure()`

- `Void set_tangentialPressure(Single)`

- `Single get_altitudeAngle()`

- `Void set_altitudeAngle(Single)`

- `Single get_azimuthAngle()`

- `Void set_azimuthAngle(Single)`

- `Single get_twist()`

- `Void set_twist(Single)`

- `Vector2 get_radius()`

- `Void set_radius(Vector2)`

- `Vector2 get_radiusVariance()`

- `Void set_radiusVariance(Vector2)`

- `Boolean get_fullyExited()`

- `Void set_fullyExited(Boolean)`

- `Boolean get_reentered()`

- `Void set_reentered(Boolean)`

- `Boolean IsPointerMoving()`

- `Boolean IsScrolling()`

- `Camera get_enterEventCamera()`

- `Camera get_pressEventCamera()`

- `GameObject get_pointerPress()`

- `Void set_pointerPress(GameObject)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.EventSystems
public class PointerEventData : BaseEventData
{
	private GameObject <pointerEnter>k__BackingField; // 0x20
	private GameObject m_PointerPress; // 0x28
	private GameObject <lastPress>k__BackingField; // 0x30
	private GameObject <rawPointerPress>k__BackingField; // 0x38
	private GameObject <pointerDrag>k__BackingField; // 0x40
	private GameObject <pointerClick>k__BackingField; // 0x48
	private RaycastResult <pointerCurrentRaycast>k__BackingField; // 0x50
	private RaycastResult <pointerPressRaycast>k__BackingField; // 0xa0
	public List`1 hovered; // 0xf0
	private Boolean <eligibleForClick>k__BackingField; // 0xf8
	private Int32 <pointerId>k__BackingField; // 0xfc
	private Vector2 <position>k__BackingField; // 0x100
	private Vector2 <delta>k__BackingField; // 0x108
	private Vector2 <pressPosition>k__BackingField; // 0x110
	private Vector3 <worldPosition>k__BackingField; // 0x118
	private Vector3 <worldNormal>k__BackingField; // 0x124
	private Single <clickTime>k__BackingField; // 0x130
	private Int32 <clickCount>k__BackingField; // 0x134
	private Vector2 <scrollDelta>k__BackingField; // 0x138
	private Boolean <useDragThreshold>k__BackingField; // 0x140
	private Boolean <dragging>k__BackingField; // 0x141
	private InputButton <button>k__BackingField; // 0x144
	private Single <pressure>k__BackingField; // 0x148
	private Single <tangentialPressure>k__BackingField; // 0x14c
	private Single <altitudeAngle>k__BackingField; // 0x150
	private Single <azimuthAngle>k__BackingField; // 0x154
	private Single <twist>k__BackingField; // 0x158
	private Vector2 <radius>k__BackingField; // 0x15c
	private Vector2 <radiusVariance>k__BackingField; // 0x164
	private Boolean <fullyExited>k__BackingField; // 0x16c
	private Boolean <reentered>k__BackingField; // 0x16d

	public GameObject pointerEnter { get; set; }
	public GameObject lastPress { get; set; }
	public GameObject rawPointerPress { get; set; }
	public GameObject pointerDrag { get; set; }
	public GameObject pointerClick { get; set; }
	public RaycastResult pointerCurrentRaycast { get; set; }
	public RaycastResult pointerPressRaycast { get; set; }
	public Boolean eligibleForClick { get; set; }
	public Int32 pointerId { get; set; }
	public Vector2 position { get; set; }
	public Vector2 delta { get; set; }
	public Vector2 pressPosition { get; set; }
	public Vector3 worldPosition { get; set; }
	public Vector3 worldNormal { get; set; }
	public Single clickTime { get; set; }
	public Int32 clickCount { get; set; }
	public Vector2 scrollDelta { get; set; }
	public Boolean useDragThreshold { get; set; }
	public Boolean dragging { get; set; }
	public InputButton button { get; set; }
	public Single pressure { get; set; }
	public Single tangentialPressure { get; set; }
	public Single altitudeAngle { get; set; }
	public Single azimuthAngle { get; set; }
	public Single twist { get; set; }
	public Vector2 radius { get; set; }
	public Vector2 radiusVariance { get; set; }
	public Boolean fullyExited { get; set; }
	public Boolean reentered { get; set; }
	public Camera enterEventCamera { get; }
	public Camera pressEventCamera { get; }
	public GameObject pointerPress { get; set; }

	// RVA: 0x6a758cc VA: 0x759908d8cc
	public GameObject get_pointerEnter() { }
	// RVA: 0x6a758d4 VA: 0x759908d8d4
	public Void set_pointerEnter(GameObject value) { }
	// RVA: 0x6a758dc VA: 0x759908d8dc
	public GameObject get_lastPress() { }
	// RVA: 0x6a758e4 VA: 0x759908d8e4
	private Void set_lastPress(GameObject value) { }
	// RVA: 0x6a758ec VA: 0x759908d8ec
	public GameObject get_rawPointerPress() { }
	// RVA: 0x6a758f4 VA: 0x759908d8f4
	public Void set_rawPointerPress(GameObject value) { }
	// RVA: 0x6a758fc VA: 0x759908d8fc
	public GameObject get_pointerDrag() { }
	// RVA: 0x6a75904 VA: 0x759908d904
	public Void set_pointerDrag(GameObject value) { }
	// RVA: 0x6a7590c VA: 0x759908d90c
	public GameObject get_pointerClick() { }
	// RVA: 0x6a75914 VA: 0x759908d914
	public Void set_pointerClick(GameObject value) { }
	// RVA: 0x6a7591c VA: 0x759908d91c
	public RaycastResult get_pointerCurrentRaycast() { }
	// RVA: 0x6a7592c VA: 0x759908d92c
	public Void set_pointerCurrentRaycast(RaycastResult value) { }
	// RVA: 0x6a75950 VA: 0x759908d950
	public RaycastResult get_pointerPressRaycast() { }
	// RVA: 0x6a75960 VA: 0x759908d960
	public Void set_pointerPressRaycast(RaycastResult value) { }
	// RVA: 0x6a75984 VA: 0x759908d984
	public Boolean get_eligibleForClick() { }
	// RVA: 0x6a7598c VA: 0x759908d98c
	public Void set_eligibleForClick(Boolean value) { }
	// RVA: 0x6a75998 VA: 0x759908d998
	public Int32 get_pointerId() { }
	// RVA: 0x6a759a0 VA: 0x759908d9a0
	public Void set_pointerId(Int32 value) { }
	// RVA: 0x6a759a8 VA: 0x759908d9a8
	public Vector2 get_position() { }
	// RVA: 0x6a759b4 VA: 0x759908d9b4
	public Void set_position(Vector2 value) { }
	// RVA: 0x6a759c0 VA: 0x759908d9c0
	public Vector2 get_delta() { }
	// RVA: 0x6a759cc VA: 0x759908d9cc
	public Void set_delta(Vector2 value) { }
	// RVA: 0x6a759d8 VA: 0x759908d9d8
	public Vector2 get_pressPosition() { }
	// RVA: 0x6a759e4 VA: 0x759908d9e4
	public Void set_pressPosition(Vector2 value) { }
	// RVA: 0x6a759f0 VA: 0x759908d9f0
	public Vector3 get_worldPosition() { }
	// RVA: 0x6a75a00 VA: 0x759908da00
	public Void set_worldPosition(Vector3 value) { }
	// RVA: 0x6a75a10 VA: 0x759908da10
	public Vector3 get_worldNormal() { }
	// RVA: 0x6a75a20 VA: 0x759908da20
	public Void set_worldNormal(Vector3 value) { }
	// RVA: 0x6a75a30 VA: 0x759908da30
	public Single get_clickTime() { }
	// RVA: 0x6a75a38 VA: 0x759908da38
	public Void set_clickTime(Single value) { }
	// RVA: 0x6a75a40 VA: 0x759908da40
	public Int32 get_clickCount() { }
	// RVA: 0x6a75a48 VA: 0x759908da48
	public Void set_clickCount(Int32 value) { }
	// RVA: 0x6a75a50 VA: 0x759908da50
	public Vector2 get_scrollDelta() { }
	// RVA: 0x6a75a5c VA: 0x759908da5c
	public Void set_scrollDelta(Vector2 value) { }
	// RVA: 0x6a75a68 VA: 0x759908da68
	public Boolean get_useDragThreshold() { }
	// RVA: 0x6a75a70 VA: 0x759908da70
	public Void set_useDragThreshold(Boolean value) { }
	// RVA: 0x6a75a7c VA: 0x759908da7c
	public Boolean get_dragging() { }
	// RVA: 0x6a75a84 VA: 0x759908da84
	public Void set_dragging(Boolean value) { }
	// RVA: 0x6a75a90 VA: 0x759908da90
	public InputButton get_button() { }
	// RVA: 0x6a75a98 VA: 0x759908da98
	public Void set_button(InputButton value) { }
	// RVA: 0x6a75aa0 VA: 0x759908daa0
	public Single get_pressure() { }
	// RVA: 0x6a75aa8 VA: 0x759908daa8
	public Void set_pressure(Single value) { }
	// RVA: 0x6a75ab0 VA: 0x759908dab0
	public Single get_tangentialPressure() { }
	// RVA: 0x6a75ab8 VA: 0x759908dab8
	public Void set_tangentialPressure(Single value) { }
	// RVA: 0x6a75ac0 VA: 0x759908dac0
	public Single get_altitudeAngle() { }
	// RVA: 0x6a75ac8 VA: 0x759908dac8
	public Void set_altitudeAngle(Single value) { }
	// RVA: 0x6a75ad0 VA: 0x759908dad0
	public Single get_azimuthAngle() { }
	// RVA: 0x6a75ad8 VA: 0x759908dad8
	public Void set_azimuthAngle(Single value) { }
	// RVA: 0x6a75ae0 VA: 0x759908dae0
	public Single get_twist() { }
	// RVA: 0x6a75ae8 VA: 0x759908dae8
	public Void set_twist(Single value) { }
	// RVA: 0x6a75af0 VA: 0x759908daf0
	public Vector2 get_radius() { }
	// RVA: 0x6a75afc VA: 0x759908dafc
	public Void set_radius(Vector2 value) { }
	// RVA: 0x6a75b08 VA: 0x759908db08
	public Vector2 get_radiusVariance() { }
	// RVA: 0x6a75b14 VA: 0x759908db14
	public Void set_radiusVariance(Vector2 value) { }
	// RVA: 0x6a75b20 VA: 0x759908db20
	public Boolean get_fullyExited() { }
	// RVA: 0x6a75b28 VA: 0x759908db28
	public Void set_fullyExited(Boolean value) { }
	// RVA: 0x6a75b34 VA: 0x759908db34
	public Boolean get_reentered() { }
	// RVA: 0x6a75b3c VA: 0x759908db3c
	public Void set_reentered(Boolean value) { }
	// RVA: 0x6a75b48 VA: 0x759908db48
	public Void .ctor(EventSystem eventSystem) { }
	// RVA: 0x6a75c90 VA: 0x759908dc90
	public Boolean IsPointerMoving() { }
	// RVA: 0x6a75cb0 VA: 0x759908dcb0
	public Boolean IsScrolling() { }
	// RVA: 0x6a75cd0 VA: 0x759908dcd0
	public Camera get_enterEventCamera() { }
	// RVA: 0x6a75d60 VA: 0x759908dd60
	public Camera get_pressEventCamera() { }
	// RVA: 0x6a75df0 VA: 0x759908ddf0
	public GameObject get_pointerPress() { }
	// RVA: 0x6a75df8 VA: 0x759908ddf8
	public Void set_pointerPress(GameObject value) { }
	// RVA: 0x6a75e9c VA: 0x759908de9c
	public override String ToString() { }
}
```