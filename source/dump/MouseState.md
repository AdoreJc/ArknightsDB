# MouseState

**Namespace:** ` `


## Methods

- `Boolean AnyPressesThisFrame()`

- `Boolean AnyReleasesThisFrame()`

- `ButtonState GetButtonState(InputButton)`

- `Void SetButtonState(InputButton, FramePressState, PointerEventData)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : 
protected class MouseState
{
	private List`1 m_TrackedButtons; // 0x10


	// RVA: 0x6a7d698 VA: 0x7599095698
	public Boolean AnyPressesThisFrame() { }
	// RVA: 0x6a7d75c VA: 0x759909575c
	public Boolean AnyReleasesThisFrame() { }
	// RVA: 0x6a7d828 VA: 0x7599095828
	public ButtonState GetButtonState(InputButton button) { }
	// RVA: 0x6a7cbec VA: 0x7599094bec
	public Void SetButtonState(InputButton button, FramePressState stateForMouseButton, PointerEventData data) { }
	// RVA: 0x6a7d5e8 VA: 0x75990955e8
	public Void .ctor() { }
}
```