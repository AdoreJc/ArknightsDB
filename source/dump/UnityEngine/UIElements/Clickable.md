# Clickable

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Action clicked`

- `Boolean <active>k__BackingField`

- `Vector2 <lastMousePosition>k__BackingField`

- `Int32 m_ActivePointerId`

- `Boolean m_AcceptClicksIfDisabled`

- `IVisualElementScheduledItem m_Repeater`


## Properties

- `Boolean active`

- `Vector2 lastMousePosition`

- `InvokePolicy invokePolicy`


## Methods

- `Void add_clicked(Action)`

- `Void remove_clicked(Action)`

- `Boolean get_active()`

- `Void set_active(Boolean)`

- `Vector2 get_lastMousePosition()`

- `Void set_lastMousePosition(Vector2)`

- `InvokePolicy get_invokePolicy()`

- `Void OnTimer(TimerState)`

- `Boolean IsRepeatable()`

- `Void OnMouseDown(MouseDownEvent)`

- `Void OnMouseMove(MouseMoveEvent)`

- `Void OnMouseUp(MouseUpEvent)`

- `Void OnMouseCaptureOut(MouseCaptureOutEvent)`

- `Void OnPointerDown(PointerDownEvent)`

- `Void OnPointerMove(PointerMoveEvent)`

- `Void OnPointerUp(PointerUpEvent)`

- `Void OnPointerCancel(PointerCancelEvent)`

- `Void OnPointerCaptureOut(PointerCaptureOutEvent)`

- `Boolean ContainsPointer(Int32)`

- `Void Invoke(EventBase)`

- `Void <SimulateSingleClick>b__43_0()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class Clickable : PointerManipulator
{
	private Action`1 clickedWithEventInfo; // 0x30
	private Action clicked; // 0x38
	private readonly Int64 m_Delay; // 0x40
	private readonly Int64 m_Interval; // 0x48
	private Boolean <active>k__BackingField; // 0x50
	private Vector2 <lastMousePosition>k__BackingField; // 0x54
	private Int32 m_ActivePointerId; // 0x5c
	private Boolean m_AcceptClicksIfDisabled; // 0x60
	private IVisualElementScheduledItem m_Repeater; // 0x68

	protected Boolean active { get; set; }
	public Vector2 lastMousePosition { get; set; }
	internal Boolean acceptClicksIfDisabled { get; }
	private InvokePolicy invokePolicy { get; }

	// RVA: 0x692ea38 VA: 0x7598f46a38
	public Void add_clicked(Action value) { }
	// RVA: 0x692ead4 VA: 0x7598f46ad4
	public Void remove_clicked(Action value) { }
	// RVA: 0x692eb70 VA: 0x7598f46b70
	protected Boolean get_active() { }
	// RVA: 0x692eb78 VA: 0x7598f46b78
	protected Void set_active(Boolean value) { }
	// RVA: 0x692eb84 VA: 0x7598f46b84
	public Vector2 get_lastMousePosition() { }
	// RVA: 0x692eb8c VA: 0x7598f46b8c
	private Void set_lastMousePosition(Vector2 value) { }
	// RVA: 0x692eb94 VA: 0x7598f46b94
	internal Boolean get_acceptClicksIfDisabled() { }
	// RVA: 0x692eb9c VA: 0x7598f46b9c
	private InvokePolicy get_invokePolicy() { }
	// RVA: 0x692eba4 VA: 0x7598f46ba4
	public Void .ctor(Action handler, Int64 delay, Int64 interval) { }
	// RVA: 0x692eca8 VA: 0x7598f46ca8
	public Void .ctor(Action`1 handler) { }
	// RVA: 0x692ebd0 VA: 0x7598f46bd0
	public Void .ctor(Action handler) { }
	// RVA: 0x692ed80 VA: 0x7598f46d80
	private Void OnTimer(TimerState timerState) { }
	// RVA: 0x692ee1c VA: 0x7598f46e1c
	private Boolean IsRepeatable() { }
	// RVA: 0x692eefc VA: 0x7598f46efc
	protected override Void RegisterCallbacksOnTarget() { }
	// RVA: 0x692f38c VA: 0x7598f4738c
	protected override Void UnregisterCallbacksFromTarget() { }
	// RVA: 0x692f7f8 VA: 0x7598f477f8
	protected Void OnMouseDown(MouseDownEvent evt) { }
	// RVA: 0x692fa2c VA: 0x7598f47a2c
	protected Void OnMouseMove(MouseMoveEvent evt) { }
	// RVA: 0x692fa98 VA: 0x7598f47a98
	protected Void OnMouseUp(MouseUpEvent evt) { }
	// RVA: 0x692fc10 VA: 0x7598f47c10
	private Void OnMouseCaptureOut(MouseCaptureOutEvent evt) { }
	// RVA: 0x692fc94 VA: 0x7598f47c94
	private Void OnPointerDown(PointerDownEvent evt) { }
	// RVA: 0x6930060 VA: 0x7598f48060
	private Void OnPointerMove(PointerMoveEvent evt) { }
	// RVA: 0x6930168 VA: 0x7598f48168
	private Void OnPointerUp(PointerUpEvent evt) { }
	// RVA: 0x6930338 VA: 0x7598f48338
	private Void OnPointerCancel(PointerCancelEvent evt) { }
	// RVA: 0x6930424 VA: 0x7598f48424
	private Void OnPointerCaptureOut(PointerCaptureOutEvent evt) { }
	// RVA: 0x692ee40 VA: 0x7598f46e40
	private Boolean ContainsPointer(Int32 pointerId) { }
	// RVA: 0x69303c0 VA: 0x7598f483c0
	private static Boolean IsNotMouseEvent(Int32 pointerId) { }
	// RVA: 0x692ee9c VA: 0x7598f46e9c
	protected Void Invoke(EventBase evt) { }
	// RVA: 0x69304b8 VA: 0x7598f484b8
	internal Void SimulateSingleClick(EventBase evt, Int32 delayMs) { }
	// RVA: 0x693067c VA: 0x7598f4867c
	protected virtual Void ProcessDownEvent(EventBase evt, Vector2 localPosition, Int32 pointerId) { }
	// RVA: 0x6930ad0 VA: 0x7598f48ad0
	protected virtual Void ProcessMoveEvent(EventBase evt, Vector2 localPosition) { }
	// RVA: 0x6930b3c VA: 0x7598f48b3c
	protected virtual Void ProcessUpEvent(EventBase evt, Vector2 localPosition, Int32 pointerId) { }
	// RVA: 0x6930cfc VA: 0x7598f48cfc
	protected virtual Void ProcessCancelEvent(EventBase evt, Int32 pointerId) { }
	// RVA: 0x6930e50 VA: 0x7598f48e50
	private Void <SimulateSingleClick>b__43_0() { }
}
```