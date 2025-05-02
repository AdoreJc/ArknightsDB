# ContextualMenuPopulateEvent

**Namespace:** `UnityEngine.UIElements`


## Fields

- `DropdownMenu <menu>k__BackingField`

- `EventBase <triggerEvent>k__BackingField`

- `ContextualMenuManager m_ContextualMenuManager`


## Properties

- `DropdownMenu menu`

- `EventBase triggerEvent`


## Methods

- `DropdownMenu get_menu()`

- `Void set_menu(DropdownMenu)`

- `EventBase get_triggerEvent()`

- `Void set_triggerEvent(EventBase)`

- `Void LocalInit()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class ContextualMenuPopulateEvent : MouseEventBase`1
{
	private DropdownMenu <menu>k__BackingField; // 0xb0
	private EventBase <triggerEvent>k__BackingField; // 0xb8
	private ContextualMenuManager m_ContextualMenuManager; // 0xc0

	public DropdownMenu menu { get; set; }
	public EventBase triggerEvent { get; set; }

	// RVA: 0x69e4fc4 VA: 0x7598ffcfc4
	public DropdownMenu get_menu() { }
	// RVA: 0x69e4fcc VA: 0x7598ffcfcc
	private Void set_menu(DropdownMenu value) { }
	// RVA: 0x69e4fd4 VA: 0x7598ffcfd4
	public EventBase get_triggerEvent() { }
	// RVA: 0x69e4fdc VA: 0x7598ffcfdc
	private Void set_triggerEvent(EventBase value) { }
	// RVA: 0x69e4fe4 VA: 0x7598ffcfe4
	protected override Void Init() { }
	// RVA: 0x69e5034 VA: 0x7598ffd034
	private Void LocalInit() { }
	// RVA: 0x69e508c VA: 0x7598ffd08c
	public Void .ctor() { }
	// RVA: 0x69e50dc VA: 0x7598ffd0dc
	protected internal override Void PostDispatch(IPanel panel) { }
}
```