# OcbBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Fields

- `Boolean forEncryption`

- `Int32 macSize`

- `IList L`

- `Int32 hashBlockPos`

- `Int32 mainBlockPos`

- `Int64 hashBlockCount`

- `Int64 mainBlockCount`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class OcbBlockCipher : IAeadBlockCipher
{
	private const Int32 BLOCK_SIZE; // 0x0
	private readonly IBlockCipher hashCipher; // 0x10
	private readonly IBlockCipher mainCipher; // 0x18
	private Boolean forEncryption; // 0x20
	private Int32 macSize; // 0x24
	private Byte[] initialAssociatedText; // 0x28
	private IList L; // 0x30
	private Byte[] L_Asterisk; // 0x38
	private Byte[] L_Dollar; // 0x40
	private Byte[] KtopInput; // 0x48
	private Byte[] Stretch; // 0x50
	private Byte[] OffsetMAIN_0; // 0x58
	private Byte[] hashBlock; // 0x60
	private Byte[] mainBlock; // 0x68
	private Int32 hashBlockPos; // 0x70
	private Int32 mainBlockPos; // 0x74
	private Int64 hashBlockCount; // 0x78
	private Int64 mainBlockCount; // 0x80
	private Byte[] OffsetHASH; // 0x88
	private Byte[] Sum; // 0x90
	private Byte[] OffsetMAIN; // 0x98
	private Byte[] Checksum; // 0xa0
	private Byte[] macBlock; // 0xa8

	public virtual String AlgorithmName { get; }

	// RVA: 0x6527e18 VA: 0x7598b3fe18
	public Void .ctor(IBlockCipher hashCipher, IBlockCipher mainCipher) { }
	// RVA: 0x6528228 VA: 0x7598b40228
	public virtual IBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x6528230 VA: 0x7598b40230
	public virtual String get_AlgorithmName() { }
	// RVA: 0x65282f0 VA: 0x7598b402f0
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6528ae0 VA: 0x7598b40ae0
	protected virtual Int32 ProcessNonce(Byte[] N) { }
	// RVA: 0x6528d0c VA: 0x7598b40d0c
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x6528d14 VA: 0x7598b40d14
	public virtual Byte[] GetMac() { }
	// RVA: 0x6528d20 VA: 0x7598b40d20
	public virtual Int32 GetOutputSize(Int32 len) { }
	// RVA: 0x6528d48 VA: 0x7598b40d48
	public virtual Int32 GetUpdateOutputSize(Int32 len) { }
	// RVA: 0x6528d80 VA: 0x7598b40d80
	public virtual Void ProcessAadByte(Byte input) { }
	// RVA: 0x6528de8 VA: 0x7598b40de8
	public virtual Void ProcessAadBytes(Byte[] input, Int32 off, Int32 len) { }
	// RVA: 0x6528e9c VA: 0x7598b40e9c
	public virtual Int32 ProcessByte(Byte input, Byte[] output, Int32 outOff) { }
	// RVA: 0x6528f18 VA: 0x7598b40f18
	public virtual Int32 ProcessBytes(Byte[] input, Int32 inOff, Int32 len, Byte[] output, Int32 outOff) { }
	// RVA: 0x6528ff8 VA: 0x7598b40ff8
	public virtual Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x65294a0 VA: 0x7598b414a0
	public virtual Void Reset() { }
	// RVA: 0x65294b4 VA: 0x7598b414b4
	protected virtual Void Clear(Byte[] bs) { }
	// RVA: 0x65294d0 VA: 0x7598b414d0
	protected virtual Byte[] GetLSub(Int32 n) { }
	// RVA: 0x652979c VA: 0x7598b4179c
	protected virtual Void ProcessHashBlock() { }
	// RVA: 0x6529840 VA: 0x7598b41840
	protected virtual Void ProcessMainBlock(Byte[] output, Int32 outOff) { }
	// RVA: 0x6529a10 VA: 0x7598b41a10
	protected virtual Void Reset(Boolean clearMac) { }
	// RVA: 0x6529c08 VA: 0x7598b41c08
	protected virtual Void UpdateHASH(Byte[] LSub) { }
	// RVA: 0x6528a48 VA: 0x7598b40a48
	protected static Byte[] OCB_double(Byte[] block) { }
	// RVA: 0x65293e8 VA: 0x7598b413e8
	protected static Void OCB_extend(Byte[] block, Int32 pos) { }
	// RVA: 0x652980c VA: 0x7598b4180c
	protected static Int32 OCB_ntz(Int64 x) { }
	// RVA: 0x6529ce8 VA: 0x7598b41ce8
	protected static Int32 ShiftLeft(Byte[] block, Byte[] output) { }
	// RVA: 0x6529448 VA: 0x7598b41448
	protected static Void Xor(Byte[] block, Byte[] val) { }
}
```