# ArgumentOutOfRangeException

**Namespace:** `System`


## Fields

- `Object _actualValue`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class ArgumentOutOfRangeException : ArgumentException
{
	private Object _actualValue; // 0x98

	public override String Message { get; }

	// RVA: 0x6022f38 VA: 0x759863af38
	public Void .ctor() { }
	// RVA: 0x6022f94 VA: 0x759863af94
	public Void .ctor(String paramName) { }
	// RVA: 0x601e7e0 VA: 0x75986367e0
	public Void .ctor(String paramName, String message) { }
	// RVA: 0x601fab0 VA: 0x7598637ab0
	public Void .ctor(String paramName, Object actualValue, String message) { }
	// RVA: 0x602300c VA: 0x759863b00c
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60230ec VA: 0x759863b0ec
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60231c4 VA: 0x759863b1c4
	public override String get_Message() { }
}
```