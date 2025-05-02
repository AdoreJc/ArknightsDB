# TlsDheKeyExchange

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `TlsSignerCredentials mServerCredentials`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsDheKeyExchange : TlsDHKeyExchange
{
	protected TlsSignerCredentials mServerCredentials; // 0x58


	// RVA: 0x64e28ac VA: 0x7598afa8ac
	public Void .ctor(Int32 keyExchange, IList supportedSignatureAlgorithms, DHParameters dhParameters) { }
	// RVA: 0x64f01f8 VA: 0x7598b081f8
	public override Void ProcessServerCredentials(TlsCredentials serverCredentials) { }
	// RVA: 0x64f035c VA: 0x7598b0835c
	public override Byte[] GenerateServerKeyExchange() { }
	// RVA: 0x64f0900 VA: 0x7598b08900
	public override Void ProcessServerKeyExchange(Stream input) { }
	// RVA: 0x64f0be4 VA: 0x7598b08be4
	protected virtual ISigner InitVerifyer(TlsSigner tlsSigner, SignatureAndHashAlgorithm algorithm, SecurityParameters securityParameters) { }
}
```