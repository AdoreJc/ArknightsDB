# ChaChaEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class ChaChaEngine : Salsa20Engine
{

	public override String AlgorithmName { get; }

	// RVA: 0x654614c VA: 0x7598b5e14c
	public Void .ctor() { }
	// RVA: 0x65461a4 VA: 0x7598b5e1a4
	public Void .ctor(Int32 rounds) { }
	// RVA: 0x654620c VA: 0x7598b5e20c
	public override String get_AlgorithmName() { }
	// RVA: 0x6546268 VA: 0x7598b5e268
	protected override Void AdvanceCounter() { }
	// RVA: 0x65462b4 VA: 0x7598b5e2b4
	protected override Void ResetCounter() { }
	// RVA: 0x65462e0 VA: 0x7598b5e2e0
	protected override Void SetKey(Byte[] keyBytes, Byte[] ivBytes) { }
	// RVA: 0x65463f4 VA: 0x7598b5e3f4
	protected override Void GenerateKeyStream(Byte[] output) { }
	// RVA: 0x6545ab4 VA: 0x7598b5dab4
	internal static Void ChachaCore(Int32 rounds, UInt32[] input, UInt32[] x) { }
}
```