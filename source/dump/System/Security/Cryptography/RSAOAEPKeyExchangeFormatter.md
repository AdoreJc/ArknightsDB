# RSAOAEPKeyExchangeFormatter

**Namespace:** `System.Security.Cryptography`


## Fields

- `RSA _rsaKey`

- `RandomNumberGenerator RngValue`


## Properties

- `RandomNumberGenerator Rng`

- `Boolean OverridesEncrypt`


## Methods

- `Void set_Parameter(Byte[])`

- `RandomNumberGenerator get_Rng()`

- `Void set_Rng(RandomNumberGenerator)`

- `Boolean get_OverridesEncrypt()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class RSAOAEPKeyExchangeFormatter : AsymmetricKeyExchangeFormatter
{
	private Byte[] ParameterValue; // 0x10
	private RSA _rsaKey; // 0x18
	private Nullable`1 _rsaOverridesEncrypt; // 0x20
	private RandomNumberGenerator RngValue; // 0x28

	public Byte[] Parameter { get; set; }
	public override String Parameters { get; }
	public RandomNumberGenerator Rng { get; set; }
	private Boolean OverridesEncrypt { get; }

	// RVA: 0x5f632a8 VA: 0x759857b2a8
	public Void .ctor() { }
	// RVA: 0x5f6177c VA: 0x759857977c
	public Void .ctor(AsymmetricAlgorithm key) { }
	// RVA: 0x5f632b0 VA: 0x759857b2b0
	public Byte[] get_Parameter() { }
	// RVA: 0x5f63324 VA: 0x759857b324
	public Void set_Parameter(Byte[] value) { }
	// RVA: 0x5f633e0 VA: 0x759857b3e0
	public override String get_Parameters() { }
	// RVA: 0x5f633e8 VA: 0x759857b3e8
	public RandomNumberGenerator get_Rng() { }
	// RVA: 0x5f633f0 VA: 0x759857b3f0
	public Void set_Rng(RandomNumberGenerator value) { }
	// RVA: 0x5f633f8 VA: 0x759857b3f8
	public override Void SetKey(AsymmetricAlgorithm key) { }
	// RVA: 0x5f634f4 VA: 0x759857b4f4
	public override Byte[] CreateKeyExchange(Byte[] rgbData) { }
	// RVA: 0x5f63930 VA: 0x759857b930
	public override Byte[] CreateKeyExchange(Byte[] rgbData, Type symAlgType) { }
	// RVA: 0x5f636a0 VA: 0x759857b6a0
	private Boolean get_OverridesEncrypt() { }
}
```