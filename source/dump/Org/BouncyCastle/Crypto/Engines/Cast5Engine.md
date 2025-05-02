# Cast5Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Boolean _encrypting`

- `Int32 _rounds`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class Cast5Engine : IBlockCipher
{
	internal static readonly UInt32[] S1; // 0x0
	internal static readonly UInt32[] S2; // 0x8
	internal static readonly UInt32[] S3; // 0x10
	internal static readonly UInt32[] S4; // 0x18
	internal static readonly UInt32[] S5; // 0x20
	internal static readonly UInt32[] S6; // 0x28
	internal static readonly UInt32[] S7; // 0x30
	internal static readonly UInt32[] S8; // 0x38
	internal static readonly Int32 MAX_ROUNDS; // 0x40
	internal static readonly Int32 RED_ROUNDS; // 0x44
	private const Int32 BLOCK_SIZE; // 0x0
	private Int32[] _Kr; // 0x10
	private UInt32[] _Km; // 0x18
	private Boolean _encrypting; // 0x20
	private Byte[] _workingKey; // 0x28
	private Int32 _rounds; // 0x30

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x65400ec VA: 0x7598b580ec
	public Void .ctor() { }
	// RVA: 0x65401bc VA: 0x7598b581bc
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x654034c VA: 0x7598b5834c
	public virtual String get_AlgorithmName() { }
	// RVA: 0x654038c VA: 0x7598b5838c
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x6540394 VA: 0x7598b58394
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x6540500 VA: 0x7598b58500
	public virtual Void Reset() { }
	// RVA: 0x6540504 VA: 0x7598b58504
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x654050c VA: 0x7598b5850c
	internal virtual Void SetKey(Byte[] key) { }
	// RVA: 0x6543830 VA: 0x7598b5b830
	internal virtual Int32 EncryptBlock(Byte[] src, Int32 srcIndex, Byte[] dst, Int32 dstIndex) { }
	// RVA: 0x6543b48 VA: 0x7598b5bb48
	internal virtual Int32 DecryptBlock(Byte[] src, Int32 srcIndex, Byte[] dst, Int32 dstIndex) { }
	// RVA: 0x6543e88 VA: 0x7598b5be88
	internal static UInt32 F1(UInt32 D, UInt32 Kmi, Int32 Kri) { }
	// RVA: 0x6543f90 VA: 0x7598b5bf90
	internal static UInt32 F2(UInt32 D, UInt32 Kmi, Int32 Kri) { }
	// RVA: 0x6544098 VA: 0x7598b5c098
	internal static UInt32 F3(UInt32 D, UInt32 Kmi, Int32 Kri) { }
	// RVA: 0x654392c VA: 0x7598b5b92c
	internal Void CAST_Encipher(UInt32 L0, UInt32 R0, UInt32[] result) { }
	// RVA: 0x6543c44 VA: 0x7598b5bc44
	internal Void CAST_Decipher(UInt32 L16, UInt32 R16, UInt32[] result) { }
	// RVA: 0x65437b8 VA: 0x7598b5b7b8
	internal static Void Bits32ToInts(UInt32 inData, Int32[] b, Int32 offset) { }
	// RVA: 0x6543740 VA: 0x7598b5b740
	internal static UInt32 IntsTo32bits(Int32[] b, Int32 i) { }
	// RVA: 0x65441a0 VA: 0x7598b5c1a0
	private static Void .cctor() { }
}
```