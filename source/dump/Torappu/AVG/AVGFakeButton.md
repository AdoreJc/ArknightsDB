# AVGFakeButton

**Namespace:** `Torappu.AVG`


## Fields

- `Action onClickCB`

- `UILongPressButton m_longPressBtnOnTarget`

- `Button m_target`

- `UILongPressButtonEx m_longPressButtonExTarget`


## Properties

- `Button target`

- `UILongPressButtonEx longPressButtonExTarget`


## Methods

- `Button get_target()`

- `UILongPressButtonEx get_longPressButtonExTarget()`

- `Void SetTarget(Button, UILongPressButtonEx)`

- `Void OnPointerDown(PointerEventData)`

- `Void OnPointerUp(PointerEventData)`

- `Void OnPointerEnter(PointerEventData)`

- `Void OnPointerExit(PointerEventData)`

- `Void OnClick()`

- `Void _RemoveAudioClickPlayerIfExist()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGFakeButton : MonoBehaviour, IPointerEnterHandler, IEventSystemHandler, IPointerDownHandler, IPointerUpHandler, IPointerExitHandler
{
	public Action onClickCB; // 0x18
	private UILongPressButton m_longPressBtnOnTarget; // 0x20
	private Button m_target; // 0x28
	private UILongPressButtonEx m_longPressButtonExTarget; // 0x30

	public Button target { get; }
	public UILongPressButtonEx longPressButtonExTarget { get; }

	// RVA: 0x3ea74d0 VA: 0x75964bf4d0
	public Button get_target() { }
	// RVA: 0x3ea74d8 VA: 0x75964bf4d8
	public UILongPressButtonEx get_longPressButtonExTarget() { }
	// RVA: 0x3ea74e0 VA: 0x75964bf4e0
	public Void SetTarget(Button target, UILongPressButtonEx longPressButtonExTarget) { }
	// RVA: 0x3ea7804 VA: 0x75964bf804
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x3ea78a4 VA: 0x75964bf8a4
	public Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x3ea7944 VA: 0x75964bf944
	public Void OnPointerEnter(PointerEventData eventData) { }
	// RVA: 0x3ea79e4 VA: 0x75964bf9e4
	public Void OnPointerExit(PointerEventData eventData) { }
	// RVA: 0x3ea7a84 VA: 0x75964bfa84
	public Void OnClick() { }
	// RVA: 0x3ea7744 VA: 0x75964bf744
	private Void _RemoveAudioClickPlayerIfExist() { }
	// RVA: 0x3ea7bc4 VA: 0x75964bfbc4
	public Void .ctor() { }
}
```