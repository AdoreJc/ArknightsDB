# FileLoadException

**Namespace:** `System.IO`


## Properties

- `String FileName`

- `String FusionLog`


## Methods

- `String get_FileName()`

- `String get_FusionLog()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class FileLoadException : IOException
{
	private readonly String <FileName>k__BackingField; // 0x90
	private readonly String <FusionLog>k__BackingField; // 0x98

	public override String Message { get; }
	public String FileName { get; }
	public String FusionLog { get; }

	// RVA: 0x5ffbdc8 VA: 0x7598613dc8
	public Void .ctor() { }
	// RVA: 0x5ffbe24 VA: 0x7598613e24
	public Void .ctor(String message) { }
	// RVA: 0x5ffbe48 VA: 0x7598613e48
	public override String get_Message() { }
	// RVA: 0x5ffbefc VA: 0x7598613efc
	public String get_FileName() { }
	// RVA: 0x5ffbf04 VA: 0x7598613f04
	public String get_FusionLog() { }
	// RVA: 0x5ffbf0c VA: 0x7598613f0c
	public override String ToString() { }
	// RVA: 0x5ffc0f0 VA: 0x75986140f0
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ffc1b4 VA: 0x75986141b4
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ffbe88 VA: 0x7598613e88
	internal static String FormatFileLoadExceptionMessage(String fileName, Int32 hResult) { }
}
```