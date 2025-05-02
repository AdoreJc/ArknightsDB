# TlsBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsBlockCipher : TlsCipher
{
	protected readonly TlsContext context; // 0x10
	protected readonly Byte[] randomData; // 0x18
	protected readonly Boolean useExplicitIV; // 0x20
	protected readonly Boolean encryptThenMac; // 0x21
	protected readonly IBlockCipher encryptCipher; // 0x28
	protected readonly IBlockCipher decryptCipher; // 0x30
	protected readonly TlsMac mWriteMac; // 0x38
	protected readonly TlsMac mReadMac; // 0x40

	public virtual TlsMac WriteMac { get; }
	public virtual TlsMac ReadMac { get; }

	// RVA: 0x64eaf20 VA: 0x7598b02f20
	public virtual TlsMac get_WriteMac() { }
	// RVA: 0x64eaf28 VA: 0x7598b02f28
	public virtual TlsMac get_ReadMac() { }
	// RVA: 0x64e0150 VA: 0x7598af8150
	public Void .ctor(TlsContext context, IBlockCipher clientWriteCipher, IBlockCipher serverWriteCipher, IDigest clientWriteDigest, IDigest serverWriteDigest, Int32 cipherKeySize) { }
	// RVA: 0x64eb334 VA: 0x7598b03334
	public virtual Int32 GetPlaintextLimit(Int32 ciphertextLimit) { }
	// RVA: 0x64eb434 VA: 0x7598b03434
	public virtual Byte[] EncodePlaintext(Int64 seqNo, Byte type, Byte[] plaintext, Int32 offset, Int32 len) { }
	// RVA: 0x64eba00 VA: 0x7598b03a00
	public virtual Byte[] DecodeCiphertext(Int64 seqNo, Byte type, Byte[] ciphertext, Int32 offset, Int32 len) { }
	// RVA: 0x64ebe60 VA: 0x7598b03e60
	protected virtual Int32 CheckPaddingConstantTime(Byte[] buf, Int32 off, Int32 len, Int32 blockSize, Int32 macSize) { }
	// RVA: 0x64ebfcc VA: 0x7598b03fcc
	protected virtual Int32 ChooseExtraPadBlocks(SecureRandom r, Int32 max) { }
	// RVA: 0x64ec074 VA: 0x7598b04074
	protected virtual Int32 LowestBitSet(Int32 x) { }
}
```