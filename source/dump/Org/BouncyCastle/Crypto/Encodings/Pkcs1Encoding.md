# Pkcs1Encoding

**Namespace:** `Org.BouncyCastle.Crypto.Encodings`


## Fields

- `SecureRandom random`

- `IAsymmetricBlockCipher engine`

- `Boolean forEncryption`

- `Boolean forPrivateKey`

- `Boolean useStrictLength`

- `Int32 pLen`


## Properties

- `String AlgorithmName`


## Methods

- `IAsymmetricBlockCipher GetUnderlyingCipher()`

- `String get_AlgorithmName()`

- `Void Init(Boolean, ICipherParameters)`

- `Int32 GetInputBlockSize()`

- `Int32 GetOutputBlockSize()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Encodings
public class Pkcs1Encoding : IAsymmetricBlockCipher
{
	public const String StrictLengthEnabledProperty; // 0x0
	private const Int32 HeaderLength; // 0x0
	private static readonly Boolean[] strictLengthEnabled; // 0x0
	private SecureRandom random; // 0x10
	private IAsymmetricBlockCipher engine; // 0x18
	private Boolean forEncryption; // 0x20
	private Boolean forPrivateKey; // 0x21
	private Boolean useStrictLength; // 0x22
	private Int32 pLen; // 0x24
	private Byte[] fallback; // 0x28

	public static Boolean StrictLengthEnabled { get; set; }
	public String AlgorithmName { get; }

	// RVA: 0x6570930 VA: 0x7598b88930
	public static Boolean get_StrictLengthEnabled() { }
	// RVA: 0x65709a0 VA: 0x7598b889a0
	public static Void set_StrictLengthEnabled(Boolean value) { }
	// RVA: 0x6570a18 VA: 0x7598b88a18
	private static Void .cctor() { }
	// RVA: 0x6570b24 VA: 0x7598b88b24
	public Void .ctor(IAsymmetricBlockCipher cipher) { }
	// RVA: 0x6570bb0 VA: 0x7598b88bb0
	public Void .ctor(IAsymmetricBlockCipher cipher, Int32 pLen) { }
	// RVA: 0x6570c44 VA: 0x7598b88c44
	public Void .ctor(IAsymmetricBlockCipher cipher, Byte[] fallback) { }
	// RVA: 0x6570cf4 VA: 0x7598b88cf4
	public IAsymmetricBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x6570cfc VA: 0x7598b88cfc
	public String get_AlgorithmName() { }
	// RVA: 0x6570dbc VA: 0x7598b88dbc
	public Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6570fb0 VA: 0x7598b88fb0
	public Int32 GetInputBlockSize() { }
	// RVA: 0x6571068 VA: 0x7598b89068
	public Int32 GetOutputBlockSize() { }
	// RVA: 0x6571120 VA: 0x7598b89120
	public Byte[] ProcessBlock(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x6571450 VA: 0x7598b89450
	private Byte[] EncodeBlock(Byte[] input, Int32 inOff, Int32 inLen) { }
	// RVA: 0x6571758 VA: 0x7598b89758
	private static Int32 CheckPkcs1Encoding(Byte[] encoded, Int32 pLen) { }
	// RVA: 0x65717f8 VA: 0x7598b897f8
	private Byte[] DecodeBlockOrRandom(Byte[] input, Int32 inOff, Int32 inLen) { }
	// RVA: 0x6571130 VA: 0x7598b89130
	private Byte[] DecodeBlock(Byte[] input, Int32 inOff, Int32 inLen) { }
}
```