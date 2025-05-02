# ParametersWithRandom

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `SecureRandom Random`

- `ICipherParameters Parameters`


## Methods

- `SecureRandom GetRandom()`

- `SecureRandom get_Random()`

- `ICipherParameters get_Parameters()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ParametersWithRandom : ICipherParameters
{
	private readonly ICipherParameters parameters; // 0x10
	private readonly SecureRandom random; // 0x18

	public SecureRandom Random { get; }
	public ICipherParameters Parameters { get; }

	// RVA: 0x6519e80 VA: 0x7598b31e80
	public Void .ctor(ICipherParameters parameters, SecureRandom random) { }
	// RVA: 0x6519f3c VA: 0x7598b31f3c
	public Void .ctor(ICipherParameters parameters) { }
	// RVA: 0x6519fb0 VA: 0x7598b31fb0
	public SecureRandom GetRandom() { }
	// RVA: 0x6519fb8 VA: 0x7598b31fb8
	public SecureRandom get_Random() { }
	// RVA: 0x6519fc0 VA: 0x7598b31fc0
	public ICipherParameters get_Parameters() { }
}
```