# PointerEvent

**Namespace:** ` `


## Fields

- `Int32 <pointerId>k__BackingField`

- `String <pointerType>k__BackingField`

- `Boolean <isPrimary>k__BackingField`

- `Int32 <button>k__BackingField`

- `Int32 <pressedButtons>k__BackingField`

- `Vector3 <position>k__BackingField`

- `Vector3 <localPosition>k__BackingField`

- `Vector3 <deltaPosition>k__BackingField`

- `Single <deltaTime>k__BackingField`

- `Int32 <clickCount>k__BackingField`

- `Single <pressure>k__BackingField`

- `Single <tangentialPressure>k__BackingField`

- `Single <altitudeAngle>k__BackingField`

- `Single <azimuthAngle>k__BackingField`

- `Single <twist>k__BackingField`

- `Vector2 <radius>k__BackingField`

- `Vector2 <radiusVariance>k__BackingField`

- `EventModifiers <modifiers>k__BackingField`


## Properties

- `Int32 pointerId`

- `String pointerType`

- `Boolean isPrimary`

- `Int32 button`

- `Int32 pressedButtons`

- `Vector3 position`

- `Vector3 localPosition`

- `Vector3 deltaPosition`

- `Single deltaTime`

- `Int32 clickCount`

- `Single pressure`

- `Single tangentialPressure`

- `Single altitudeAngle`

- `Single azimuthAngle`

- `Single twist`

- `Vector2 radius`

- `Vector2 radiusVariance`

- `EventModifiers modifiers`

- `Boolean shiftKey`

- `Boolean ctrlKey`

- `Boolean commandKey`

- `Boolean altKey`

- `Boolean actionKey`


## Methods

- `Int32 get_pointerId()`

- `Void set_pointerId(Int32)`

- `String get_pointerType()`

- `Void set_pointerType(String)`

- `Boolean get_isPrimary()`

- `Void set_isPrimary(Boolean)`

- `Int32 get_button()`

- `Void set_button(Int32)`

- `Int32 get_pressedButtons()`

- `Void set_pressedButtons(Int32)`

- `Vector3 get_position()`

- `Void set_position(Vector3)`

- `Vector3 get_localPosition()`

- `Void set_localPosition(Vector3)`

- `Vector3 get_deltaPosition()`

- `Void set_deltaPosition(Vector3)`

- `Single get_deltaTime()`

- `Void set_deltaTime(Single)`

- `Int32 get_clickCount()`

- `Void set_clickCount(Int32)`

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

- `EventModifiers get_modifiers()`

- `Void set_modifiers(EventModifiers)`

- `Boolean get_shiftKey()`

- `Boolean get_ctrlKey()`

- `Boolean get_commandKey()`

- `Boolean get_altKey()`

- `Boolean get_actionKey()`

- `Void Read(PanelEventHandler, PointerEventData, PointerEventType)`

