# MqvPrivateParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class MqvPrivateParameters : ICipherParameters
{
	private readonly ECPrivateKeyParameters staticPrivateKey; // 0x10
	private readonly ECPrivateKeyParameters ephemeralPrivateKey; // 0x18
	private readonly ECPublicKeyParameters ephemeralPublicKey; // 0x20

	public virtual ECPrivateKeyParameters StaticPrivateKey { get; }
	public virtual ECPrivateKeyParameters EphemeralPrivateKey { get; }
	public virtual ECPublicKeyParameters EphemeralPublicKey { get; }

	// RVA: 0x65199b8 VA: 0x7598b319b8
	public Void .ctor(ECPrivateKeyParameters staticPrivateKey, ECPrivateKeyParameters ephemeralPrivateKey) { }
	// RVA: 0x65199c0 VA: 0x7598b319c0
	public Void .ctor(ECPrivateKeyParameters staticPrivateKey, ECPrivateKeyParameters ephemeralPrivateKey, ECPublicKeyParameters ephemeralPublicKey) { }
	// RVA: 0x6519ba8 VA: 0x7598b31ba8
	public virtual ECPrivateKeyParameters get_StaticPrivateKey() { }
	// RVA: 0x6519bb0 VA: 0x7598b31bb0
	public virtual ECPrivateKeyParameters get_EphemeralPrivateKey() { }
	// RVA: 0x6519bb8 VA: 0x7598b31bb8
	public virtual ECPublicKeyParameters get_EphemeralPublicKey() { }
}
```