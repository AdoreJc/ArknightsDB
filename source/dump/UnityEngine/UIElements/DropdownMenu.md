# DropdownMenu

**Namespace:** `UnityEngine.UIElements`


## Fields

- `DropdownMenuEventInfo m_DropdownMenuEventInfo`


## Methods

- `Void AppendAction(String, Action`1, Func`2, Object)`

- `Void InsertSeparator(String, Int32)`

- `Void PrepareForDisplay(EventBase)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class DropdownMenu
{
	private List`1 m_MenuItems; // 0x10
	private DropdownMenuEventInfo m_DropdownMenuEventInfo; // 0x18


	// RVA: 0x69348c4 VA: 0x7598f4c8c4
	public List`1 MenuItems() { }
	// RVA: 0x69348cc VA: 0x7598f4c8cc
	public Void AppendAction(String actionName, Action`1 action, Func`2 actionStatusCallback, Object userData) { }
	// RVA: 0x69349d8 VA: 0x7598f4c9d8
	public Void InsertSeparator(String subMenuPath, Int32 atIndex) { }
	// RVA: 0x6934b24 VA: 0x7598f4cb24
	public Void PrepareForDisplay(EventBase e) { }
}
```