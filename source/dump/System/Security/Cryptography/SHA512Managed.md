# SHA512Managed

**Namespace:** `System.Security.Cryptography`


## Fields

- `UInt64 _count`


## Methods

- `Void InitializeState()`

- `Void _HashData(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class SHA512Managed : SHA512
{
	private Byte[] _buffer; // 0x28
	private UInt64 _count; // 0x30
	private UInt64[] _stateSHA512; // 0x38
	private UInt64[] _W; // 0x40
	private static readonly UInt64[] _K; // 0x0


	// RVA: 0x5f670b8 VA: 0x759857f0b8
	public Void .ctor() { }
	// RVA: 0x5f67344 VA: 0x759857f344
	public override Void Initialize() { }
	// RVA: 0x5f67388 VA: 0x759857f388
	protected override Void HashCore(Byte[] rgb, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f67558 VA: 0x759857f558
	protected override Byte[] HashFinal() { }
	// RVA: 0x5f67244 VA: 0x759857f244
	private Void InitializeState() { }
	// RVA: 0x5f6738c VA: 0x759857f38c
	private Void _HashData(Byte[] partIn, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f6755c VA: 0x759857f55c
	private Byte[] _EndHash() { }
	// RVA: 0x5f67734 VA: 0x759857f734
	private static Void SHATransform(UInt64* expandedBuffer, UInt64* state, Byte* block) { }
	// RVA: 0x5f67e3c VA: 0x759857fe3c
	private static UInt64 RotateRight(UInt64 x, Int32 n) { }
	// RVA: 0x5f67dbc VA: 0x759857fdbc
	private static UInt64 Ch(UInt64 x, UInt64 y, UInt64 z) { }
	// RVA: 0x5f67e28 VA: 0x759857fe28
	private static UInt64 Maj(UInt64 x, UInt64 y, UInt64 z) { }
	// RVA: 0x5f67dcc VA: 0x759857fdcc
	private static UInt64 Sigma_0(UInt64 x) { }
	// RVA: 0x5f67d60 VA: 0x759857fd60
	private static UInt64 Sigma_1(UInt64 x) { }
	// RVA: 0x5f67e44 VA: 0x759857fe44
	private static UInt64 sigma_0(UInt64 x) { }
	// RVA: 0x5f67ea0 VA: 0x759857fea0
	private static UInt64 sigma_1(UInt64 x) { }
	// RVA: 0x5f67cb8 VA: 0x759857fcb8
	private static Void SHA512Expand(UInt64* x) { }
	// RVA: 0x5f67efc VA: 0x759857fefc
	private static Void .cctor() { }
}
```