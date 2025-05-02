# FileNotFoundException

**Namespace:** `System.IO`


## Properties

- `String FileName`

- `String FusionLog`


## Methods

- `Void SetMessageField()`

- `String get_FileName()`

- `String get_FusionLog()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class FileNotFoundException : IOException
{
	private readonly String <FileName>k__BackingField; // 0x90
	private readonly String <FusionLog>k__BackingField; // 0x98

	public override String Message { get; }
	public String FileName { get; }
	public String FusionLog { get; }

	// RVA: 0x5ffc2cc VA: 0x75986142cc
	public Void .ctor() { }
	// RVA: 0x5ffc328 VA: 0x7598614328
	public Void .ctor(String message) { }
	// RVA: 0x5ffc34c VA: 0x759861434c
	public Void .ctor(String message, String fileName) { }
	// RVA: 0x5ffc388 VA: 0x7598614388
	public override String get_Message() { }
	// RVA: 0x5ffc3a0 VA: 0x75986143a0
	private Void SetMessageField() { }
	// RVA: 0x5ffc430 VA: 0x7598614430
	public String get_FileName() { }
	// RVA: 0x5ffc438 VA: 0x7598614438
	public String get_FusionLog() { }
	// RVA: 0x5ffc440 VA: 0x7598614440
	public override String ToString() { }
	// RVA: 0x5ffc624 VA: 0x7598614624
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ffc6e8 VA: 0x75986146e8
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
}
```