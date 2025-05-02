# TlsRsaSigner

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsRsaSigner : AbstractTlsSigner
{


	// RVA: 0x64fe3dc VA: 0x7598b163dc
	public override Byte[] GenerateRawSignature(SignatureAndHashAlgorithm algorithm, AsymmetricKeyParameter privateKey, Byte[] hash) { }
	// RVA: 0x64fe5e4 VA: 0x7598b165e4
	public override Boolean VerifyRawSignature(SignatureAndHashAlgorithm algorithm, Byte[] sigBytes, AsymmetricKeyParameter publicKey, Byte[] hash) { }
	// RVA: 0x64fe740 VA: 0x7598b16740
	public override ISigner CreateSigner(SignatureAndHashAlgorithm algorithm, AsymmetricKeyParameter privateKey) { }
	// RVA: 0x64fe854 VA: 0x7598b16854
	public override ISigner CreateVerifyer(SignatureAndHashAlgorithm algorithm, AsymmetricKeyParameter publicKey) { }
	// RVA: 0x64fe870 VA: 0x7598b16870
	public override Boolean IsValidPublicKey(AsymmetricKeyParameter publicKey) { }
	// RVA: 0x64fe8f4 VA: 0x7598b168f4
	protected virtual ISigner MakeSigner(SignatureAndHashAlgorithm algorithm, Boolean raw, Boolean forSigning, ICipherParameters cp) { }
	// RVA: 0x64ff0ec VA: 0x7598b170ec
	protected virtual IAsymmetricBlockCipher CreateRsaImpl() { }
	// RVA: 0x64ff178 VA: 0x7598b17178
	public Void .ctor() { }
}
```