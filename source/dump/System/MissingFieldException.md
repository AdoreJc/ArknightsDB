# MissingFieldException

**Namespace:** `System`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class MissingFieldException : MissingMemberException, ISerializable
{

	public override String Message { get; }

	// RVA: 0x60d42c4 VA: 0x75986ec2c4
	public Void .ctor() { }
	// RVA: 0x60d4344 VA: 0x75986ec344
	public Void .ctor(String message) { }
	// RVA: 0x60d4368 VA: 0x75986ec368
	public Void .ctor(String className, String fieldName) { }
	// RVA: 0x60d4404 VA: 0x75986ec404
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60d45a8 VA: 0x75986ec5a8
	public override String get_Message() { }
}
```