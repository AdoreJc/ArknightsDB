# VmpcEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Byte n`

- `Byte s`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class VmpcEngine : IStreamCipher
{
	protected Byte n; // 0x10
	protected Byte[] P; // 0x18
	protected Byte s; // 0x20
	protected Byte[] workingIV; // 0x28
	protected Byte[] workingKey; // 0x30

	public virtual String AlgorithmName { get; }

	// RVA: 0x656062c VA: 0x7598b7862c
	public virtual String get_AlgorithmName() { }
	// RVA: 0x656066c VA: 0x7598b7866c
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6560828 VA: 0x7598b78828
	protected virtual Void InitKey(Byte[] keyBytes, Byte[] ivBytes) { }
	// RVA: 0x6560a2c VA: 0x7598b78a2c
	public virtual Void ProcessBytes(Byte[] input, Int32 inOff, Int32 len, Byte[] output, Int32 outOff) { }
	// RVA: 0x6560bec VA: 0x7598b78bec
	public virtual Void Reset() { }
	// RVA: 0x6560bfc VA: 0x7598b78bfc
	public virtual Byte ReturnByte(Byte input) { }
	// RVA: 0x6560cc0 VA: 0x7598b78cc0
	public Void .ctor() { }
}
```