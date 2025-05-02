# ButtonState

**Namespace:** ` `


## Fields

- `InputButton m_Button`

- `MouseButtonEventData m_EventData`


## Properties

- `MouseButtonEventData eventData`

- `InputButton button`


## Methods

- `MouseButtonEventData get_eventData()`

- `Void set_eventData(MouseButtonEventData)`

- `InputButton get_button()`

- `Void set_button(InputButton)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : 
protected class ButtonState
{
	private InputButton m_Button; // 0x10
	private MouseButtonEventData m_EventData; // 0x18

	public MouseButtonEventData eventData { get; set; }
	public InputButton button { get; set; }

	// RVA: 0x6a7d670 VA: 0x7599095670
	public MouseButtonEventData get_eventData() { }
	// RVA: 0x6a7d678 VA: 0x7599095678
	public Void set_eventData(MouseButtonEventData value) { }
	// RVA: 0x6a7d680 VA: 0x7599095680
	public InputButton get_button() { }
	// RVA: 0x6a7d688 VA: 0x7599095688
	public Void set_button(InputButton value) { }
	// RVA: 0x6a7d690 VA: 0x7599095690
	public Void .ctor() { }
}
```