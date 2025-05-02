# TeeInputStream

**Namespace:** `Org.BouncyCastle.Utilities.IO`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.IO
public class TeeInputStream : BaseInputStream
{
	private readonly Stream input; // 0x30
	private readonly Stream tee; // 0x38


	// RVA: 0x66f751c VA: 0x7598d0f51c
	public Void .ctor(Stream input, Stream tee) { }
	// RVA: 0x66f755c VA: 0x7598d0f55c
	public override Void Close() { }
	// RVA: 0x66f75d8 VA: 0x7598d0f5d8
	public override Int32 Read(Byte[] buf, Int32 off, Int32 len) { }
	// RVA: 0x66f7650 VA: 0x7598d0f650
	public override Int32 ReadByte() { }
}
```