# NullStreamReader

**Namespace:** ` `


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class NullStreamReader : StreamReader
{

	public override Stream BaseStream { get; }
	public override Encoding CurrentEncoding { get; }

	// RVA: 0x6002418 VA: 0x759861a418
	internal Void .ctor() { }
	// RVA: 0x60024b4 VA: 0x759861a4b4
	public override Stream get_BaseStream() { }
	// RVA: 0x600250c VA: 0x759861a50c
	public override Encoding get_CurrentEncoding() { }
	// RVA: 0x6002514 VA: 0x759861a514
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6002518 VA: 0x759861a518
	public override Int32 Peek() { }
	// RVA: 0x6002520 VA: 0x759861a520
	public override Int32 Read() { }
	// RVA: 0x6002528 VA: 0x759861a528
	public override Int32 Read(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6002530 VA: 0x759861a530
	public override String ReadLine() { }
	// RVA: 0x6002538 VA: 0x759861a538
	public override String ReadToEnd() { }
	// RVA: 0x6002580 VA: 0x759861a580
	internal override Int32 ReadBuffer() { }
}
```