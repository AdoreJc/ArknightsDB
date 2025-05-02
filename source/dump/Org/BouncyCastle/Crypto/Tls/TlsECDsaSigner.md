# TlsECDsaSigner

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsECDsaSigner : TlsDsaSigner
{

	protected override Byte SignatureAlgorithm { get; }

	// RVA: 0x64f7870 VA: 0x7598b0f870
	public override Boolean IsValidPublicKey(AsymmetricKeyParameter publicKey) { }
	// RVA: 0x64f78e8 VA: 0x7598b0f8e8
	protected override IDsa CreateDsaImpl(Byte hashAlgorithm) { }
	// RVA: 0x64f79b4 VA: 0x7598b0f9b4
	protected override Byte get_SignatureAlgorithm() { }
	// RVA: 0x64f6b90 VA: 0x7598b0eb90
	public Void .ctor() { }
}
```