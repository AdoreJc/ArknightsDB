# ParametersWithSalt

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
public class ParametersWithSalt : ICipherParameters
{
	private Byte[] salt; // 0x10
	private ICipherParameters parameters; // 0x18

	public ICipherParameters Parameters { get; }

	// RVA: 0x6519fc8 VA: 0x7598b31fc8
	public Void .ctor(ICipherParameters parameters, Byte[] salt) { }
	// RVA: 0x6519fe4 VA: 0x7598b31fe4
	public Void .ctor(ICipherParameters parameters, Byte[] salt, Int32 saltOff, Int32 saltLen) { }
	// RVA: 0x651a098 VA: 0x7598b32098
	public Byte[] GetSalt() { }
	// RVA: 0x651a0a0 VA: 0x7598b320a0
	public ICipherParameters get_Parameters() { }
}
```