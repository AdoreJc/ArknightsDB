# Rfc3394WrapEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `KeyParameter param`

- `Boolean forWrapping`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class Rfc3394WrapEngine : IWrapper
{
	private readonly IBlockCipher engine; // 0x10
	private KeyParameter param; // 0x18
	private Boolean forWrapping; // 0x20
	private Byte[] iv; // 0x28

	public virtual String AlgorithmName { get; }

	// RVA: 0x6553768 VA: 0x7598b6b768
	public Void .ctor(IBlockCipher engine) { }
	// RVA: 0x655380c VA: 0x7598b6b80c
	public virtual Void Init(Boolean forWrapping, ICipherParameters parameters) { }
	// RVA: 0x6553a54 VA: 0x7598b6ba54
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6553af4 VA: 0x7598b6baf4
	public virtual Byte[] Wrap(Byte[] input, Int32 inOff, Int32 inLen) { }
	// RVA: 0x6553e84 VA: 0x7598b6be84
	public virtual Byte[] Unwrap(Byte[] input, Int32 inOff, Int32 inLen) { }
}
```