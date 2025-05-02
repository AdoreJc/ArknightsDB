# CStreamReader

**Namespace:** `System.IO`


## Fields

- `TermInfoDriver driver`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
internal class CStreamReader : StreamReader
{
	private TermInfoDriver driver; // 0x60


	// RVA: 0x603d07c VA: 0x759865507c
	public Void .ctor(Stream stream, Encoding encoding) { }
	// RVA: 0x603d19c VA: 0x759865519c
	public override Int32 Peek() { }
	// RVA: 0x603d224 VA: 0x7598655224
	public override Int32 Read() { }
	// RVA: 0x603d2f4 VA: 0x75986552f4
	public override Int32 Read([In] [Out] Char[] dest, Int32 index, Int32 count) { }
	// RVA: 0x603d4a4 VA: 0x75986554a4
	public override String ReadLine() { }
	// RVA: 0x603d53c VA: 0x759865553c
	public override String ReadToEnd() { }
}
```