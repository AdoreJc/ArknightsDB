# TouchInputModule

**Namespace:** `UnityEngine.EventSystems`


## Fields

- `Vector2 m_LastMousePosition`

- `Vector2 m_MousePosition`

- `PointerEventData m_InputPointerEvent`

- `Boolean m_ForceModuleActive`


## Properties

- `Boolean allowActivationOnStandalone`

- `Boolean forceModuleActive`


## Methods

- `Boolean get_allowActivationOnStandalone()`

- `Void set_allowActivationOnStandalone(Boolean)`

- `Boolean get_forceModuleActive()`

- `Void set_forceModuleActive(Boolean)`

- `Boolean UseFakeInput()`

- `Void FakeTouches()`

- `Void ProcessTouchEvents()`

- `Void ProcessTouchPress(PointerEventData, Boolean, Boolean)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.EventSystems
public class TouchInputModule : PointerInputModule
{
	private Vector2 m_LastMousePosition; // 0x60
	private Vector2 m_MousePosition; // 0x68
	private PointerEventData m_InputPointerEvent; // 0x70
	private Boolean m_ForceModuleActive; // 0x78

	public Boolean allowActivationOnStandalone { get; set; }
	public Boolean forceModuleActive { get; set; }

	// RVA: 0x6a7f940 VA: 0x7599097940
	protected Void .ctor() { }
	// RVA: 0x6a7f944 VA: 0x7599097944
	public Boolean get_allowActivationOnStandalone() { }
	// RVA: 0x6a7f94c VA: 0x759909794c
	public Void set_allowActivationOnStandalone(Boolean value) { }
	// RVA: 0x6a7f958 VA: 0x7599097958
	public Boolean get_forceModuleActive() { }
	// RVA: 0x6a7f960 VA: 0x7599097960
	public Void set_forceModuleActive(Boolean value) { }
	// RVA: 0x6a7f96c VA: 0x759909796c
	public override Void UpdateModule() { }
	// RVA: 0x6a7fad4 VA: 0x7599097ad4
	public override Boolean IsModuleSupported() { }
	// RVA: 0x6a7fb0c VA: 0x7599097b0c
	public override Boolean ShouldActivateModule() { }
	// RVA: 0x6a7fbb0 VA: 0x7599097bb0
	private Boolean UseFakeInput() { }
	// RVA: 0x6a7fbe0 VA: 0x7599097be0
	public override Void Process() { }
	// RVA: 0x6a7fc08 VA: 0x7599097c08
	private Void FakeTouches() { }
	// RVA: 0x6a7fd2c VA: 0x7599097d2c
	private Void ProcessTouchEvents() { }
	// RVA: 0x6a7fe74 VA: 0x7599097e74
	protected Void ProcessTouchPress(PointerEventData pointerEvent, Boolean pressed, Boolean released) { }
	// RVA: 0x6a80578 VA: 0x7599098578
	public override Void DeactivateModule() { }
	// RVA: 0x6a8057c VA: 0x759909857c
	public override String ToString() { }
}
```