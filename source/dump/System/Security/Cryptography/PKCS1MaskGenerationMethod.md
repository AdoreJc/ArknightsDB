# PKCS1MaskGenerationMethod

**Namespace:** `System.Security.Cryptography`


## Fields

- `String HashNameValue`


## Properties

- `String HashName`


## Methods

- `String get_HashName()`

- `Void set_HashName(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class PKCS1MaskGenerationMethod : MaskGenerationMethod
{
	private String HashNameValue; // 0x10

	public String HashName { get; set; }

	// RVA: 0x5f5703c VA: 0x759856f03c
	public Void .ctor() { }
	// RVA: 0x5f57094 VA: 0x759856f094
	public String get_HashName() { }
	// RVA: 0x5f5709c VA: 0x759856f09c
	public Void set_HashName(String value) { }
	// RVA: 0x5f57110 VA: 0x759856f110
	public override Byte[] GenerateMask(Byte[] rgbSeed, Int32 cbReturn) { }
}
```