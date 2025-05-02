# StandaloneInputModule

**Namespace:** `UnityEngine.EventSystems`


## Fields

- `Single m_PrevActionTime`

- `Vector2 m_LastMoveVector`

- `Int32 m_ConsecutiveMoveCount`

- `Vector2 m_LastMousePosition`

- `Vector2 m_MousePosition`

- `GameObject m_CurrentFocusedGameObject`

- `PointerEventData m_InputPointerEvent`

- `String m_HorizontalAxis`

- `String m_VerticalAxis`

- `String m_SubmitButton`

- `String m_CancelButton`

- `Single m_InputActionsPerSecond`

- `Single m_RepeatDelay`

- `Boolean m_ForceModuleActive`


## Properties

- `InputMode inputMode`

- `Boolean allowActivationOnMobileDevice`

- `Boolean forceModuleActive`

- `Single inputActionsPerSecond`

- `Single repeatDelay`

- `String horizontalAxis`

- `String verticalAxis`

- `String submitButton`

- `String cancelButton`


## Methods

- `InputMode get_inputMode()`

- `Boolean get_allowActivationOnMobileDevice()`

- `Void set_allowActivationOnMobileDevice(Boolean)`

- `Boolean get_forceModuleActive()`

- `Void set_forceModuleActive(Boolean)`

- `Single get_inputActionsPerSecond()`

- `Void set_inputActionsPerSecond(Single)`

- `Single get_repeatDelay()`

- `Void set_repeatDelay(Single)`

- `String get_horizontalAxis()`

- `Void set_horizontalAxis(String)`

- `String get_verticalAxis()`

- `Void set_verticalAxis(String)`

- `String get_submitButton()`

- `Void set_submitButton(String)`

- `String get_cancelButton()`

- `Void set_cancelButton(String)`

- `Boolean ShouldIgnoreEventsOnNoFocus()`

- `Void ReleaseMouse(PointerEventData, GameObject)`

- `Boolean ProcessTouchEvents()`

- `Void ProcessTouchPress(PointerEventData, Boolean, Boolean)`

- `Boolean SendSubmitEventToSelectedObject()`

- `Vector2 GetRawMoveVector()`

- `Boolean SendMoveEventToSelectedObject()`

- `Void ProcessMouseEvent()`

- `Void ProcessMouseEvent(Int32)`

- `Boolean SendUpdateEventToSelectedObject()`

- `Void ProcessMousePress(MouseButtonEventData)`

