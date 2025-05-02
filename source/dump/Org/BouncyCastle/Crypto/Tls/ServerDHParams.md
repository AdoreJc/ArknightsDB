# ServerDHParams

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class ServerDHParams
{
	protected readonly DHPublicKeyParameters mPublicKey; // 0x10

	public virtual DHPublicKeyParameters PublicKey { get; }

	// RVA: 0x64e77c0 VA: 0x7598aff7c0
	public Void .ctor(DHPublicKeyParameters publicKey) { }
	// RVA: 0x64e7840 VA: 0x7598aff840
	public virtual DHPublicKeyParameters get_PublicKey() { }
	// RVA: 0x64e7848 VA: 0x7598aff848
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64e795c VA: 0x7598aff95c
	public static ServerDHParams Parse(Stream input) { }
}
```