# NullDigest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Properties

- `String AlgorithmName`


## Methods

- `String get_AlgorithmName()`

- `Int32 GetByteLength()`

- `Int32 GetDigestSize()`

- `Void Update(Byte)`

- `Void BlockUpdate(Byte[], Int32, Int32)`

- `Int32 DoFinal(Byte[], Int32)`

- `Void Reset()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class NullDigest : IDigest
{
	private readonly MemoryStream bOut; // 0x10

	public String AlgorithmName { get; }

	// RVA: 0x657ed14 VA: 0x7598b96d14
	public String get_AlgorithmName() { }
	// RVA: 0x657ed54 VA: 0x7598b96d54
	public Int32 GetByteLength() { }
	// RVA: 0x657ed5c VA: 0x7598b96d5c
	public Int32 GetDigestSize() { }
	// RVA: 0x657ed80 VA: 0x7598b96d80
	public Void Update(Byte b) { }
	// RVA: 0x657eda4 VA: 0x7598b96da4
	public Void BlockUpdate(Byte[] inBytes, Int32 inOff, Int32 len) { }
	// RVA: 0x657edc8 VA: 0x7598b96dc8
	public Int32 DoFinal(Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x657ee44 VA: 0x7598b96e44
	public Void Reset() { }
	// RVA: 0x657ee6c VA: 0x7598b96e6c
	public Void .ctor() { }
}
```