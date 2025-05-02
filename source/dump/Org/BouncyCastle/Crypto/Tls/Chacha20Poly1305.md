# Chacha20Poly1305

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class Chacha20Poly1305 : TlsCipher
{
	private static readonly Byte[] Zeroes; // 0x0
	protected readonly TlsContext context; // 0x10
	protected readonly ChaCha7539Engine encryptCipher; // 0x18
	protected readonly ChaCha7539Engine decryptCipher; // 0x20
	protected readonly Byte[] encryptIV; // 0x28
	protected readonly Byte[] decryptIV; // 0x30


	// RVA: 0x64ddffc VA: 0x7598af5ffc
	public Void .ctor(TlsContext context) { }
	// RVA: 0x64de354 VA: 0x7598af6354
	public virtual Int32 GetPlaintextLimit(Int32 ciphertextLimit) { }
	// RVA: 0x64de35c VA: 0x7598af635c
	public virtual Byte[] EncodePlaintext(Int64 seqNo, Byte type, Byte[] plaintext, Int32 offset, Int32 len) { }
	// RVA: 0x64de498 VA: 0x7598af6498
	public virtual Byte[] DecodeCiphertext(Int64 seqNo, Byte type, Byte[] ciphertext, Int32 offset, Int32 len) { }
	// RVA: 0x64de65c VA: 0x7598af665c
	protected virtual KeyParameter InitRecord(IStreamCipher cipher, Boolean forEncryption, Int64 seqNo, Byte[] iv) { }
	// RVA: 0x64de78c VA: 0x7598af678c
	protected virtual Byte[] CalculateNonce(Int64 seqNo, Byte[] iv) { }
	// RVA: 0x64de878 VA: 0x7598af6878
	protected virtual KeyParameter GenerateRecordMacKey(IStreamCipher cipher) { }
	// RVA: 0x64de9b0 VA: 0x7598af69b0
	protected virtual Byte[] CalculateRecordMac(KeyParameter macKey, Byte[] additionalData, Byte[] buf, Int32 off, Int32 len) { }
	// RVA: 0x64deb58 VA: 0x7598af6b58
	protected virtual Void UpdateRecordMacLength(IMac mac, Int32 len) { }
	// RVA: 0x64dec20 VA: 0x7598af6c20
	protected virtual Void UpdateRecordMacText(IMac mac, Byte[] buf, Int32 off, Int32 len) { }
	// RVA: 0x64deda8 VA: 0x7598af6da8
	protected virtual Byte[] GetAdditionalData(Int64 seqNo, Byte type, Int32 len) { }
	// RVA: 0x64def08 VA: 0x7598af6f08
	private static Void .cctor() { }
}
```