- `GameObject GetCurrentFocusedGameObject()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.EventSystems
public class StandaloneInputModule : PointerInputModule
{
	private Single m_PrevActionTime; // 0x60
	private Vector2 m_LastMoveVector; // 0x64
	private Int32 m_ConsecutiveMoveCount; // 0x6c
	private Vector2 m_LastMousePosition; // 0x70
	private Vector2 m_MousePosition; // 0x78
	private GameObject m_CurrentFocusedGameObject; // 0x80
	private PointerEventData m_InputPointerEvent; // 0x88
	private String m_HorizontalAxis; // 0x90
	private String m_VerticalAxis; // 0x98
	private String m_SubmitButton; // 0xa0
	private String m_CancelButton; // 0xa8
	private Single m_InputActionsPerSecond; // 0xb0
	private Single m_RepeatDelay; // 0xb4
	private Boolean m_ForceModuleActive; // 0xb8

	public InputMode inputMode { get; }
	public Boolean allowActivationOnMobileDevice { get; set; }
	public Boolean forceModuleActive { get; set; }
	public Single inputActionsPerSecond { get; set; }
	public Single repeatDelay { get; set; }
	public String horizontalAxis { get; set; }
	public String verticalAxis { get; set; }
	public String submitButton { get; set; }
	public String cancelButton { get; set; }

	// RVA: 0x6a7d9e0 VA: 0x75990959e0
	protected Void .ctor() { }
	// RVA: 0x6a7dabc VA: 0x7599095abc
	public InputMode get_inputMode() { }
	// RVA: 0x6a7dac4 VA: 0x7599095ac4
	public Boolean get_allowActivationOnMobileDevice() { }
	// RVA: 0x6a7dacc VA: 0x7599095acc
	public Void set_allowActivationOnMobileDevice(Boolean value) { }
	// RVA: 0x6a7dad8 VA: 0x7599095ad8
	public Boolean get_forceModuleActive() { }
	// RVA: 0x6a7dae0 VA: 0x7599095ae0
	public Void set_forceModuleActive(Boolean value) { }
	// RVA: 0x6a7daec VA: 0x7599095aec
	public Single get_inputActionsPerSecond() { }
	// RVA: 0x6a7daf4 VA: 0x7599095af4
	public Void set_inputActionsPerSecond(Single value) { }
	// RVA: 0x6a7dafc VA: 0x7599095afc
	public Single get_repeatDelay() { }
	// RVA: 0x6a7db04 VA: 0x7599095b04
	public Void set_repeatDelay(Single value) { }
	// RVA: 0x6a7db0c VA: 0x7599095b0c
	public String get_horizontalAxis() { }
	// RVA: 0x6a7db14 VA: 0x7599095b14
	public Void set_horizontalAxis(String value) { }
	// RVA: 0x6a7db1c VA: 0x7599095b1c
	public String get_verticalAxis() { }
	// RVA: 0x6a7db24 VA: 0x7599095b24
	public Void set_verticalAxis(String value) { }
	// RVA: 0x6a7db2c VA: 0x7599095b2c
	public String get_submitButton() { }
	// RVA: 0x6a7db34 VA: 0x7599095b34
	public Void set_submitButton(String value) { }
	// RVA: 0x6a7db3c VA: 0x7599095b3c
	public String get_cancelButton() { }
	// RVA: 0x6a7db44 VA: 0x7599095b44
	public Void set_cancelButton(String value) { }
	// RVA: 0x6a7db4c VA: 0x7599095b4c
	private Boolean ShouldIgnoreEventsOnNoFocus() { }
	// RVA: 0x6a7db54 VA: 0x7599095b54
	public override Void UpdateModule() { }
	// RVA: 0x6a7dc38 VA: 0x7599095c38
	private Void ReleaseMouse(PointerEventData pointerEvent, GameObject currentOverGo) { }
	// RVA: 0x6a7dfdc VA: 0x7599095fdc
	public override Boolean ShouldActivateModule() { }
	// RVA: 0x6a7e210 VA: 0x7599096210
	public override Void ActivateModule() { }
	// RVA: 0x6a7e310 VA: 0x7599096310
	public override Void DeactivateModule() { }
	// RVA: 0x6a7e314 VA: 0x7599096314
	public override Void Process() { }
	// RVA: 0x6a7e500 VA: 0x7599096500
	private Boolean ProcessTouchEvents() { }
	// RVA: 0x6a7eadc VA: 0x7599096adc
	protected Void ProcessTouchPress(PointerEventData pointerEvent, Boolean pressed, Boolean released) { }
	// RVA: 0x6a7e8d0 VA: 0x75990968d0
	protected Boolean SendSubmitEventToSelectedObject() { }
	// RVA: 0x6a7f1d4 VA: 0x75990971d4
	private Vector2 GetRawMoveVector() { }
	// RVA: 0x6a7e66c VA: 0x759909666c
	protected Boolean SendMoveEventToSelectedObject() { }
	// RVA: 0x6a7e664 VA: 0x7599096664
	protected Void ProcessMouseEvent() { }
	// RVA: 0x6a7f594 VA: 0x7599097594
	protected virtual Boolean ForceAutoSelect() { }
	// RVA: 0x6a7f2e4 VA: 0x75990972e4
	protected Void ProcessMouseEvent(Int32 id) { }
	// RVA: 0x6a7e3b8 VA: 0x75990963b8
	protected Boolean SendUpdateEventToSelectedObject() { }
	// RVA: 0x6a7f59c VA: 0x759909759c
	protected Void ProcessMousePress(MouseButtonEventData data) { }
	// RVA: 0x6a7f938 VA: 0x7599097938
	protected GameObject GetCurrentFocusedGameObject() { }
}
```