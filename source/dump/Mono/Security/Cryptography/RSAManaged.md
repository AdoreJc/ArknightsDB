# RSAManaged

**Namespace:** `Mono.Security.Cryptography`


## Fields

- `Boolean isCRTpossible`

- `Boolean keyBlinding`

- `Boolean keypairGenerated`

- `Boolean m_disposed`

- `BigInteger d`

- `BigInteger p`

- `BigInteger q`

- `BigInteger dp`

- `BigInteger dq`

- `BigInteger qInv`

- `BigInteger n`

- `BigInteger e`

- `KeyGeneratedEventHandler KeyGenerated`


## Properties

- `Boolean PublicOnly`


## Methods

- `Void GenerateKeyPair()`

- `Boolean get_PublicOnly()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Cryptography
public class RSAManaged : RSA
{
	private Boolean isCRTpossible; // 0x20
	private Boolean keyBlinding; // 0x21
	private Boolean keypairGenerated; // 0x22
	private Boolean m_disposed; // 0x23
	private BigInteger d; // 0x28
	private BigInteger p; // 0x30
	private BigInteger q; // 0x38
	private BigInteger dp; // 0x40
	private BigInteger dq; // 0x48
	private BigInteger qInv; // 0x50
	private BigInteger n; // 0x58
	private BigInteger e; // 0x60
	private KeyGeneratedEventHandler KeyGenerated; // 0x68

	public override Int32 KeySize { get; }
	public override String KeyExchangeAlgorithm { get; }
	public Boolean PublicOnly { get; }
	public override String SignatureAlgorithm { get; }

	// RVA: 0x5eedb5c VA: 0x7598505b5c
	public Void .ctor() { }
	// RVA: 0x5eedb64 VA: 0x7598505b64
	public Void .ctor(Int32 keySize) { }
	// RVA: 0x5eedc70 VA: 0x7598505c70
	protected override Void Finalize() { }
	// RVA: 0x5eedd10 VA: 0x7598505d10
	private Void GenerateKeyPair() { }
	// RVA: 0x5eee634 VA: 0x7598506634
	public override Int32 get_KeySize() { }
	// RVA: 0x5eee6d8 VA: 0x75985066d8
	public override String get_KeyExchangeAlgorithm() { }
	// RVA: 0x5eee718 VA: 0x7598506718
	public Boolean get_PublicOnly() { }
	// RVA: 0x5eee868 VA: 0x7598506868
	public override String get_SignatureAlgorithm() { }
	// RVA: 0x5eee8a8 VA: 0x75985068a8
	public override Byte[] DecryptValue(Byte[] rgb) { }
	// RVA: 0x5eef0f8 VA: 0x75985070f8
	public override Byte[] EncryptValue(Byte[] rgb) { }
	// RVA: 0x5eef204 VA: 0x7598507204
	public override RSAParameters ExportParameters(Boolean includePrivateParameters) { }
	// RVA: 0x5eef6c8 VA: 0x75985076c8
	public override Void ImportParameters(RSAParameters parameters) { }
	// RVA: 0x5eefc40 VA: 0x7598507c40
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x5eefec4 VA: 0x7598507ec4
	public override String ToXmlString(Boolean includePrivateParameters) { }
	// RVA: 0x5eef048 VA: 0x7598507048
	private Byte[] GetPaddedValue(BigInteger value, Int32 length) { }
}
```