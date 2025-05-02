# HMACSHA512

**Namespace:** `System.Security.Cryptography`


## Fields

- `Boolean m_useLegacyBlockSize`


## Properties

- `Int32 BlockSize`

- `Boolean ProduceLegacyHmacValues`


## Methods

- `Int32 get_BlockSize()`

- `Boolean get_ProduceLegacyHmacValues()`

- `Void set_ProduceLegacyHmacValues(Boolean)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class HMACSHA512 : HMAC
{
	private Boolean m_useLegacyBlockSize; // 0x61

	private Int32 BlockSize { get; }
	public Boolean ProduceLegacyHmacValues { get; set; }

	// RVA: 0x5f54804 VA: 0x759856c804
	public Void .ctor() { }
	// RVA: 0x5f54868 VA: 0x759856c868
	public Void .ctor(Byte[] key) { }
	// RVA: 0x5f5499c VA: 0x759856c99c
	private Int32 get_BlockSize() { }
	// RVA: 0x5f549b4 VA: 0x759856c9b4
	public Boolean get_ProduceLegacyHmacValues() { }
	// RVA: 0x5f549bc VA: 0x759856c9bc
	public Void set_ProduceLegacyHmacValues(Boolean value) { }
}
```