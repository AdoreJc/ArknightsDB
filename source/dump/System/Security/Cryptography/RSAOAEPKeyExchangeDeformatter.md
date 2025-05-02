# RSAOAEPKeyExchangeDeformatter

**Namespace:** `System.Security.Cryptography`


## Fields

- `RSA _rsaKey`


## Properties

- `Boolean OverridesDecrypt`


## Methods

- `Boolean get_OverridesDecrypt()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class RSAOAEPKeyExchangeDeformatter : AsymmetricKeyExchangeDeformatter
{
	private RSA _rsaKey; // 0x10
	private Nullable`1 _rsaOverridesDecrypt; // 0x18

	public override String Parameters { get; set; }
	private Boolean OverridesDecrypt { get; }

	// RVA: 0x5f62c28 VA: 0x759857ac28
	public Void .ctor() { }
	// RVA: 0x5f614e4 VA: 0x75985794e4
	public Void .ctor(AsymmetricAlgorithm key) { }
	// RVA: 0x5f62c30 VA: 0x759857ac30
	public override String get_Parameters() { }
	// RVA: 0x5f62c38 VA: 0x759857ac38
	public override Void set_Parameters(String value) { }
	// RVA: 0x5f62c3c VA: 0x759857ac3c
	public override Byte[] DecryptKeyExchange(Byte[] rgbData) { }
	// RVA: 0x5f630b4 VA: 0x759857b0b4
	public override Void SetKey(AsymmetricAlgorithm key) { }
	// RVA: 0x5f62dd4 VA: 0x759857add4
	private Boolean get_OverridesDecrypt() { }
}
```