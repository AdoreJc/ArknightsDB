# ErrorContext

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `Boolean <Traced>k__BackingField`

- `Exception <Error>k__BackingField`

- `Object <OriginalObject>k__BackingField`

- `Object <Member>k__BackingField`

- `String <Path>k__BackingField`

- `Boolean <Handled>k__BackingField`


## Properties

- `Exception Error`

- `Object OriginalObject`

- `Object Member`

- `String Path`

- `Boolean Handled`


## Methods

- `Exception get_Error()`

- `Void set_Error(Exception)`

- `Void set_OriginalObject(Object)`

- `Void set_Member(Object)`

- `Void set_Path(String)`

- `Boolean get_Handled()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class ErrorContext
{
	private Boolean <Traced>k__BackingField; // 0x10
	private Exception <Error>k__BackingField; // 0x18
	private Object <OriginalObject>k__BackingField; // 0x20
	private Object <Member>k__BackingField; // 0x28
	private String <Path>k__BackingField; // 0x30
	private Boolean <Handled>k__BackingField; // 0x38

	internal Boolean Traced { get; set; }
	public Exception Error { get; set; }
	private Object OriginalObject { set; }
	private Object Member { set; }
	private String Path { set; }
	public Boolean Handled { get; }

	// RVA: 0x616f5a0 VA: 0x75987875a0
	internal Void .ctor(Object originalObject, Object member, String path, Exception error) { }
	// RVA: 0x616f614 VA: 0x7598787614
	internal Boolean get_Traced() { }
	// RVA: 0x616f61c VA: 0x759878761c
	internal Void set_Traced(Boolean value) { }
	// RVA: 0x616f628 VA: 0x7598787628
	public Exception get_Error() { }
	// RVA: 0x616f630 VA: 0x7598787630
	private Void set_Error(Exception value) { }
	// RVA: 0x616f638 VA: 0x7598787638
	private Void set_OriginalObject(Object value) { }
	// RVA: 0x616f640 VA: 0x7598787640
	private Void set_Member(Object value) { }
	// RVA: 0x616f648 VA: 0x7598787648
	private Void set_Path(String value) { }
	// RVA: 0x616f650 VA: 0x7598787650
	public Boolean get_Handled() { }
}
```