# PemObject

**Namespace:** `Org.BouncyCastle.Utilities.IO.Pem`


## Fields

- `String type`

- `IList headers`


## Properties

- `String Type`

- `IList Headers`


## Methods

- `String get_Type()`

- `IList get_Headers()`

- `PemObject Generate()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.IO.Pem
public class PemObject : PemObjectGenerator
{
	private String type; // 0x10
	private IList headers; // 0x18
	private Byte[] content; // 0x20

	public String Type { get; }
	public IList Headers { get; }
	public Byte[] Content { get; }

	// RVA: 0x66f7ad8 VA: 0x7598d0fad8
	public Void .ctor(String type, Byte[] content) { }
	// RVA: 0x66f7b50 VA: 0x7598d0fb50
	public Void .ctor(String type, IList headers, Byte[] content) { }
	// RVA: 0x66f7c00 VA: 0x7598d0fc00
	public String get_Type() { }
	// RVA: 0x66f7c08 VA: 0x7598d0fc08
	public IList get_Headers() { }
	// RVA: 0x66f7c10 VA: 0x7598d0fc10
	public Byte[] get_Content() { }
	// RVA: 0x66f7c18 VA: 0x7598d0fc18
	public PemObject Generate() { }
}
```