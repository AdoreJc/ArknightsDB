# StringReader

**Namespace:** `System.IO`


## Fields

- `String _s`

- `Int32 _pos`

- `Int32 _length`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class StringReader : TextReader
{
	private String _s; // 0x18
	private Int32 _pos; // 0x20
	private Int32 _length; // 0x24


	// RVA: 0x6033104 VA: 0x759864b104
	public Void .ctor(String s) { }
	// RVA: 0x60331dc VA: 0x759864b1dc
	public override Void Close() { }
	// RVA: 0x60331ec VA: 0x759864b1ec
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6033224 VA: 0x759864b224
	public override Int32 Peek() { }
	// RVA: 0x6033270 VA: 0x759864b270
	public override Int32 Read() { }
	// RVA: 0x60332c4 VA: 0x759864b2c4
	public override Int32 Read([In] [Out] Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x60334a0 VA: 0x759864b4a0
	public override String ReadToEnd() { }
	// RVA: 0x60334e8 VA: 0x759864b4e8
	public override String ReadLine() { }
}
```