- `Void SetPosition(Vector3, Vector3)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : 
private class PointerEvent : IPointerEvent
{
	private Int32 <pointerId>k__BackingField; // 0x10
	private String <pointerType>k__BackingField; // 0x18
	private Boolean <isPrimary>k__BackingField; // 0x20
	private Int32 <button>k__BackingField; // 0x24
	private Int32 <pressedButtons>k__BackingField; // 0x28
	private Vector3 <position>k__BackingField; // 0x2c
	private Vector3 <localPosition>k__BackingField; // 0x38
	private Vector3 <deltaPosition>k__BackingField; // 0x44
	private Single <deltaTime>k__BackingField; // 0x50
	private Int32 <clickCount>k__BackingField; // 0x54
	private Single <pressure>k__BackingField; // 0x58
	private Single <tangentialPressure>k__BackingField; // 0x5c
	private Single <altitudeAngle>k__BackingField; // 0x60
	private Single <azimuthAngle>k__BackingField; // 0x64
	private Single <twist>k__BackingField; // 0x68
	private Vector2 <radius>k__BackingField; // 0x6c
	private Vector2 <radiusVariance>k__BackingField; // 0x74
	private EventModifiers <modifiers>k__BackingField; // 0x7c

	public Int32 pointerId { get; set; }
	public String pointerType { get; set; }
	public Boolean isPrimary { get; set; }
	public Int32 button { get; set; }
	public Int32 pressedButtons { get; set; }
	public Vector3 position { get; set; }
	public Vector3 localPosition { get; set; }
	public Vector3 deltaPosition { get; set; }
	public Single deltaTime { get; set; }
	public Int32 clickCount { get; set; }
	public Single pressure { get; set; }
	public Single tangentialPressure { get; set; }
	public Single altitudeAngle { get; set; }
	public Single azimuthAngle { get; set; }
	public Single twist { get; set; }
	public Vector2 radius { get; set; }
	public Vector2 radiusVariance { get; set; }
	public EventModifiers modifiers { get; set; }
	public Boolean shiftKey { get; }
	public Boolean ctrlKey { get; }
	public Boolean commandKey { get; }
	public Boolean altKey { get; }
	public Boolean actionKey { get; }

	// RVA: 0x6a74b8c VA: 0x759908cb8c
	public Int32 get_pointerId() { }
	// RVA: 0x6a74b94 VA: 0x759908cb94
	private Void set_pointerId(Int32 value) { }
	// RVA: 0x6a74b9c VA: 0x759908cb9c
	public String get_pointerType() { }
	// RVA: 0x6a74ba4 VA: 0x759908cba4
	private Void set_pointerType(String value) { }
	// RVA: 0x6a74bac VA: 0x759908cbac
	public Boolean get_isPrimary() { }
	// RVA: 0x6a74bb4 VA: 0x759908cbb4
	private Void set_isPrimary(Boolean value) { }
	// RVA: 0x6a74bc0 VA: 0x759908cbc0
	public Int32 get_button() { }
	// RVA: 0x6a74bc8 VA: 0x759908cbc8
	private Void set_button(Int32 value) { }
	// RVA: 0x6a74bd0 VA: 0x759908cbd0
	public Int32 get_pressedButtons() { }
	// RVA: 0x6a74bd8 VA: 0x759908cbd8
	private Void set_pressedButtons(Int32 value) { }
	// RVA: 0x6a74be0 VA: 0x759908cbe0
	public Vector3 get_position() { }
	// RVA: 0x6a74bec VA: 0x759908cbec
	private Void set_position(Vector3 value) { }
	// RVA: 0x6a74bf8 VA: 0x759908cbf8
	public Vector3 get_localPosition() { }
	// RVA: 0x6a74c04 VA: 0x759908cc04
	private Void set_localPosition(Vector3 value) { }
	// RVA: 0x6a74c10 VA: 0x759908cc10
	public Vector3 get_deltaPosition() { }
	// RVA: 0x6a74c1c VA: 0x759908cc1c
	private Void set_deltaPosition(Vector3 value) { }
	// RVA: 0x6a74c28 VA: 0x759908cc28
	public Single get_deltaTime() { }
	// RVA: 0x6a74c30 VA: 0x759908cc30
	private Void set_deltaTime(Single value) { }
	// RVA: 0x6a74c38 VA: 0x759908cc38
	public Int32 get_clickCount() { }
	// RVA: 0x6a74c40 VA: 0x759908cc40
	private Void set_clickCount(Int32 value) { }
	// RVA: 0x6a74c48 VA: 0x759908cc48
	public Single get_pressure() { }
	// RVA: 0x6a74c50 VA: 0x759908cc50
	private Void set_pressure(Single value) { }
	// RVA: 0x6a74c58 VA: 0x759908cc58
	public Single get_tangentialPressure() { }
	// RVA: 0x6a74c60 VA: 0x759908cc60
	private Void set_tangentialPressure(Single value) { }
	// RVA: 0x6a74c68 VA: 0x759908cc68
	public Single get_altitudeAngle() { }
	// RVA: 0x6a74c70 VA: 0x759908cc70
	private Void set_altitudeAngle(Single value) { }
	// RVA: 0x6a74c78 VA: 0x759908cc78
	public Single get_azimuthAngle() { }
	// RVA: 0x6a74c80 VA: 0x759908cc80
	private Void set_azimuthAngle(Single value) { }
	// RVA: 0x6a74c88 VA: 0x759908cc88
	public Single get_twist() { }
	// RVA: 0x6a74c90 VA: 0x759908cc90
	private Void set_twist(Single value) { }
	// RVA: 0x6a74c98 VA: 0x759908cc98
	public Vector2 get_radius() { }
	// RVA: 0x6a74ca0 VA: 0x759908cca0
	private Void set_radius(Vector2 value) { }
	// RVA: 0x6a74ca8 VA: 0x759908cca8
	public Vector2 get_radiusVariance() { }
	// RVA: 0x6a74cb0 VA: 0x759908ccb0
	private Void set_radiusVariance(Vector2 value) { }
	// RVA: 0x6a74cb8 VA: 0x759908ccb8
	public EventModifiers get_modifiers() { }
	// RVA: 0x6a74cc0 VA: 0x759908ccc0
	private Void set_modifiers(EventModifiers value) { }
	// RVA: 0x6a74cc8 VA: 0x759908ccc8
	public Boolean get_shiftKey() { }
	// RVA: 0x6a74cd4 VA: 0x759908ccd4
	public Boolean get_ctrlKey() { }
	// RVA: 0x6a74ce0 VA: 0x759908cce0
	public Boolean get_commandKey() { }
	// RVA: 0x6a74cec VA: 0x759908ccec
	public Boolean get_altKey() { }
	// RVA: 0x6a74cf8 VA: 0x759908ccf8
	public Boolean get_actionKey() { }
	// RVA: 0x6a74610 VA: 0x759908c610
	public Void Read(PanelEventHandler self, PointerEventData eventData, PointerEventType eventType) { }
	// RVA: 0x6a74ab4 VA: 0x759908cab4
	public Void SetPosition(Vector3 positionOverride, Vector3 deltaOverride) { }
	// RVA: 0x6a74b7c VA: 0x759908cb7c
	public Void .ctor() { }
	// RVA: 0x6a74d3c VA: 0x759908cd3c
	internal static Boolean <Read>g__InRange|82_0(Int32 i, Int32 start, Int32 count) { }
}
```