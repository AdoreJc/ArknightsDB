# BadImageFormatException

**Namespace:** `System`


## Fields

- `String _fileName`

- `String _fusionLog`


## Methods

- `Void SetMessageField()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class BadImageFormatException : SystemException
{
	private String _fileName; // 0x90
	private String _fusionLog; // 0x98

	public override String Message { get; }

	// RVA: 0x60237b0 VA: 0x759863b7b0
	public Void .ctor() { }
	// RVA: 0x602380c VA: 0x759863b80c
	public Void .ctor(String message) { }
	// RVA: 0x6023830 VA: 0x759863b830
	public Void .ctor(String message, Exception inner) { }
	// RVA: 0x6023854 VA: 0x759863b854
	public Void .ctor(String message, String fileName) { }
	// RVA: 0x6023890 VA: 0x759863b890
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6023954 VA: 0x759863b954
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6023a6c VA: 0x759863ba6c
	public override String get_Message() { }
	// RVA: 0x6023a84 VA: 0x759863ba84
	private Void SetMessageField() { }
	// RVA: 0x6023b18 VA: 0x759863bb18
	public override String ToString() { }
}
```