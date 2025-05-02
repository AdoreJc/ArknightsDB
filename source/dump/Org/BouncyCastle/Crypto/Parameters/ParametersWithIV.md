# ParametersWithIV

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `ICipherParameters Parameters`


## Methods

- `ICipherParameters get_Parameters()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ParametersWithIV : ICipherParameters
{
	private readonly ICipherParameters parameters; // 0x10
	private readonly Byte[] iv; // 0x18

	public ICipherParameters Parameters { get; }

	// RVA: 0x6519ce4 VA: 0x7598b31ce4
	public Void .ctor(ICipherParameters parameters, Byte[] iv) { }
	// RVA: 0x6519d00 VA: 0x7598b31d00
	public Void .ctor(ICipherParameters parameters, Byte[] iv, Int32 ivOff, Int32 ivLen) { }
	// RVA: 0x6519e00 VA: 0x7598b31e00
	public Byte[] GetIV() { }
	// RVA: 0x6519e78 VA: 0x7598b31e78
	public ICipherParameters get_Parameters() { }
}
```