# DesEdeEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Boolean forEncryption`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class DesEdeEngine : DesEngine
{
	private Int32[] workingKey1; // 0x18
	private Int32[] workingKey2; // 0x20
	private Int32[] workingKey3; // 0x28
	private Boolean forEncryption; // 0x30

	public override String AlgorithmName { get; }

	// RVA: 0x6546430 VA: 0x7598b5e430
	public override Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6546c44 VA: 0x7598b5ec44
	public override String get_AlgorithmName() { }
	// RVA: 0x6546c84 VA: 0x7598b5ec84
	public override Int32 GetBlockSize() { }
	// RVA: 0x6546c8c VA: 0x7598b5ec8c
	public override Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x65472b0 VA: 0x7598b5f2b0
	public override Void Reset() { }
	// RVA: 0x65472b4 VA: 0x7598b5f2b4
	public Void .ctor() { }
}
```