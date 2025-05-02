# CcmBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Fields

- `Boolean forEncryption`

- `Int32 macSize`

- `ICipherParameters keyParam`


## Methods

- `Int32 CalculateMac(Byte[], Int32, Int32, Byte[])`

- `Int32 GetAssociatedTextLength()`

- `Boolean HasAssociatedText()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class CcmBlockCipher : IAeadBlockCipher
{
	private static readonly Int32 BlockSize; // 0x0
	private readonly IBlockCipher cipher; // 0x10
	private readonly Byte[] macBlock; // 0x18
	private Boolean forEncryption; // 0x20
	private Byte[] nonce; // 0x28
	private Byte[] initialAssociatedText; // 0x30
	private Int32 macSize; // 0x38
	private ICipherParameters keyParam; // 0x40
	private readonly MemoryStream associatedText; // 0x48
	private readonly MemoryStream data; // 0x50

	public virtual String AlgorithmName { get; }

	// RVA: 0x6520cbc VA: 0x7598b38cbc
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x6520f14 VA: 0x7598b38f14
	public virtual IBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x6520f1c VA: 0x7598b38f1c
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6521150 VA: 0x7598b39150
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6521210 VA: 0x7598b39210
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x65212b4 VA: 0x7598b392b4
	public virtual Void ProcessAadByte(Byte input) { }
	// RVA: 0x65212d8 VA: 0x7598b392d8
	public virtual Void ProcessAadBytes(Byte[] inBytes, Int32 inOff, Int32 len) { }
	// RVA: 0x65212fc VA: 0x7598b392fc
	public virtual Int32 ProcessByte(Byte input, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6521328 VA: 0x7598b39328
	public virtual Int32 ProcessBytes(Byte[] inBytes, Int32 inOff, Int32 inLen, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x65213c8 VA: 0x7598b393c8
	public virtual Int32 DoFinal(Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x652146c VA: 0x7598b3946c
	public virtual Void Reset() { }
	// RVA: 0x6521548 VA: 0x7598b39548
	public virtual Byte[] GetMac() { }
	// RVA: 0x6521560 VA: 0x7598b39560
	public virtual Int32 GetUpdateOutputSize(Int32 len) { }
	// RVA: 0x6521568 VA: 0x7598b39568
	public virtual Int32 GetOutputSize(Int32 len) { }
	// RVA: 0x65215bc VA: 0x7598b395bc
	public virtual Byte[] ProcessPacket(Byte[] input, Int32 inOff, Int32 inLen) { }
	// RVA: 0x65216b8 VA: 0x7598b396b8
	public virtual Int32 ProcessPacket(Byte[] input, Int32 inOff, Int32 inLen, Byte[] output, Int32 outOff) { }
	// RVA: 0x6522080 VA: 0x7598b3a080
	private Int32 CalculateMac(Byte[] data, Int32 dataOff, Int32 dataLen, Byte[] macBlock) { }
	// RVA: 0x652292c VA: 0x7598b3a92c
	private Int32 GetAssociatedTextLength() { }
	// RVA: 0x6522914 VA: 0x7598b3a914
	private Boolean HasAssociatedText() { }
	// RVA: 0x6522964 VA: 0x7598b3a964
	private static Void .cctor() { }
}
```