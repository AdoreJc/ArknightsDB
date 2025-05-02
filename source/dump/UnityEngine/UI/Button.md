# Button

**Namespace:** `UnityEngine.UI`


## Fields

- `ButtonClickedEvent m_OnClick`


## Properties

- `ButtonClickedEvent onClick`


## Methods

- `ButtonClickedEvent get_onClick()`

- `Void set_onClick(ButtonClickedEvent)`

- `Void Press()`

- `IEnumerator OnFinishSubmit()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class Button : Selectable, IPointerClickHandler, IEventSystemHandler, ISubmitHandler
{
	private ButtonClickedEvent m_OnClick; // 0xf8

	public ButtonClickedEvent onClick { get; set; }

	// RVA: 0x6912b1c VA: 0x7598f2ab1c
	protected Void .ctor() { }
	// RVA: 0x6912bbc VA: 0x7598f2abbc
	public ButtonClickedEvent get_onClick() { }
	// RVA: 0x6912bc4 VA: 0x7598f2abc4
	public Void set_onClick(ButtonClickedEvent value) { }
	// RVA: 0x6912bcc VA: 0x7598f2abcc
	private Void Press() { }
	// RVA: 0x6912c64 VA: 0x7598f2ac64
	public virtual Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x6912c88 VA: 0x7598f2ac88
	public virtual Void OnSubmit(BaseEventData eventData) { }
	// RVA: 0x6912d00 VA: 0x7598f2ad00
	private IEnumerator OnFinishSubmit() { }
}
```