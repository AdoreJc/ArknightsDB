# ElGamalEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `ElGamalKeyParameters key`

- `SecureRandom random`

- `Boolean forEncryption`

- `Int32 bitSize`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class ElGamalEngine : IAsymmetricBlockCipher
{
	private ElGamalKeyParameters key; // 0x10
	private SecureRandom random; // 0x18
	private Boolean forEncryption; // 0x20
	private Int32 bitSize; // 0x24

	public virtual String AlgorithmName { get; }

	// RVA: 0x6548978 VA: 0x7598b60978
	public virtual String get_AlgorithmName() { }
	// RVA: 0x65489b8 VA: 0x7598b609b8
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6548ca0 VA: 0x7598b60ca0
	public virtual Int32 GetInputBlockSize() { }
	// RVA: 0x6548ce0 VA: 0x7598b60ce0
	public virtual Int32 GetOutputBlockSize() { }
	// RVA: 0x6548d20 VA: 0x7598b60d20
	public virtual Byte[] ProcessBlock(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x654924c VA: 0x7598b6124c
	public Void .ctor() { }
}
```