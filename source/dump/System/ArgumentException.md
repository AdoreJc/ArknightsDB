# ArgumentException

**Namespace:** `System`


## Fields

- `String _paramName`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class ArgumentException : SystemException
{
	private String _paramName; // 0x90

	public override String Message { get; }

	// RVA: 0x6022bc4 VA: 0x759863abc4
	public Void .ctor() { }
	// RVA: 0x6021990 VA: 0x7598639990
	public Void .ctor(String message) { }
	// RVA: 0x6022c20 VA: 0x759863ac20
	public Void .ctor(String message, Exception innerException) { }
	// RVA: 0x6022c44 VA: 0x759863ac44
	public Void .ctor(String message, String paramName, Exception innerException) { }
	// RVA: 0x601affc VA: 0x7598632ffc
	public Void .ctor(String message, String paramName) { }
	// RVA: 0x6022c88 VA: 0x759863ac88
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6022d18 VA: 0x759863ad18
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6022df4 VA: 0x759863adf4
	public override String get_Message() { }
}
```