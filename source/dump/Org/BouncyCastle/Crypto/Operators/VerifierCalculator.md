# VerifierCalculator

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
internal class VerifierCalculator : IStreamCalculator
{
	private readonly ISigner sig; // 0x10
	private readonly Stream stream; // 0x18

	public Stream Stream { get; }

	// RVA: 0x651ff4c VA: 0x7598b37f4c
	internal Void .ctor(ISigner sig) { }
	// RVA: 0x651ffdc VA: 0x7598b37fdc
	public Stream get_Stream() { }
	// RVA: 0x651ffe4 VA: 0x7598b37fe4
	public Object GetResult() { }
}
```