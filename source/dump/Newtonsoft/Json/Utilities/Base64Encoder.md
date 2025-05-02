# Base64Encoder

**Namespace:** `Newtonsoft.Json.Utilities`


## Fields

- `Int32 _leftOverBytesCount`


## Methods

- `Void Encode(Byte[], Int32, Int32)`

- `Void Flush()`

- `Void WriteChars(Char[], Int32, Int32)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Utilities
internal class Base64Encoder
{
	private readonly Char[] _charsLine; // 0x10
	private readonly TextWriter _writer; // 0x18
	private Byte[] _leftOverBytes; // 0x20
	private Int32 _leftOverBytesCount; // 0x28


	// RVA: 0x6152dc0 VA: 0x759876adc0
	public Void .ctor(TextWriter writer) { }
	// RVA: 0x6152eb4 VA: 0x759876aeb4
	public Void Encode(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6153238 VA: 0x759876b238
	public Void Flush() { }
	// RVA: 0x6153214 VA: 0x759876b214
	private Void WriteChars(Char[] chars, Int32 index, Int32 count) { }
}
```