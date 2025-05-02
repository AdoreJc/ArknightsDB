# MissingMemberException

**Namespace:** `System`


## Fields

- `String ClassName`

- `String MemberName`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class MissingMemberException : MemberAccessException
{
	protected String ClassName; // 0x90
	protected String MemberName; // 0x98
	protected Byte[] Signature; // 0xa0

	public override String Message { get; }

	// RVA: 0x60d43a8 VA: 0x75986ec3a8
	public Void .ctor() { }
	// RVA: 0x60d4320 VA: 0x75986ec320
	public Void .ctor(String message) { }
	// RVA: 0x60d4408 VA: 0x75986ec408
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60d47e8 VA: 0x75986ec7e8
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60d46bc VA: 0x75986ec6bc
	public override String get_Message() { }
	// RVA: 0x60d4944 VA: 0x75986ec944
	internal static String FormatSignature(Byte[] signature) { }
}
```