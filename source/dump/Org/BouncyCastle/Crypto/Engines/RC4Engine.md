# RC4Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Int32 x`

- `Int32 y`


## Methods

- `Void SetKey(Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class RC4Engine : IStreamCipher
{
	private static readonly Int32 STATE_LENGTH; // 0x0
	private Byte[] engineState; // 0x10
	private Int32 x; // 0x18
	private Int32 y; // 0x1c
	private Byte[] workingKey; // 0x20

	public virtual String AlgorithmName { get; }

	// RVA: 0x65505e0 VA: 0x7598b685e0
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x65508bc VA: 0x7598b688bc
	public virtual String get_AlgorithmName() { }
	// RVA: 0x65508fc VA: 0x7598b688fc
	public virtual Byte ReturnByte(Byte input) { }
	// RVA: 0x65509d0 VA: 0x7598b689d0
	public virtual Void ProcessBytes(Byte[] input, Int32 inOff, Int32 length, Byte[] output, Int32 outOff) { }
	// RVA: 0x6550ba4 VA: 0x7598b68ba4
	public virtual Void Reset() { }
	// RVA: 0x65506f8 VA: 0x7598b686f8
	private Void SetKey(Byte[] keyBytes) { }
	// RVA: 0x6550bac VA: 0x7598b68bac
	public Void .ctor() { }
	// RVA: 0x6550bb4 VA: 0x7598b68bb4
	private static Void .cctor() { }
}
```