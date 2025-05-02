# UnexceptionalStreamReader

**Namespace:** `System.IO`


## Methods

- `Boolean CheckEOL(Char)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
internal class UnexceptionalStreamReader : StreamReader
{
	private static Boolean[] newline; // 0x0
	private static Char newlineChar; // 0x8


	// RVA: 0x603c600 VA: 0x7598654600
	private static Void .cctor() { }
	// RVA: 0x603c6b0 VA: 0x75986546b0
	public Void .ctor(Stream stream, Encoding encoding) { }
	// RVA: 0x603c720 VA: 0x7598654720
	public override Int32 Peek() { }
	// RVA: 0x603c7a8 VA: 0x75986547a8
	public override Int32 Read() { }
	// RVA: 0x603c830 VA: 0x7598654830
	public override Int32 Read([In] [Out] Char[] dest_buffer, Int32 index, Int32 count) { }
	// RVA: 0x603cac8 VA: 0x7598654ac8
	private Boolean CheckEOL(Char current) { }
	// RVA: 0x603cc60 VA: 0x7598654c60
	public override String ReadLine() { }
	// RVA: 0x603cce8 VA: 0x7598654ce8
	public override String ReadToEnd() { }
}
```