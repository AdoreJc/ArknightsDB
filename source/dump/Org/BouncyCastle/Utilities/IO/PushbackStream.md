# PushbackStream

**Namespace:** `Org.BouncyCastle.Utilities.IO`


## Fields

- `Int32 buf`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.IO
public class PushbackStream : FilterStream
{
	private Int32 buf; // 0x30


	// RVA: 0x66f6f8c VA: 0x7598d0ef8c
	public Void .ctor(Stream s) { }
	// RVA: 0x66f6f98 VA: 0x7598d0ef98
	public override Int32 ReadByte() { }
	// RVA: 0x66f6fdc VA: 0x7598d0efdc
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x66f7048 VA: 0x7598d0f048
	public virtual Void Unread(Int32 b) { }
}
```