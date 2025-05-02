# ParametersWithSBox

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Fields

- `ICipherParameters parameters`


## Properties

- `ICipherParameters Parameters`


## Methods

- `ICipherParameters get_Parameters()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ParametersWithSBox : ICipherParameters
{
	private ICipherParameters parameters; // 0x10
	private Byte[] sBox; // 0x18

	public ICipherParameters Parameters { get; }

	// RVA: 0x651a0a8 VA: 0x7598b320a8
	public Void .ctor(ICipherParameters parameters, Byte[] sBox) { }
	// RVA: 0x651a0ec VA: 0x7598b320ec
	public Byte[] GetSBox() { }
	// RVA: 0x651a0f4 VA: 0x7598b320f4
	public ICipherParameters get_Parameters() { }
}
```