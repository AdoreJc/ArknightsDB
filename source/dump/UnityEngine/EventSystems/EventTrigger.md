# EventTrigger

**Namespace:** `UnityEngine.EventSystems`


## Methods

- `Void set_delegates(List`1)`

- `Void set_triggers(List`1)`

- `Void Execute(EventTriggerType, BaseEventData)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.EventSystems
public class EventTrigger : MonoBehaviour, IPointerEnterHandler, IEventSystemHandler, IPointerExitHandler, IPointerDownHandler, IPointerUpHandler, IPointerClickHandler, IInitializePotentialDragHandler, IBeginDragHandler, IDragHandler, IEndDragHandler, IDropHandler, IScrollHandler, IUpdateSelectedHandler, ISelectHandler, IDeselectHandler, IMoveHandler, ISubmitHandler, ICancelHandler
{
	private List`1 m_Delegates; // 0x18

	public List`1 delegates { get; set; }
	public List`1 triggers { get; set; }

	// RVA: 0x6a78ca0 VA: 0x7599090ca0
	public List`1 get_delegates() { }
	// RVA: 0x6a78d30 VA: 0x7599090d30
	public Void set_delegates(List`1 value) { }
	// RVA: 0x6a78d38 VA: 0x7599090d38
	protected Void .ctor() { }
	// RVA: 0x6a78ca4 VA: 0x7599090ca4
	public List`1 get_triggers() { }
	// RVA: 0x6a78d40 VA: 0x7599090d40
	public Void set_triggers(List`1 value) { }
	// RVA: 0x6a78d48 VA: 0x7599090d48
	private Void Execute(EventTriggerType id, BaseEventData eventData) { }
	// RVA: 0x6a78e34 VA: 0x7599090e34
	public virtual Void OnPointerEnter(PointerEventData eventData) { }
	// RVA: 0x6a78e40 VA: 0x7599090e40
	public virtual Void OnPointerExit(PointerEventData eventData) { }
	// RVA: 0x6a78e4c VA: 0x7599090e4c
	public virtual Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x6a78e58 VA: 0x7599090e58
	public virtual Void OnDrop(PointerEventData eventData) { }
	// RVA: 0x6a78e64 VA: 0x7599090e64
	public virtual Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x6a78e70 VA: 0x7599090e70
	public virtual Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x6a78e7c VA: 0x7599090e7c
	public virtual Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x6a78e88 VA: 0x7599090e88
	public virtual Void OnSelect(BaseEventData eventData) { }
	// RVA: 0x6a78e94 VA: 0x7599090e94
	public virtual Void OnDeselect(BaseEventData eventData) { }
	// RVA: 0x6a78ea0 VA: 0x7599090ea0
	public virtual Void OnScroll(PointerEventData eventData) { }
	// RVA: 0x6a78eac VA: 0x7599090eac
	public virtual Void OnMove(AxisEventData eventData) { }
	// RVA: 0x6a78eb8 VA: 0x7599090eb8
	public virtual Void OnUpdateSelected(BaseEventData eventData) { }
	// RVA: 0x6a78ec4 VA: 0x7599090ec4
	public virtual Void OnInitializePotentialDrag(PointerEventData eventData) { }
	// RVA: 0x6a78ed0 VA: 0x7599090ed0
	public virtual Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x6a78edc VA: 0x7599090edc
	public virtual Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x6a78ee8 VA: 0x7599090ee8
	public virtual Void OnSubmit(BaseEventData eventData) { }
	// RVA: 0x6a78ef4 VA: 0x7599090ef4
	public virtual Void OnCancel(BaseEventData eventData) { }
}
```