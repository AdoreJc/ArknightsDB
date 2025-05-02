# RSAPKCS1KeyExchangeDeformatter

**Namespace:** `System.Security.Cryptography`


## Fields

- `RSA _rsaKey`

- `RandomNumberGenerator RngValue`


## Properties

- `RandomNumberGenerator RNG`

- `Boolean OverridesDecrypt`


## Methods

- `RandomNumberGenerator get_RNG()`

- `Void set_RNG(RandomNumberGenerator)`

- `Boolean get_OverridesDecrypt()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class RSAPKCS1KeyExchangeDeformatter : AsymmetricKeyExchangeDeformatter
{
	private RSA _rsaKey; // 0x10
	private Nullable`1 _rsaOverridesDecrypt; // 0x18
	private RandomNumberGenerator RngValue; // 0x20

	public RandomNumberGenerator RNG { get; set; }
	public override String Parameters { get; set; }
	private Boolean OverridesDecrypt { get; }

	// RVA: 0x5f6393c VA: 0x759857b93c
	public Void .ctor() { }
	// RVA: 0x5f615e4 VA: 0x75985795e4
	public Void .ctor(AsymmetricAlgorithm key) { }
	// RVA: 0x5f63944 VA: 0x759857b944
	public RandomNumberGenerator get_RNG() { }
	// RVA: 0x5f6394c VA: 0x759857b94c
	public Void set_RNG(RandomNumberGenerator value) { }
	// RVA: 0x5f63954 VA: 0x759857b954
	public override String get_Parameters() { }
	// RVA: 0x5f6395c VA: 0x759857b95c
	public override Void set_Parameters(String value) { }
	// RVA: 0x5f63960 VA: 0x759857b960
	public override Byte[] DecryptKeyExchange(Byte[] rgbIn) { }
	// RVA: 0x5f63d54 VA: 0x759857bd54
	public override Void SetKey(AsymmetricAlgorithm key) { }
	// RVA: 0x5f63b44 VA: 0x759857bb44
	private Boolean get_OverridesDecrypt() { }
}
```