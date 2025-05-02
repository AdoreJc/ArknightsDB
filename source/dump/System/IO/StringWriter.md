# StringWriter

**Namespace:** `System.IO`


## Fields

- `StringBuilder _sb`

- `Boolean _isOpen`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class StringWriter : TextWriter
{
	private static UnicodeEncoding m_encoding; // 0x0
	private StringBuilder _sb; // 0x30
	private Boolean _isOpen; // 0x38

	public override Encoding Encoding { get; }

	// RVA: 0x6033600 VA: 0x759864b600
	public Void .ctor() { }
	// RVA: 0x6033788 VA: 0x759864b788
	public Void .ctor(IFormatProvider formatProvider) { }
	// RVA: 0x60337fc VA: 0x759864b7fc
	public Void .ctor(StringBuilder sb) { }
	// RVA: 0x6033694 VA: 0x759864b694
	public Void .ctor(StringBuilder sb, IFormatProvider formatProvider) { }
	// RVA: 0x603386c VA: 0x759864b86c
	public override Void Close() { }
	// RVA: 0x603387c VA: 0x759864b87c
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x603388c VA: 0x759864b88c
	public override Encoding get_Encoding() { }
	// RVA: 0x6033948 VA: 0x759864b948
	public override Void Write(Char value) { }
	// RVA: 0x6033988 VA: 0x759864b988
	public override Void Write(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6033b38 VA: 0x759864bb38
	public override Void Write(String value) { }
	// RVA: 0x6033b8c VA: 0x759864bb8c
	public override String ToString() { }
}
```