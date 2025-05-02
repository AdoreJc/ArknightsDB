# MqvPublicParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class MqvPublicParameters : ICipherParameters
{
	private readonly ECPublicKeyParameters staticPublicKey; // 0x10
	private readonly ECPublicKeyParameters ephemeralPublicKey; // 0x18

	public virtual ECPublicKeyParameters StaticPublicKey { get; }
	public virtual ECPublicKeyParameters EphemeralPublicKey { get; }

	// RVA: 0x6519bc0 VA: 0x7598b31bc0
	public Void .ctor(ECPublicKeyParameters staticPublicKey, ECPublicKeyParameters ephemeralPublicKey) { }
	// RVA: 0x6519cd4 VA: 0x7598b31cd4
	public virtual ECPublicKeyParameters get_StaticPublicKey() { }
	// RVA: 0x6519cdc VA: 0x7598b31cdc
	public virtual ECPublicKeyParameters get_EphemeralPublicKey() { }
}
```