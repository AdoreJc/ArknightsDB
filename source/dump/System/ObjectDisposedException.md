# ObjectDisposedException

**Namespace:** `System`


## Fields

- `String _objectName`


## Properties

- `String ObjectName`


## Methods

- `String get_ObjectName()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class ObjectDisposedException : InvalidOperationException
{
	private String _objectName; // 0x90

	public override String Message { get; }
	public String ObjectName { get; }

	// RVA: 0x60bfeec VA: 0x75986d7eec
	private Void .ctor() { }
	// RVA: 0x60bff94 VA: 0x75986d7f94
	public Void .ctor(String objectName) { }
	// RVA: 0x60bff54 VA: 0x75986d7f54
	public Void .ctor(String objectName, String message) { }
	// RVA: 0x60c0008 VA: 0x75986d8008
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60c0098 VA: 0x75986d8098
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60c0288 VA: 0x75986d8288
	public override String get_Message() { }
	// RVA: 0x60c01a0 VA: 0x75986d81a0
	public String get_ObjectName() { }
}
```