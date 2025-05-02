# DefaultTlsCipherFactory

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class DefaultTlsCipherFactory : AbstractTlsCipherFactory
{


	// RVA: 0x64dfe9c VA: 0x7598af7e9c
	public override TlsCipher CreateCipher(TlsContext context, Int32 encryptionAlgorithm, Int32 macAlgorithm) { }
	// RVA: 0x64e004c VA: 0x7598af804c
	protected virtual TlsBlockCipher CreateAESCipher(TlsContext context, Int32 cipherKeySize, Int32 macAlgorithm) { }
	// RVA: 0x64e0d14 VA: 0x7598af8d14
	protected virtual TlsBlockCipher CreateCamelliaCipher(TlsContext context, Int32 cipherKeySize, Int32 macAlgorithm) { }
	// RVA: 0x64e0e18 VA: 0x7598af8e18
	protected virtual TlsCipher CreateChaCha20Poly1305(TlsContext context) { }
	// RVA: 0x64e0e78 VA: 0x7598af8e78
	protected virtual TlsAeadCipher CreateCipher_Aes_Ccm(TlsContext context, Int32 cipherKeySize, Int32 macSize) { }
	// RVA: 0x64e0f44 VA: 0x7598af8f44
	protected virtual TlsAeadCipher CreateCipher_Aes_Gcm(TlsContext context, Int32 cipherKeySize, Int32 macSize) { }
	// RVA: 0x64e1008 VA: 0x7598af9008
	protected virtual TlsAeadCipher CreateCipher_Aes_Ocb(TlsContext context, Int32 cipherKeySize, Int32 macSize) { }
	// RVA: 0x64e154c VA: 0x7598af954c
	protected virtual TlsAeadCipher CreateCipher_Camellia_Gcm(TlsContext context, Int32 cipherKeySize, Int32 macSize) { }
	// RVA: 0x64e1610 VA: 0x7598af9610
	protected virtual TlsBlockCipher CreateDesEdeCipher(TlsContext context, Int32 macAlgorithm) { }
	// RVA: 0x64e1708 VA: 0x7598af9708
	protected virtual TlsNullCipher CreateNullCipher(TlsContext context, Int32 macAlgorithm) { }
	// RVA: 0x64e1c50 VA: 0x7598af9c50
	protected virtual TlsStreamCipher CreateRC4Cipher(TlsContext context, Int32 cipherKeySize, Int32 macAlgorithm) { }
	// RVA: 0x64e1d64 VA: 0x7598af9d64
	protected virtual TlsBlockCipher CreateSeedCipher(TlsContext context, Int32 macAlgorithm) { }
	// RVA: 0x64e1e5c VA: 0x7598af9e5c
	protected virtual IBlockCipher CreateAesEngine() { }
	// RVA: 0x64e1eb8 VA: 0x7598af9eb8
	protected virtual IBlockCipher CreateCamelliaEngine() { }
	// RVA: 0x64e1f14 VA: 0x7598af9f14
	protected virtual IBlockCipher CreateAesBlockCipher() { }
	// RVA: 0x64e1f94 VA: 0x7598af9f94
	protected virtual IAeadBlockCipher CreateAeadBlockCipher_Aes_Ccm() { }
	// RVA: 0x64e2014 VA: 0x7598afa014
	protected virtual IAeadBlockCipher CreateAeadBlockCipher_Aes_Gcm() { }
	// RVA: 0x64e2094 VA: 0x7598afa094
	protected virtual IAeadBlockCipher CreateAeadBlockCipher_Aes_Ocb() { }
	// RVA: 0x64e2130 VA: 0x7598afa130
	protected virtual IAeadBlockCipher CreateAeadBlockCipher_Camellia_Gcm() { }
	// RVA: 0x64e21b0 VA: 0x7598afa1b0
	protected virtual IBlockCipher CreateCamelliaBlockCipher() { }
	// RVA: 0x64e2230 VA: 0x7598afa230
	protected virtual IBlockCipher CreateDesEdeBlockCipher() { }
	// RVA: 0x64e22bc VA: 0x7598afa2bc
	protected virtual IStreamCipher CreateRC4StreamCipher() { }
	// RVA: 0x64e2318 VA: 0x7598afa318
	protected virtual IBlockCipher CreateSeedBlockCipher() { }
	// RVA: 0x64e23a4 VA: 0x7598afa3a4
	protected virtual IDigest CreateHMacDigest(Int32 macAlgorithm) { }
	// RVA: 0x64d9310 VA: 0x7598af1310
	public Void .ctor() { }
}
```