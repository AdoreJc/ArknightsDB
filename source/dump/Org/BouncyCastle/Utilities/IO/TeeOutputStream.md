# TeeOutputStream

**Namespace:** `Org.BouncyCastle.Utilities.IO`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.IO
public class TeeOutputStream : BaseOutputStream
{
	private readonly Stream output; // 0x30
	private readonly Stream tee; // 0x38


	// RVA: 0x66f76ac VA: 0x7598d0f6ac
	public Void .ctor(Stream output, Stream tee) { }
	// RVA: 0x66f76ec VA: 0x7598d0f6ec
	public override Void Close() { }
	// RVA: 0x66f7768 VA: 0x7598d0f768
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x66f77d0 VA: 0x7598d0f7d0
	public override Void WriteByte(Byte b) { }
}
```