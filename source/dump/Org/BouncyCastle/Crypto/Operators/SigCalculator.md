# SigCalculator

**Namespace:** `Org.BouncyCastle.Crypto.Operators`


## Properties

- `Stream Stream`


## Methods

- `Stream get_Stream()`

- `Object GetResult()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Operators
internal class SigCalculator : IStreamCalculator
{
	private readonly ISigner sig; // 0x10
	private readonly Stream stream; // 0x18

	public Stream Stream { get; }

	// RVA: 0x651faa0 VA: 0x7598b37aa0
	internal Void .ctor(ISigner sig) { }
	// RVA: 0x651fb7c VA: 0x7598b37b7c
	public Stream get_Stream() { }
	// RVA: 0x651fb84 VA: 0x7598b37b84
	public Object GetResult() { }
}
```