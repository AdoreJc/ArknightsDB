# DropdownMenuAction

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Status <status>k__BackingField`

- `DropdownMenuEventInfo <eventInfo>k__BackingField`

- `Object <userData>k__BackingField`


## Properties

- `Status status`

- `DropdownMenuEventInfo eventInfo`

- `Object userData`


## Methods

- `Void set_status(Status)`

- `Void set_eventInfo(DropdownMenuEventInfo)`

- `Void set_userData(Object)`

- `Void UpdateActionStatus(DropdownMenuEventInfo)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class DropdownMenuAction : DropdownMenuItem
{
	private readonly String <name>k__BackingField; // 0x10
	private Status <status>k__BackingField; // 0x18
	private DropdownMenuEventInfo <eventInfo>k__BackingField; // 0x20
	private Object <userData>k__BackingField; // 0x28
	private readonly Action`1 actionCallback; // 0x30
	private readonly Func`2 actionStatusCallback; // 0x38

	private Status status { set; }
	private DropdownMenuEventInfo eventInfo { set; }
	private Object userData { set; }

	// RVA: 0x69347e8 VA: 0x7598f4c7e8
	private Void set_status(Status value) { }
	// RVA: 0x69347f0 VA: 0x7598f4c7f0
	private Void set_eventInfo(DropdownMenuEventInfo value) { }
	// RVA: 0x69347f8 VA: 0x7598f4c7f8
	private Void set_userData(Object value) { }
	// RVA: 0x6934800 VA: 0x7598f4c800
	public Void .ctor(String actionName, Action`1 actionCallback, Func`2 actionStatusCallback, Object userData) { }
	// RVA: 0x6934874 VA: 0x7598f4c874
	public Void UpdateActionStatus(DropdownMenuEventInfo eventInfo) { }
}
```