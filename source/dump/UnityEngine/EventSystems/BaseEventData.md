# BaseEventData

**Namespace:** `UnityEngine.EventSystems`


## Properties

- `BaseInputModule currentInputModule`

- `GameObject selectedObject`


## Methods

- `BaseInputModule get_currentInputModule()`

- `GameObject get_selectedObject()`

- `Void set_selectedObject(GameObject)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.EventSystems
public class BaseEventData : AbstractEventData
{
	private readonly EventSystem m_EventSystem; // 0x18

	public BaseInputModule currentInputModule { get; }
	public GameObject selectedObject { get; set; }

	// RVA: 0x6a755ec VA: 0x759908d5ec
	public Void .ctor(EventSystem eventSystem) { }
	// RVA: 0x6a75640 VA: 0x759908d640
	public BaseInputModule get_currentInputModule() { }
	// RVA: 0x6a7565c VA: 0x759908d65c
	public GameObject get_selectedObject() { }
	// RVA: 0x6a75678 VA: 0x759908d678
	public Void set_selectedObject(GameObject value) { }
}
```