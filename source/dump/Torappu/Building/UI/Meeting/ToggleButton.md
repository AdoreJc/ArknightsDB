# ToggleButton

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `GameObject _onPanel`

- `GameObject _offPanel`

- `Boolean m_on`


## Properties

- `Boolean on`


## Methods

- `Void add_pressed(Action`1)`

- `Void remove_pressed(Action`1)`

- `Boolean get_on()`

- `Void SetToggleState(Boolean)`

- `Void OnPressed()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class ToggleButton : MonoBehaviour
{
	private GameObject _onPanel; // 0x18
	private GameObject _offPanel; // 0x20
	private Action`1 pressed; // 0x28
	private Boolean m_on; // 0x30

	public Boolean on { get; }

	// RVA: 0x3e000c8 VA: 0x75964180c8
	public Void add_pressed(Action`1 value) { }
	// RVA: 0x3e00178 VA: 0x7596418178
	public Void remove_pressed(Action`1 value) { }
	// RVA: 0x3e00228 VA: 0x7596418228
	public Boolean get_on() { }
	// RVA: 0x3e00230 VA: 0x7596418230
	public Void SetToggleState(Boolean on) { }
	// RVA: 0x3e00278 VA: 0x7596418278
	public Void OnPressed() { }
	// RVA: 0x3e00298 VA: 0x7596418298
	private Void OnDestroy() { }
	// RVA: 0x3e002a4 VA: 0x75964182a4
	public Void .ctor() { }
}
```