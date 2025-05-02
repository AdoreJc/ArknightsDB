# PemReader

**Namespace:** `Org.BouncyCastle.Utilities.IO.Pem`


## Properties

- `TextReader Reader`


## Methods

- `TextReader get_Reader()`

- `PemObject ReadPemObject()`

- `PemObject LoadObject(String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.IO.Pem
public class PemReader
{
	private const String BeginString; // 0x0
	private const String EndString; // 0x0
	private readonly TextReader reader; // 0x10

	public TextReader Reader { get; }

	// RVA: 0x66f7c1c VA: 0x7598d0fc1c
	public Void .ctor(TextReader reader) { }
	// RVA: 0x66f7c9c VA: 0x7598d0fc9c
	public TextReader get_Reader() { }
	// RVA: 0x66f7ca4 VA: 0x7598d0fca4
	public PemObject ReadPemObject() { }
	// RVA: 0x66f7da4 VA: 0x7598d0fda4
	private PemObject LoadObject(String type) { }
}
```