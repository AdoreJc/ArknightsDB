# MD2Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `Int32 xOff`

- `Int32 mOff`

- `Int32 COff`


## Properties

- `String AlgorithmName`


## Methods

- `Void CopyIn(MD2Digest)`

- `String get_AlgorithmName()`

- `Int32 GetDigestSize()`

- `Int32 GetByteLength()`

- `Int32 DoFinal(Byte[], Int32)`

- `Void Reset()`

- `Void Update(Byte)`

- `Void BlockUpdate(Byte[], Int32, Int32)`

- `IMemoable Copy()`

- `Void Reset(IMemoable)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class MD2Digest : IDigest, IMemoable
{
	private const Int32 DigestLength; // 0x0
	private const Int32 BYTE_LENGTH; // 0x0
	private Byte[] X; // 0x10
	private Int32 xOff; // 0x18
	private Byte[] M; // 0x20
	private Int32 mOff; // 0x28
	private Byte[] C; // 0x30
	private Int32 COff; // 0x38
	private static readonly Byte[] S; // 0x0

	public String AlgorithmName { get; }

	// RVA: 0x657c790 VA: 0x7598b94790
	public Void .ctor() { }
	// RVA: 0x657c8ec VA: 0x7598b948ec
	public Void .ctor(MD2Digest t) { }
	// RVA: 0x657c9a0 VA: 0x7598b949a0
	private Void CopyIn(MD2Digest t) { }
	// RVA: 0x657ca3c VA: 0x7598b94a3c
	public String get_AlgorithmName() { }
	// RVA: 0x657ca7c VA: 0x7598b94a7c
	public Int32 GetDigestSize() { }
	// RVA: 0x657ca84 VA: 0x7598b94a84
	public Int32 GetByteLength() { }
	// RVA: 0x657ca8c VA: 0x7598b94a8c
	public Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x657c834 VA: 0x7598b94834
	public Void Reset() { }
	// RVA: 0x657cddc VA: 0x7598b94ddc
	public Void Update(Byte input) { }
	// RVA: 0x657ce44 VA: 0x7598b94e44
	public Void BlockUpdate(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x657cb44 VA: 0x7598b94b44
	internal Void ProcessChecksum(Byte[] m) { }
	// RVA: 0x657cc5c VA: 0x7598b94c5c
	internal Void ProcessBlock(Byte[] m) { }
	// RVA: 0x657cf6c VA: 0x7598b94f6c
	public IMemoable Copy() { }
	// RVA: 0x657cfcc VA: 0x7598b94fcc
	public Void Reset(IMemoable other) { }
	// RVA: 0x657d050 VA: 0x7598b95050
	private static Void .cctor() { }
}
```