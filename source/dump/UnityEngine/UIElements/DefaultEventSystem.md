# DefaultEventSystem

**Namespace:** `UnityEngine.UIElements`


## Fields

- `IInput m_Input`

- `Boolean m_SendingTouchEvents`

- `Event m_Event`

- `BaseRuntimePanel m_FocusedPanel`

- `Int32 m_ConsecutiveMoveCount`

- `Vector2 m_LastMoveVector`

- `Single m_PrevActionTime`


## Properties

- `Boolean isAppFocused`

- `BaseRuntimePanel focusedPanel`


## Methods

- `Boolean get_isAppFocused()`

- `IInput GetDefaultInput()`

- `Boolean ShouldIgnoreEventsOnAppNotFocused()`

- `BaseRuntimePanel get_focusedPanel()`

- `Void set_focusedPanel(BaseRuntimePanel)`

- `Void Update(UpdateMode)`

- `Void SendIMGUIEvents()`

- `Void SendInputEvents()`

- `Void SendPositionBasedEvent(Vector3, Vector3, Int32, Nullable`1, Func`4, TArg, Boolean)`

- `Void UpdateFocusedPanel(BaseRuntimePanel)`

- `Boolean ProcessTouchEvents()`

- `Vector2 GetRawMoveVector()`

- `Boolean ShouldSendMoveFromInput()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class DefaultEventSystem
{
	internal static Func`1 IsEditorRemoteConnected; // 0x0
	private IInput m_Input; // 0x10
	private readonly String m_HorizontalAxis; // 0x18
	private readonly String m_VerticalAxis; // 0x20
	private readonly String m_SubmitButton; // 0x28
	private readonly String m_CancelButton; // 0x30
	private readonly Single m_InputActionsPerSecond; // 0x38
	private readonly Single m_RepeatDelay; // 0x3c
	private Boolean m_SendingTouchEvents; // 0x40
	private Event m_Event; // 0x48
	private BaseRuntimePanel m_FocusedPanel; // 0x50
	private Int32 m_ConsecutiveMoveCount; // 0x58
	private Vector2 m_LastMoveVector; // 0x5c
	private Single m_PrevActionTime; // 0x64

	private Boolean isAppFocused { get; }
	internal IInput input { get; }
	public BaseRuntimePanel focusedPanel { get; set; }

	// RVA: 0x6932624 VA: 0x7598f4a624
	private Boolean get_isAppFocused() { }
	// RVA: 0x693262c VA: 0x7598f4a62c
	internal IInput get_input() { }
	// RVA: 0x693266c VA: 0x7598f4a66c
	private IInput GetDefaultInput() { }
	// RVA: 0x6932810 VA: 0x7598f4a810
	private Boolean ShouldIgnoreEventsOnAppNotFocused() { }
	// RVA: 0x6932830 VA: 0x7598f4a830
	public BaseRuntimePanel get_focusedPanel() { }
	// RVA: 0x6932838 VA: 0x7598f4a838
	public Void set_focusedPanel(BaseRuntimePanel value) { }
	// RVA: 0x6932904 VA: 0x7598f4a904
	public Void Update(UpdateMode updateMode) { }
	// RVA: 0x6932dbc VA: 0x7598f4adbc
	private Void SendIMGUIEvents() { }
	// RVA: 0x6933288 VA: 0x7598f4b288
	private Void SendInputEvents() { }
	// RVA: 0x VA: 0x0
	internal Void SendFocusBasedEvent(Func`2 evtFactory, TArg arg) { }
	// RVA: 0x VA: 0x0
	private Void SendPositionBasedEvent(Vector3 mousePosition, Vector3 delta, Int32 pointerId, Nullable`1 targetDisplay, Func`4 evtFactory, TArg arg, Boolean deselectIfNoTarget) { }
	// RVA: 0x69338a0 VA: 0x7598f4b8a0
	private Void UpdateFocusedPanel(BaseRuntimePanel runtimePanel) { }
	// RVA: 0x6933954 VA: 0x7598f4b954
	private static EventBase MakeTouchEvent(Touch touch, EventModifiers modifiers) { }
	// RVA: 0x6932970 VA: 0x7598f4a970
	private Boolean ProcessTouchEvents() { }
	// RVA: 0x6933ae4 VA: 0x7598f4bae4
	private Vector2 GetRawMoveVector() { }
	// RVA: 0x6933600 VA: 0x7598f4b600
	private Boolean ShouldSendMoveFromInput() { }
	// RVA: 0x69335e4 VA: 0x7598f4b5e4
	private static Vector2 GetLocalScreenPosition(Event evt, out Nullable`1 targetDisplay) { }
	// RVA: 0x6933d6c VA: 0x7598f4bd6c
	public Void .ctor() { }
	// RVA: 0x6933e90 VA: 0x7598f4be90
	private static Void .cctor() { }
}
```