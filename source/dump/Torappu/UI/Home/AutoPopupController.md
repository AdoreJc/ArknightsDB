# AutoPopupController

**Namespace:** `Torappu.UI.Home`


## Fields

- `Boolean m_isTriggering`


## Properties

- `Boolean isActive`


## Methods

- `Void Clear()`

- `Void Reset(Func`2)`

- `Void AddEvent(AutoPopupType, Object)`

- `Void InitialTrigger()`

- `Boolean get_isActive()`

- `Void OnStateResume()`

- `Void _TriggerResume()`

- `Void _TryTriggerNextPopup(HomePage)`

- `IEnumerator _TriggerPopupCoroutine(HomePage, Queue`1)`

- `Void _TriggerPopupWithItems(Queue`1)`

- `Boolean _TriggerPopup(AutoPopupItem)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class AutoPopupController
{
	private Func`2 m_popupHandler; // 0x10
	private Boolean m_isTriggering; // 0x18
	private Queue`1 m_items; // 0x20

	public Boolean isActive { get; }

	// RVA: 0x2806bdc VA: 0x7594e1ebdc
	public Void Clear() { }
	// RVA: 0x2806c40 VA: 0x7594e1ec40
	public Void Reset(Func`2 popupHandler) { }
	// RVA: 0x2806ca8 VA: 0x7594e1eca8
	public Void AddEvent(AutoPopupType type, Object param) { }
	// RVA: 0x2806d3c VA: 0x7594e1ed3c
	public Void InitialTrigger() { }
	// RVA: 0x2806e3c VA: 0x7594e1ee3c
	public Boolean get_isActive() { }
	// RVA: 0x2806e8c VA: 0x7594e1ee8c
	public Void OnStateResume() { }
	// RVA: 0x2806d40 VA: 0x7594e1ed40
	private Void _TriggerResume() { }
	// RVA: 0x2806e90 VA: 0x7594e1ee90
	private Void _TryTriggerNextPopup(HomePage homePage) { }
	// RVA: 0x2806f0c VA: 0x7594e1ef0c
	private IEnumerator _TriggerPopupCoroutine(HomePage homePage, Queue`1 items) { }
	// RVA: 0x2806fb0 VA: 0x7594e1efb0
	private Void _TriggerPopupWithItems(Queue`1 items) { }
	// RVA: 0x2807074 VA: 0x7594e1f074
	private Boolean _TriggerPopup(AutoPopupItem popup) { }
	// RVA: 0x2807094 VA: 0x7594e1f094
	public Void .ctor() { }
}
```