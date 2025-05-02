# OaepEncoding

**Namespace:** `Org.BouncyCastle.Crypto.Encodings`


## Fields

- `IDigest hash`

- `IDigest mgf1Hash`

- `IAsymmetricBlockCipher engine`

- `SecureRandom random`

- `Boolean forEncryption`


## Properties

- `String AlgorithmName`


## Methods

- `IAsymmetricBlockCipher GetUnderlyingCipher()`

- `String get_AlgorithmName()`

- `Void Init(Boolean, ICipherParameters)`

- `Int32 GetInputBlockSize()`

- `Int32 GetOutputBlockSize()`

- `Void ItoOSP(Int32, Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Encodings
public class OaepEncoding : IAsymmetricBlockCipher
{
	private Byte[] defHash; // 0x10
	private IDigest hash; // 0x18
	private IDigest mgf1Hash; // 0x20
	private IAsymmetricBlockCipher engine; // 0x28
	private SecureRandom random; // 0x30
	private Boolean forEncryption; // 0x38

	public String AlgorithmName { get; }

	// RVA: 0x656f5e0 VA: 0x7598b875e0
	public Void .ctor(IAsymmetricBlockCipher cipher) { }
	// RVA: 0x656f668 VA: 0x7598b87668
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest hash) { }
	// RVA: 0x656f65c VA: 0x7598b8765c
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest hash, Byte[] encodingParams) { }
	// RVA: 0x656f674 VA: 0x7598b87674
	public Void .ctor(IAsymmetricBlockCipher cipher, IDigest hash, IDigest mgf1Hash, Byte[] encodingParams) { }
	// RVA: 0x656f87c VA: 0x7598b8787c
	public IAsymmetricBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x656f884 VA: 0x7598b87884
	public String get_AlgorithmName() { }
	// RVA: 0x656f944 VA: 0x7598b87944
	public Void Init(Boolean forEncryption, ICipherParameters param) { }
	// RVA: 0x656fa9c VA: 0x7598b87a9c
	public Int32 GetInputBlockSize() { }
	// RVA: 0x656fb64 VA: 0x7598b87b64
	public Int32 GetOutputBlockSize() { }
	// RVA: 0x656fc2c VA: 0x7598b87c2c
	public Byte[] ProcessBlock(Byte[] inBytes, Int32 inOff, Int32 inLen) { }
	// RVA: 0x656fc3c VA: 0x7598b87c3c
	private Byte[] EncodeBlock(Byte[] inBytes, Int32 inOff, Int32 inLen) { }
	// RVA: 0x656ff28 VA: 0x7598b87f28
	private Byte[] DecodeBlock(Byte[] inBytes, Int32 inOff, Int32 inLen) { }
	// RVA: 0x65708dc VA: 0x7598b888dc
	private Void ItoOSP(Int32 i, Byte[] sp) { }
	// RVA: 0x6570420 VA: 0x7598b88420
	private Byte[] maskGeneratorFunction1(Byte[] Z, Int32 zOff, Int32 zLen, Int32 length) { }
}
```