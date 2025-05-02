# RSAPKCS1KeyExchangeFormatter

**Namespace:** `System.Security.Cryptography`


## Fields

- `RandomNumberGenerator RngValue`

- `RSA _rsaKey`


## Properties

- `RandomNumberGenerator Rng`

- `Boolean OverridesEncrypt`


## Methods

- `RandomNumberGenerator get_Rng()`

- `Void set_Rng(RandomNumberGenerator)`

- `Boolean get_OverridesEncrypt()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class RSAPKCS1KeyExchangeFormatter : AsymmetricKeyExchangeFormatter
{
	private RandomNumberGenerator RngValue; // 0x10
	private RSA _rsaKey; // 0x18
	private Nullable`1 _rsaOverridesEncrypt; // 0x20

	public override String Parameters { get; }
	public RandomNumberGenerator Rng { get; set; }
	private Boolean OverridesEncrypt { get; }

	// RVA: 0x5f63e50 VA: 0x759857be50
	public Void .ctor() { }
	// RVA: 0x5f6187c VA: 0x759857987c
	public Void .ctor(AsymmetricAlgorithm key) { }
	// RVA: 0x5f63e58 VA: 0x759857be58
	public override String get_Parameters() { }
	// RVA: 0x5f63e98 VA: 0x759857be98
	public RandomNumberGenerator get_Rng() { }
	// RVA: 0x5f63ea0 VA: 0x759857bea0
	public Void set_Rng(RandomNumberGenerator value) { }
	// RVA: 0x5f63ea8 VA: 0x759857bea8
	public override Void SetKey(AsymmetricAlgorithm key) { }
	// RVA: 0x5f63fa4 VA: 0x759857bfa4
	public override Byte[] CreateKeyExchange(Byte[] rgbData) { }
	// RVA: 0x5f644f4 VA: 0x759857c4f4
	public override Byte[] CreateKeyExchange(Byte[] rgbData, Type symAlgType) { }
	// RVA: 0x5f642e4 VA: 0x759857c2e4
	private Boolean get_OverridesEncrypt() { }
}
```