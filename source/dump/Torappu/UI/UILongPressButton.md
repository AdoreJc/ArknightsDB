# UILongPressButton

**Namespace:** `Torappu.UI`


## Fields

- `Int32 _longPressThreshold`

- `Int32 _longPressInterval`

- `Boolean m_isPressing`

- `DateTime m_pressStartTime`

- `DateTime m_lastLongPressUpdateTime`

- `Boolean m_isInteractable`

- `State m_state`

- `Action <onClick>k__BackingField`


## Properties

- `Boolean interactable`

- `Action onClick`


## Methods

- `Boolean get_interactable()`

- `Void set_interactable(Boolean)`

- `Action get_onClick()`

- `Void set_onClick(Action)`

- `Void set_onLongPress(Func`1)`

- `Void OnPointerDown(PointerEventData)`

- `Void OnPointerExit(PointerEventData)`

- `Void OnPointerUp(PointerEventData)`

- `Void Update()`

- `Void _FinishPointDown()`

- `Void _UpdateLongPress()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UILongPressButton : MonoBehaviour, IPointerDownHandler, IEventSystemHandler, IPointerExitHandler, IPointerUpHandler
{
	private Int32 _longPressThreshold; // 0x18
	private Int32 _longPressInterval; // 0x1c
	private Boolean m_isPressing; // 0x20
	private DateTime m_pressStartTime; // 0x28
	private DateTime m_lastLongPressUpdateTime; // 0x30
	private Boolean m_isInteractable; // 0x38
	private State m_state; // 0x3c
	private Action <onClick>k__BackingField; // 0x40
	private Func`1 <onLongPress>k__BackingField; // 0x48

	public Boolean interactable { get; set; }
	public Action onClick { get; set; }
	public Func`1 onLongPress { get; set; }

	// RVA: 0x2219dc4 VA: 0x7594831dc4
	public Boolean get_interactable() { }
	// RVA: 0x2219dcc VA: 0x7594831dcc
	public Void set_interactable(Boolean value) { }
	// RVA: 0x2219e1c VA: 0x7594831e1c
	public Action get_onClick() { }
	// RVA: 0x2219e24 VA: 0x7594831e24
	public Void set_onClick(Action value) { }
	// RVA: 0x2219e2c VA: 0x7594831e2c
	public Func`1 get_onLongPress() { }
	// RVA: 0x2219e34 VA: 0x7594831e34
	public Void set_onLongPress(Func`1 value) { }
	// RVA: 0x2219e3c VA: 0x7594831e3c
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x2219eac VA: 0x7594831eac
	public Void OnPointerExit(PointerEventData eventData) { }
	// RVA: 0x2219ec0 VA: 0x7594831ec0
	public Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x2219f28 VA: 0x7594831f28
	private Void Update() { }
	// RVA: 0x2219dec VA: 0x7594831dec
	private Void _FinishPointDown() { }
	// RVA: 0x221a0bc VA: 0x75948320bc
	private Void _UpdateLongPress() { }
	// RVA: 0x221a148 VA: 0x7594832148
	public Void .ctor() { }
}
```