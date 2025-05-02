# DSAManaged

**Namespace:** `Mono.Security.Cryptography`


## Fields

- `Boolean keypairGenerated`

- `Boolean m_disposed`

- `BigInteger p`

- `BigInteger q`

- `BigInteger g`

- `BigInteger x`

- `BigInteger y`

- `BigInteger j`

- `BigInteger seed`

- `Int32 counter`

- `Boolean j_missing`

- `RandomNumberGenerator rng`

- `KeyGeneratedEventHandler KeyGenerated`


## Properties

- `RandomNumberGenerator Random`

- `Boolean PublicOnly`


## Methods

- `Void Generate()`

- `Void GenerateKeyPair()`

- `Void add(Byte[], Byte[], Int32)`

- `Void GenerateParams(Int32)`

- `RandomNumberGenerator get_Random()`

- `Boolean get_PublicOnly()`

- `Void add_KeyGenerated(KeyGeneratedEventHandler)`

- `Void remove_KeyGenerated(KeyGeneratedEventHandler)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : Mono.Security.Cryptography
internal class DSAManaged : DSA
{
	private Boolean keypairGenerated; // 0x20
	private Boolean m_disposed; // 0x21
	private BigInteger p; // 0x28
	private BigInteger q; // 0x30
	private BigInteger g; // 0x38
	private BigInteger x; // 0x40
	private BigInteger y; // 0x48
	private BigInteger j; // 0x50
	private BigInteger seed; // 0x58
	private Int32 counter; // 0x60
	private Boolean j_missing; // 0x64
	private RandomNumberGenerator rng; // 0x68
	private KeyGeneratedEventHandler KeyGenerated; // 0x70

	private RandomNumberGenerator Random { get; }
	public override Int32 KeySize { get; }
	public override String KeyExchangeAlgorithm { get; }
	public Boolean PublicOnly { get; }
	public override String SignatureAlgorithm { get; }

	// RVA: 0x5f14e80 VA: 0x759852ce80
	public Void .ctor(Int32 dwKeySize) { }
	// RVA: 0x5f14f74 VA: 0x759852cf74
	protected override Void Finalize() { }
	// RVA: 0x5f15014 VA: 0x759852d014
	private Void Generate() { }
	// RVA: 0x5f155e8 VA: 0x759852d5e8
	private Void GenerateKeyPair() { }
	// RVA: 0x5f157bc VA: 0x759852d7bc
	private Void add(Byte[] a, Byte[] b, Int32 value) { }
	// RVA: 0x5f15060 VA: 0x759852d060
	private Void GenerateParams(Int32 keyLength) { }
	// RVA: 0x5f15860 VA: 0x759852d860
	private RandomNumberGenerator get_Random() { }
	// RVA: 0x5f15ba4 VA: 0x759852dba4
	public override Int32 get_KeySize() { }
	// RVA: 0x5f15bd0 VA: 0x759852dbd0
	public override String get_KeyExchangeAlgorithm() { }
	// RVA: 0x5f15bd8 VA: 0x759852dbd8
	public Boolean get_PublicOnly() { }
	// RVA: 0x5f15c4c VA: 0x759852dc4c
	public override String get_SignatureAlgorithm() { }
	// RVA: 0x5f15c8c VA: 0x759852dc8c
	private Byte[] NormalizeArray(Byte[] array) { }
	// RVA: 0x5f15d30 VA: 0x759852dd30
	public override DSAParameters ExportParameters(Boolean includePrivateParameters) { }
	// RVA: 0x5f1605c VA: 0x759852e05c
	public override Void ImportParameters(DSAParameters parameters) { }
	// RVA: 0x5f16394 VA: 0x759852e394
	public override Byte[] CreateSignature(Byte[] rgbHash) { }
	// RVA: 0x5f166bc VA: 0x759852e6bc
	public override Boolean VerifySignature(Byte[] rgbHash, Byte[] rgbSignature) { }
	// RVA: 0x5f16b7c VA: 0x759852eb7c
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x5f16dbc VA: 0x759852edbc
	public Void add_KeyGenerated(KeyGeneratedEventHandler value) { }
	// RVA: 0x5f16e58 VA: 0x759852ee58
	public Void remove_KeyGenerated(KeyGeneratedEventHandler value) { }
}
```