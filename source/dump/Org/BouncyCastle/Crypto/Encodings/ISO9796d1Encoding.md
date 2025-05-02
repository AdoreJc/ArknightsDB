# ISO9796d1Encoding

**Namespace:** `Org.BouncyCastle.Crypto.Encodings`


## Fields

- `Boolean forEncryption`

- `Int32 bitSize`

- `Int32 padBits`

- `BigInteger modulus`


## Properties

- `String AlgorithmName`


## Methods

- `String get_AlgorithmName()`

- `IAsymmetricBlockCipher GetUnderlyingCipher()`

- `Void Init(Boolean, ICipherParameters)`

- `Int32 GetInputBlockSize()`

- `Int32 GetOutputBlockSize()`

- `Void SetPadBits(Int32)`

- `Int32 GetPadBits()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Encodings
public class ISO9796d1Encoding : IAsymmetricBlockCipher
{
	private static readonly BigInteger Sixteen; // 0x0
	private static readonly BigInteger Six; // 0x8
	private static readonly Byte[] shadows; // 0x10
	private static readonly Byte[] inverse; // 0x18
	private readonly IAsymmetricBlockCipher engine; // 0x10
	private Boolean forEncryption; // 0x18
	private Int32 bitSize; // 0x1c
	private Int32 padBits; // 0x20
	private BigInteger modulus; // 0x28

	public String AlgorithmName { get; }

	// RVA: 0x656e7b0 VA: 0x7598b867b0
	public Void .ctor(IAsymmetricBlockCipher cipher) { }
	// RVA: 0x656e7e0 VA: 0x7598b867e0
	public String get_AlgorithmName() { }
	// RVA: 0x656e8a0 VA: 0x7598b868a0
	public IAsymmetricBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x656e8a8 VA: 0x7598b868a8
	public Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x656ea64 VA: 0x7598b86a64
	public Int32 GetInputBlockSize() { }
	// RVA: 0x656eb28 VA: 0x7598b86b28
	public Int32 GetOutputBlockSize() { }
	// RVA: 0x656ebec VA: 0x7598b86bec
	public Void SetPadBits(Int32 padBits) { }
	// RVA: 0x656ec50 VA: 0x7598b86c50
	public Int32 GetPadBits() { }
	// RVA: 0x656ec58 VA: 0x7598b86c58
	public Byte[] ProcessBlock(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x656ec68 VA: 0x7598b86c68
	private Byte[] EncodeBlock(Byte[] input, Int32 inOff, Int32 inLen) { }
	// RVA: 0x656efb4 VA: 0x7598b86fb4
	private Byte[] DecodeBlock(Byte[] input, Int32 inOff, Int32 inLen) { }
	// RVA: 0x656f494 VA: 0x7598b87494
	private static Void .cctor() { }
}
```