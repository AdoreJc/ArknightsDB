# TlsStreamCipher

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsStreamCipher : TlsCipher
{
	protected readonly TlsContext context; // 0x10
	protected readonly IStreamCipher encryptCipher; // 0x18
	protected readonly IStreamCipher decryptCipher; // 0x20
	protected readonly TlsMac writeMac; // 0x28
	protected readonly TlsMac readMac; // 0x30
	protected readonly Boolean usesNonce; // 0x38


	// RVA: 0x64fff08 VA: 0x7598b17f08
	public Void .ctor(TlsContext context, IStreamCipher clientWriteCipher, IStreamCipher serverWriteCipher, IDigest clientWriteDigest, IDigest serverWriteDigest, Int32 cipherKeySize, Boolean usesNonce) { }
	// RVA: 0x65007a0 VA: 0x7598b187a0
	public virtual Int32 GetPlaintextLimit(Int32 ciphertextLimit) { }
	// RVA: 0x65007cc VA: 0x7598b187cc
	public virtual Byte[] EncodePlaintext(Int64 seqNo, Byte type, Byte[] plaintext, Int32 offset, Int32 len) { }
	// RVA: 0x65009c4 VA: 0x7598b189c4
	public virtual Byte[] DecodeCiphertext(Int64 seqNo, Byte type, Byte[] ciphertext, Int32 offset, Int32 len) { }
	// RVA: 0x6500ba4 VA: 0x7598b18ba4
	protected virtual Void CheckMac(Int64 seqNo, Byte type, Byte[] recBuf, Int32 recStart, Int32 recEnd, Byte[] calcBuf, Int32 calcOff, Int32 calcLen) { }
	// RVA: 0x6500c70 VA: 0x7598b18c70
	protected virtual Void UpdateIV(IStreamCipher cipher, Boolean forEncryption, Int64 seqNo) { }
}
```