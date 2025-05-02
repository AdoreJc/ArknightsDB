# AsyncStreamReader

**Namespace:** `System.Diagnostics`


## Fields

- `Stream stream`

- `Encoding encoding`

- `Decoder decoder`

- `Boolean cancelOperation`

- `ManualResetEvent eofEvent`

- `Object syncObject`

- `IAsyncResult asyncReadResult`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Diagnostics
internal class AsyncStreamReader
{
	private Stream stream; // 0x10
	private Encoding encoding; // 0x18
	private Decoder decoder; // 0x20
	private Byte[] byteBuffer; // 0x28
	private Char[] charBuffer; // 0x30
	private Boolean cancelOperation; // 0x38
	private ManualResetEvent eofEvent; // 0x40
	private Object syncObject; // 0x48
	private IAsyncResult asyncReadResult; // 0x50


	// RVA: 0x63984b4 VA: 0x75989b04b4
	public virtual Void Close() { }
	// RVA: 0x63984c4 VA: 0x75989b04c4
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x6398888 VA: 0x75989b0888
	internal Void CancelOperation() { }
}
```