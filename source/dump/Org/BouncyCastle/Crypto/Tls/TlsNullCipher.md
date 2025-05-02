# TlsNullCipher

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsNullCipher : TlsCipher
{
	protected readonly TlsContext context; // 0x10
	protected readonly TlsMac writeMac; // 0x18
	protected readonly TlsMac readMac; // 0x20


	// RVA: 0x64e6660 VA: 0x7598afe660
	public Void .ctor(TlsContext context) { }
	// RVA: 0x64e17bc VA: 0x7598af97bc
	public Void .ctor(TlsContext context, IDigest clientWriteDigest, IDigest serverWriteDigest) { }
	// RVA: 0x64f8f6c VA: 0x7598b10f6c
	public virtual Int32 GetPlaintextLimit(Int32 ciphertextLimit) { }
	// RVA: 0x64f8f98 VA: 0x7598b10f98
	public virtual Byte[] EncodePlaintext(Int64 seqNo, Byte type, Byte[] plaintext, Int32 offset, Int32 len) { }
	// RVA: 0x64f90a4 VA: 0x7598b110a4
	public virtual Byte[] DecodeCiphertext(Int64 seqNo, Byte type, Byte[] ciphertext, Int32 offset, Int32 len) { }
}
```