# PemParser

**Namespace:** `Org.BouncyCastle.X509`


## Methods

- `String ReadLine(Stream)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.X509
internal class PemParser
{
	private readonly String _header1; // 0x10
	private readonly String _header2; // 0x18
	private readonly String _footer1; // 0x20
	private readonly String _footer2; // 0x28


	// RVA: 0x66e0198 VA: 0x7598cf8198
	internal Void .ctor(String type) { }
	// RVA: 0x66e02dc VA: 0x7598cf82dc
	private String ReadLine(Stream inStream) { }
	// RVA: 0x66e03b0 VA: 0x7598cf83b0
	internal Asn1Sequence ReadPemObject(Stream inStream) { }
}
```