# SHA384Managed

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
public class SHA384Managed : SHA384
{
	private Byte[] _buffer; // 0x28
	private UInt64 _count; // 0x30
	private UInt64[] _stateSHA384; // 0x38
	private UInt64[] _W; // 0x40
	private static readonly UInt64[] _K; // 0x0


	// RVA: 0x5f65f78 VA: 0x759857df78
	public Void .ctor() { }
	// RVA: 0x5f66204 VA: 0x759857e204
	public override Void Initialize() { }
	// RVA: 0x5f66248 VA: 0x759857e248
	protected override Void HashCore(Byte[] rgb, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f66418 VA: 0x759857e418
	protected override Byte[] HashFinal() { }
	// RVA: 0x5f66104 VA: 0x759857e104
	private Void InitializeState() { }
	// RVA: 0x5f6624c VA: 0x759857e24c
	private Void _HashData(Byte[] partIn, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f6641c VA: 0x759857e41c
	private Byte[] _EndHash() { }
	// RVA: 0x5f665f4 VA: 0x759857e5f4
	private static Void SHATransform(UInt64* expandedBuffer, UInt64* state, Byte* block) { }
	// RVA: 0x5f66f38 VA: 0x759857ef38
	private static UInt64 RotateRight(UInt64 x, Int32 n) { }
	// RVA: 0x5f66eb8 VA: 0x759857eeb8
	private static UInt64 Ch(UInt64 x, UInt64 y, UInt64 z) { }
	// RVA: 0x5f66f24 VA: 0x759857ef24
	private static UInt64 Maj(UInt64 x, UInt64 y, UInt64 z) { }
	// RVA: 0x5f66ec8 VA: 0x759857eec8
	private static UInt64 Sigma_0(UInt64 x) { }
	// RVA: 0x5f66e5c VA: 0x759857ee5c
	private static UInt64 Sigma_1(UInt64 x) { }
	// RVA: 0x5f66f40 VA: 0x759857ef40
	private static UInt64 sigma_0(UInt64 x) { }
	// RVA: 0x5f66f9c VA: 0x759857ef9c
	private static UInt64 sigma_1(UInt64 x) { }
	// RVA: 0x5f66db4 VA: 0x759857edb4
	private static Void SHA384Expand(UInt64* x) { }
	// RVA: 0x5f66ff8 VA: 0x759857eff8
	private static Void .cctor() { }
}
```