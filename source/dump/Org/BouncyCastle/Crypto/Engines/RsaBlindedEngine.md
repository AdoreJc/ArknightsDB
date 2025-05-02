# RsaBlindedEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `RsaKeyParameters key`

- `SecureRandom random`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class RsaBlindedEngine : IAsymmetricBlockCipher
{
	private readonly RsaCoreEngine core; // 0x10
	private RsaKeyParameters key; // 0x18
	private SecureRandom random; // 0x20

	public virtual String AlgorithmName { get; }

	// RVA: 0x65564d0 VA: 0x7598b6e4d0
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6556510 VA: 0x7598b6e510
	public virtual Void Init(Boolean forEncryption, ICipherParameters param) { }
	// RVA: 0x65566e4 VA: 0x7598b6e6e4
	public virtual Int32 GetInputBlockSize() { }
	// RVA: 0x6556704 VA: 0x7598b6e704
	public virtual Int32 GetOutputBlockSize() { }
	// RVA: 0x6556724 VA: 0x7598b6e724
	public virtual Byte[] ProcessBlock(Byte[] inBuf, Int32 inOff, Int32 inLen) { }
	// RVA: 0x65569a8 VA: 0x7598b6e9a8
	public Void .ctor() { }
}
```