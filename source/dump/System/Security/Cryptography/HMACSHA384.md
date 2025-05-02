# HMACSHA384

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
public class HMACSHA384 : HMAC
{
	private Boolean m_useLegacyBlockSize; // 0x61

	private Int32 BlockSize { get; }
	public Boolean ProduceLegacyHmacValues { get; set; }

	// RVA: 0x5f54628 VA: 0x759856c628
	public Void .ctor() { }
	// RVA: 0x5f5468c VA: 0x759856c68c
	public Void .ctor(Byte[] key) { }
	// RVA: 0x5f547c0 VA: 0x759856c7c0
	private Int32 get_BlockSize() { }
	// RVA: 0x5f547d8 VA: 0x759856c7d8
	public Boolean get_ProduceLegacyHmacValues() { }
	// RVA: 0x5f547e0 VA: 0x759856c7e0
	public Void set_ProduceLegacyHmacValues(Boolean value) { }
}
```