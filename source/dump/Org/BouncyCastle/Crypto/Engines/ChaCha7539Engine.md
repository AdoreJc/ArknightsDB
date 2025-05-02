# ChaCha7539Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class ChaCha7539Engine : Salsa20Engine
{

	public override String AlgorithmName { get; }
	protected override Int32 NonceSize { get; }

	// RVA: 0x654581c VA: 0x7598b5d81c
	public Void .ctor() { }
	// RVA: 0x6545874 VA: 0x7598b5d874
	public override String get_AlgorithmName() { }
	// RVA: 0x65458d0 VA: 0x7598b5d8d0
	protected override Int32 get_NonceSize() { }
	// RVA: 0x65458d8 VA: 0x7598b5d8d8
	protected override Void AdvanceCounter() { }
	// RVA: 0x654595c VA: 0x7598b5d95c
	protected override Void ResetCounter() { }
	// RVA: 0x6545988 VA: 0x7598b5d988
	protected override Void SetKey(Byte[] keyBytes, Byte[] ivBytes) { }
	// RVA: 0x6545a78 VA: 0x7598b5da78
	protected override Void GenerateKeyStream(Byte[] output) { }
}
```