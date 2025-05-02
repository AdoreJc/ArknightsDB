# PanelEventHandler

**Namespace:** `UnityEngine.UIElements`


## Fields

- `BaseRuntimePanel m_Panel`

- `Boolean m_Selecting`

- `Event m_Event`


## Properties

- `IPanel panel`

- `GameObject selectableGameObject`

- `EventSystem eventSystem`


## Methods

- `IPanel get_panel()`

- `Void set_panel(IPanel)`

- `GameObject get_selectableGameObject()`

- `EventSystem get_eventSystem()`

- `Void RegisterCallbacks()`

- `Void UnregisterCallbacks()`

- `Void OnPanelDestroyed()`

- `Void OnElementFocus(FocusEvent)`

- `Void OnElementBlur(BlurEvent)`

- `Void OnSelect(BaseEventData)`

- `Void OnDeselect(BaseEventData)`

- `Void OnPointerMove(PointerEventData)`

- `Void OnPointerUp(PointerEventData)`

- `Void OnPointerDown(PointerEventData)`

- `Void OnPointerExit(PointerEventData)`

- `Void OnPointerEnter(PointerEventData)`

- `Void OnSubmit(BaseEventData)`

- `Void OnCancel(BaseEventData)`

- `Void OnMove(AxisEventData)`

- `Void OnScroll(PointerEventData)`

- `Void SendEvent(EventBase, BaseEventData)`

- `Void SendEvent(EventBase, Event)`

- `Void Update()`

- `Void LateUpdate()`

- `Void ProcessImguiEvents(Boolean)`

- `Void ProcessKeyboardEvent(Event)`

- `Void ProcessTabEvent(Event)`

- `Void SendTabEvent(Event, Int32)`

- `Void SendKeyUpEvent(Event)`

- `Void SendKeyDownEvent(Event)`

- `Boolean ReadPointerData(PointerEvent, PointerEventData, PointerEventType)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UIElements
public class PanelEventHandler : UIBehaviour, IPointerMoveHandler, IEventSystemHandler, IPointerUpHandler, IPointerDownHandler, ISubmitHandler, ICancelHandler, IMoveHandler, IScrollHandler, ISelectHandler, IDeselectHandler, IPointerExitHandler, IPointerEnterHandler, IRuntimePanelComponent
{
	private BaseRuntimePanel m_Panel; // 0x18
	private readonly PointerEvent m_PointerEvent; // 0x20
	private Boolean m_Selecting; // 0x28
	private Event m_Event; // 0x30
	private static EventModifiers s_Modifiers; // 0x0

	public IPanel panel { get; set; }
	private GameObject selectableGameObject { get; }
	private EventSystem eventSystem { get; }

	// RVA: 0x6a724e4 VA: 0x759908a4e4
	public IPanel get_panel() { }
	// RVA: 0x6a724ec VA: 0x759908a4ec
	public Void set_panel(IPanel value) { }
	// RVA: 0x6a72920 VA: 0x759908a920
	private GameObject get_selectableGameObject() { }
	// RVA: 0x6a72938 VA: 0x759908a938
	private EventSystem get_eventSystem() { }
	// RVA: 0x6a72a0c VA: 0x759908aa0c
	protected override Void OnEnable() { }
	// RVA: 0x6a72a14 VA: 0x759908aa14
	protected override Void OnDisable() { }
	// RVA: 0x6a72760 VA: 0x759908a760
	private Void RegisterCallbacks() { }
	// RVA: 0x6a725a0 VA: 0x759908a5a0
	private Void UnregisterCallbacks() { }
	// RVA: 0x6a72a1c VA: 0x759908aa1c
	private Void OnPanelDestroyed() { }
	// RVA: 0x6a72a24 VA: 0x759908aa24
	private Void OnElementFocus(FocusEvent e) { }
	// RVA: 0x6a72b0c VA: 0x759908ab0c
	private Void OnElementBlur(BlurEvent e) { }
	// RVA: 0x6a72b10 VA: 0x759908ab10
	public Void OnSelect(BaseEventData eventData) { }
	// RVA: 0x6a72b88 VA: 0x759908ab88
	public Void OnDeselect(BaseEventData eventData) { }
	// RVA: 0x6a72b9c VA: 0x759908ab9c
	public Void OnPointerMove(PointerEventData eventData) { }
	// RVA: 0x6a72eec VA: 0x759908aeec
	public Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x6a7310c VA: 0x759908b10c
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x6a73394 VA: 0x759908b394
	public Void OnPointerExit(PointerEventData eventData) { }
	// RVA: 0x6a73648 VA: 0x759908b648
	public Void OnPointerEnter(PointerEventData eventData) { }
	// RVA: 0x6a7369c VA: 0x759908b69c
	public Void OnSubmit(BaseEventData eventData) { }
	// RVA: 0x6a739a8 VA: 0x759908b9a8
	public Void OnCancel(BaseEventData eventData) { }
	// RVA: 0x6a73b6c VA: 0x759908bb6c
	public Void OnMove(AxisEventData eventData) { }
	// RVA: 0x6a73d04 VA: 0x759908bd04
	public Void OnScroll(PointerEventData eventData) { }
	// RVA: 0x6a72e88 VA: 0x759908ae88
	private Void SendEvent(EventBase e, BaseEventData sourceEventData) { }
	// RVA: 0x6a73ec4 VA: 0x759908bec4
	private Void SendEvent(EventBase e, Event sourceEvent) { }
	// RVA: 0x6a73f24 VA: 0x759908bf24
	private Void Update() { }
	// RVA: 0x6a74004 VA: 0x759908c004
	private Void LateUpdate() { }
	// RVA: 0x6a73860 VA: 0x759908b860
	private Void ProcessImguiEvents(Boolean isSelected) { }
	// RVA: 0x6a7400c VA: 0x759908c00c
	private Void ProcessKeyboardEvent(Event e) { }
	// RVA: 0x6a74080 VA: 0x759908c080
	private Void ProcessTabEvent(Event e) { }
	// RVA: 0x6a74490 VA: 0x759908c490
	private Void SendTabEvent(Event e, Int32 direction) { }
	// RVA: 0x6a74100 VA: 0x759908c100
	private Void SendKeyUpEvent(Event e) { }
	// RVA: 0x6a742bc VA: 0x759908c2bc
	private Void SendKeyDownEvent(Event e) { }
	// RVA: 0x6a72d4c VA: 0x759908ad4c
	private Boolean ReadPointerData(PointerEvent pe, PointerEventData eventData, PointerEventType eventType) { }
	// RVA: 0x6a74acc VA: 0x759908cacc
	public Void .ctor() { }
}
```