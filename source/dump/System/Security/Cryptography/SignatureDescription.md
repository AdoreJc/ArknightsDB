# SignatureDescription

**Namespace:** `System.Security.Cryptography`


## Fields

- `String _strKey`

- `String _strDigest`

- `String _strFormatter`

- `String _strDeformatter`


## Properties

- `String KeyAlgorithm`

- `String DigestAlgorithm`

- `String FormatterAlgorithm`

- `String DeformatterAlgorithm`


## Methods

- `String get_KeyAlgorithm()`

- `Void set_KeyAlgorithm(String)`

- `String get_DigestAlgorithm()`

- `Void set_DigestAlgorithm(String)`

- `String get_FormatterAlgorithm()`

- `Void set_FormatterAlgorithm(String)`

- `String get_DeformatterAlgorithm()`

- `Void set_DeformatterAlgorithm(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class SignatureDescription
{
	private String _strKey; // 0x10
	private String _strDigest; // 0x18
	private String _strFormatter; // 0x20
	private String _strDeformatter; // 0x28

	public String KeyAlgorithm { get; set; }
	public String DigestAlgorithm { get; set; }
	public String FormatterAlgorithm { get; set; }
	public String DeformatterAlgorithm { get; set; }

	// RVA: 0x5f67f9c VA: 0x759857ff9c
	public Void .ctor() { }
	// RVA: 0x5f67fa4 VA: 0x759857ffa4
	public Void .ctor(SecurityElement el) { }
	// RVA: 0x5f68104 VA: 0x7598580104
	public String get_KeyAlgorithm() { }
	// RVA: 0x5f6810c VA: 0x759858010c
	public Void set_KeyAlgorithm(String value) { }
	// RVA: 0x5f68114 VA: 0x7598580114
	public String get_DigestAlgorithm() { }
	// RVA: 0x5f6811c VA: 0x759858011c
	public Void set_DigestAlgorithm(String value) { }
	// RVA: 0x5f68124 VA: 0x7598580124
	public String get_FormatterAlgorithm() { }
	// RVA: 0x5f6812c VA: 0x759858012c
	public Void set_FormatterAlgorithm(String value) { }
	// RVA: 0x5f68134 VA: 0x7598580134
	public String get_DeformatterAlgorithm() { }
	// RVA: 0x5f6813c VA: 0x759858013c
	public Void set_DeformatterAlgorithm(String value) { }
	// RVA: 0x5f68144 VA: 0x7598580144
	public virtual AsymmetricSignatureDeformatter CreateDeformatter(AsymmetricAlgorithm key) { }
	// RVA: 0x5f68214 VA: 0x7598580214
	public virtual AsymmetricSignatureFormatter CreateFormatter(AsymmetricAlgorithm key) { }
	// RVA: 0x5f682e4 VA: 0x75985802e4
	public virtual HashAlgorithm CreateDigest() { }
}
```