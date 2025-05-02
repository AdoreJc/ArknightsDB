# ErrorEventArgs

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `Object <CurrentObject>k__BackingField`

- `ErrorContext <ErrorContext>k__BackingField`


## Properties

- `Object CurrentObject`

- `ErrorContext ErrorContext`


## Methods

- `Void set_CurrentObject(Object)`

- `Void set_ErrorContext(ErrorContext)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class ErrorEventArgs : EventArgs
{
	private Object <CurrentObject>k__BackingField; // 0x10
	private ErrorContext <ErrorContext>k__BackingField; // 0x18

	private Object CurrentObject { set; }
	private ErrorContext ErrorContext { set; }

	// RVA: 0x6166be8 VA: 0x759877ebe8
	private Void set_CurrentObject(Object value) { }
	// RVA: 0x6166bf0 VA: 0x759877ebf0
	private Void set_ErrorContext(ErrorContext value) { }
	// RVA: 0x6166bf8 VA: 0x759877ebf8
	public Void .ctor(Object currentObject, ErrorContext errorContext) { }
}
```