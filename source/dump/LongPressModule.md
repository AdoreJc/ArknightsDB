# LongPressModule

**Namespace:** ` `


## Fields

- `Boolean useLongPress`

- `Boolean continuous`

- `Boolean excludeClick`

- `Single pThresSecs`

- `Single intervalSecs`

- `ButtonClickedEvent events`

- `Int32 m_pointerId`

- `Double m_timestamp`

- `Double m_lastUpdateTs`

- `Boolean <inLongPressState>k__BackingField`


## Properties

- `Boolean inLongPressState`

- `Int32 pointerId`


## Methods

- `Boolean get_inLongPressState()`

- `Void set_inLongPressState(Boolean)`

- `Int32 get_pointerId()`

- `Boolean OnPointerDown(PointerEventData)`

- `Boolean ExcludeNormalClick()`

- `Boolean TickDuringPress(Single)`

- `Void _ResetPressStatus()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class LongPressModule
{
	public Boolean useLongPress; // 0x10
	public Boolean continuous; // 0x11
	public Boolean excludeClick; // 0x12
	public Single pThresSecs; // 0x14
	public Single intervalSecs; // 0x18
	public ButtonClickedEvent events; // 0x20
	private Int32 m_pointerId; // 0x28
	private Double m_timestamp; // 0x30
	private Double m_lastUpdateTs; // 0x38
	private Boolean <inLongPressState>k__BackingField; // 0x40

	public Boolean inLongPressState { get; set; }
	public Int32 pointerId { get; }

	// RVA: 0x677da14 VA: 0x7598d95a14
	public Boolean get_inLongPressState() { }
	// RVA: 0x677da1c VA: 0x7598d95a1c
	private Void set_inLongPressState(Boolean value) { }
	// RVA: 0x677da28 VA: 0x7598d95a28
	public Int32 get_pointerId() { }
	// RVA: 0x677bd7c VA: 0x7598d93d7c
	public Boolean OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x677da3c VA: 0x7598d95a3c
	public Boolean ExcludeNormalClick() { }
	// RVA: 0x677c76c VA: 0x7598d9476c
	public Boolean TickDuringPress(Single deltaTime) { }
	// RVA: 0x677da30 VA: 0x7598d95a30
	private Void _ResetPressStatus() { }
	// RVA: 0x677cf6c VA: 0x7598d94f6c
	public Void .ctor() { }
}
```