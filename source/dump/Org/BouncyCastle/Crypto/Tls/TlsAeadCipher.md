# TlsAeadCipher

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsAeadCipher : TlsCipher
{
	public const Int32 NONCE_RFC5288; // 0x0
	internal const Int32 NONCE_DRAFT_CHACHA20_POLY1305; // 0x0
	protected readonly TlsContext context; // 0x10
	protected readonly Int32 macSize; // 0x18
	protected readonly Int32 record_iv_length; // 0x1c
	protected readonly IAeadBlockCipher encryptCipher; // 0x20
	protected readonly IAeadBlockCipher decryptCipher; // 0x28
	protected readonly Byte[] encryptImplicitNonce; // 0x30
	protected readonly Byte[] decryptImplicitNonce; // 0x38
	protected readonly Int32 nonceMode; // 0x40


	// RVA: 0x64e0f3c VA: 0x7598af8f3c
	public Void .ctor(TlsContext context, IAeadBlockCipher clientWriteCipher, IAeadBlockCipher serverWriteCipher, Int32 cipherKeySize, Int32 macSize) { }
	// RVA: 0x64e10cc VA: 0x7598af90cc
	internal Void .ctor(TlsContext context, IAeadBlockCipher clientWriteCipher, IAeadBlockCipher serverWriteCipher, Int32 cipherKeySize, Int32 macSize, Int32 nonceMode) { }
	// RVA: 0x64ea2f4 VA: 0x7598b022f4
	public virtual Int32 GetPlaintextLimit(Int32 ciphertextLimit) { }
	// RVA: 0x64ea304 VA: 0x7598b02304
	public virtual Byte[] EncodePlaintext(Int64 seqNo, Byte type, Byte[] plaintext, Int32 offset, Int32 len) { }
	// RVA: 0x64ea87c VA: 0x7598b0287c
	public virtual Byte[] DecodeCiphertext(Int64 seqNo, Byte type, Byte[] ciphertext, Int32 offset, Int32 len) { }
	// RVA: 0x64eadc0 VA: 0x7598b02dc0
	protected virtual Byte[] GetAdditionalData(Int64 seqNo, Byte type, Int32 len) { }
}
```