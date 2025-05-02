# CStreamWriter

**Namespace:** `System.IO`


## Fields

- `TermInfoDriver driver`


## Methods

- `Void InternalWriteString(String)`

- `Void InternalWriteChar(Char)`

- `Void InternalWriteChars(Char[], Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
internal class CStreamWriter : StreamWriter
{
	private TermInfoDriver driver; // 0x70


	// RVA: 0x603d5d4 VA: 0x75986555d4
	public Void .ctor(Stream stream, Encoding encoding, Boolean leaveOpen) { }
	// RVA: 0x603d708 VA: 0x7598655708
	public override Void Write(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x603da50 VA: 0x7598655a50
	public override Void Write(Char val) { }
	// RVA: 0x603dc60 VA: 0x7598655c60
	public Void InternalWriteString(String val) { }
	// RVA: 0x603dbdc VA: 0x7598655bdc
	public Void InternalWriteChar(Char val) { }
	// RVA: 0x603dce4 VA: 0x7598655ce4
	public Void InternalWriteChars(Char[] buffer, Int32 n) { }
	// RVA: 0x603dd70 VA: 0x7598655d70
	public override Void Write(Char[] val) { }
	// RVA: 0x603dd98 VA: 0x7598655d98
	public override Void Write(String val) { }
	// RVA: 0x603de64 VA: 0x7598655e64
	public override Void WriteLine(String val) { }
}
```