# Rfc3211WrapEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `CbcBlockCipher engine`

- `ParametersWithIV param`

- `Boolean forWrapping`

- `SecureRandom rand`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class Rfc3211WrapEngine : IWrapper
{
	private CbcBlockCipher engine; // 0x10
	private ParametersWithIV param; // 0x18
	private Boolean forWrapping; // 0x20
	private SecureRandom rand; // 0x28

	public virtual String AlgorithmName { get; }

	// RVA: 0x6552e78 VA: 0x7598b6ae78
	public Void .ctor(IBlockCipher engine) { }
	// RVA: 0x6552efc VA: 0x7598b6aefc
	public virtual Void Init(Boolean forWrapping, ICipherParameters param) { }
	// RVA: 0x655305c VA: 0x7598b6b05c
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6553124 VA: 0x7598b6b124
	public virtual Byte[] Wrap(Byte[] inBytes, Int32 inOff, Int32 inLen) { }
	// RVA: 0x6553390 VA: 0x7598b6b390
	public virtual Byte[] Unwrap(Byte[] inBytes, Int32 inOff, Int32 inLen) { }
}
```