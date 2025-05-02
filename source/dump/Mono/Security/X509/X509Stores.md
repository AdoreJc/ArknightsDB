# X509Stores

**Namespace:** `Mono.Security.X509`


## Fields

- `String _storePath`

- `Boolean _newFormat`

- `X509Store _trusted`


## Properties

- `X509Store TrustedRoot`


## Methods

- `X509Store get_TrustedRoot()`

- `X509Store Open(String, Boolean)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509
public class X509Stores
{
	private String _storePath; // 0x10
	private Boolean _newFormat; // 0x18
	private X509Store _trusted; // 0x20

	public X509Store TrustedRoot { get; }

	// RVA: 0x5ee4ca0 VA: 0x75984fcca0
	internal Void .ctor(String path, Boolean newFormat) { }
	// RVA: 0x5ee4d98 VA: 0x75984fcd98
	public X509Store get_TrustedRoot() { }
	// RVA: 0x5ee4e90 VA: 0x75984fce90
	public X509Store Open(String storeName, Boolean create) { }
}
```