# EaxBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Fields

- `SicBlockCipher cipher`

- `Boolean forEncryption`

- `Int32 blockSize`

- `IMac mac`

- `Int32 macSize`

- `Int32 bufOff`

- `Boolean cipherInitialized`


## Methods

- `Void InitCipher()`

- `Void CalculateMac()`

- `Void Reset(Boolean)`

- `Int32 Process(Byte, Byte[], Int32)`

- `Boolean VerifyMac(Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class EaxBlockCipher : IAeadBlockCipher
{
	private SicBlockCipher cipher; // 0x10
	private Boolean forEncryption; // 0x18
	private Int32 blockSize; // 0x1c
	private IMac mac; // 0x20
	private Byte[] nonceMac; // 0x28
	private Byte[] associatedTextMac; // 0x30
	private Byte[] macBlock; // 0x38
	private Int32 macSize; // 0x40
	private Byte[] bufBlock; // 0x48
	private Int32 bufOff; // 0x50
	private Boolean cipherInitialized; // 0x54
	private Byte[] initialAssociatedText; // 0x58

	public virtual String AlgorithmName { get; }

	// RVA: 0x6524028 VA: 0x7598b3c028
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x65242b4 VA: 0x7598b3c2b4
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6524388 VA: 0x7598b3c388
	public virtual IBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x6524390 VA: 0x7598b3c390
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x65243b4 VA: 0x7598b3c3b4
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x652486c VA: 0x7598b3c86c
	private Void InitCipher() { }
	// RVA: 0x6524a04 VA: 0x7598b3ca04
	private Void CalculateMac() { }
	// RVA: 0x6524b5c VA: 0x7598b3cb5c
	public virtual Void Reset() { }
	// RVA: 0x6524b64 VA: 0x7598b3cb64
	private Void Reset(Boolean clearMac) { }
	// RVA: 0x6524d5c VA: 0x7598b3cd5c
	public virtual Void ProcessAadByte(Byte input) { }
	// RVA: 0x6524e5c VA: 0x7598b3ce5c
	public virtual Void ProcessAadBytes(Byte[] inBytes, Int32 inOff, Int32 len) { }
	// RVA: 0x6524f74 VA: 0x7598b3cf74
	public virtual Int32 ProcessByte(Byte input, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6525210 VA: 0x7598b3d210
	public virtual Int32 ProcessBytes(Byte[] inBytes, Int32 inOff, Int32 len, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x65252a4 VA: 0x7598b3d2a4
	public virtual Int32 DoFinal(Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6525688 VA: 0x7598b3d688
	public virtual Byte[] GetMac() { }
	// RVA: 0x65256fc VA: 0x7598b3d6fc
	public virtual Int32 GetUpdateOutputSize(Int32 len) { }
	// RVA: 0x6525730 VA: 0x7598b3d730
	public virtual Int32 GetOutputSize(Int32 len) { }
	// RVA: 0x6524fb4 VA: 0x7598b3cfb4
	private Int32 Process(Byte b, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x65255f4 VA: 0x7598b3d5f4
	private Boolean VerifyMac(Byte[] mac, Int32 off) { }
}
```