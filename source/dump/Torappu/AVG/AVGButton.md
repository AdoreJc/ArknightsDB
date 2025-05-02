# AVGButton

**Namespace:** `Torappu.AVG`


## Fields

- `Int32 _longPressThreshold`

- `Int32 _dragDiatance`

- `Action onClickAction`

- `DragContext m_context`

- `State m_state`

- `DateTime m_pressStartTime`


## Methods

- `Void _OnPointerExit()`

- `Void Update()`

- `Void OnPointerDown(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGButton : MonoBehaviour, IHotfixable, IPointerDownHandler, IEventSystemHandler
{
	private Int32 _longPressThreshold; // 0x18
	private Int32 _dragDiatance; // 0x1c
	public Action onClickAction; // 0x20
	public Action`1 onLongPressAction; // 0x28
	public Action`1 onDragAction; // 0x30
	private DragContext m_context; // 0x38
	private State m_state; // 0x48
	private DateTime m_pressStartTime; // 0x50
	private static DelegateBridge __Hotfix0__OnPointerExit; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_OnPointerDown; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3e632c8 VA: 0x759647b2c8
	private Void _OnPointerExit() { }
	// RVA: 0x3e6337c VA: 0x759647b37c
	private Void Update() { }
	// RVA: 0x3e63784 VA: 0x759647b784
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x3e63870 VA: 0x759647b870
	public Void .ctor() { }
}
```