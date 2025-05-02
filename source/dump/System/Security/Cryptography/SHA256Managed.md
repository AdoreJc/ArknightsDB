# SHA256Managed

**Namespace:** `System.Security.Cryptography`


## Fields

- `Int64 _count`


## Methods

- `Void InitializeState()`

- `Void _HashData(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class SHA256Managed : SHA256
{
	private Byte[] _buffer; // 0x28
	private Int64 _count; // 0x30
	private UInt32[] _stateSHA256; // 0x38
	private UInt32[] _W; // 0x40
	private static readonly UInt32[] _K; // 0x0


	// RVA: 0x5f650ac VA: 0x759857d0ac
	public Void .ctor() { }
	// RVA: 0x5f652f8 VA: 0x759857d2f8
	public override Void Initialize() { }
	// RVA: 0x5f6533c VA: 0x759857d33c
	protected override Void HashCore(Byte[] rgb, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f6550c VA: 0x759857d50c
	protected override Byte[] HashFinal() { }
	// RVA: 0x5f65238 VA: 0x759857d238
	private Void InitializeState() { }
	// RVA: 0x5f65340 VA: 0x759857d340
	private Void _HashData(Byte[] partIn, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f65510 VA: 0x759857d510
	private Byte[] _EndHash() { }
	// RVA: 0x5f656e8 VA: 0x759857d6e8
	private static Void SHATransform(UInt32* expandedBuffer, UInt32* state, Byte* block) { }
	// RVA: 0x5f65df8 VA: 0x759857ddf8
	private static UInt32 RotateRight(UInt32 x, Int32 n) { }
	// RVA: 0x5f65d78 VA: 0x759857dd78
	private static UInt32 Ch(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x5f65de4 VA: 0x759857dde4
	private static UInt32 Maj(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x5f65e00 VA: 0x759857de00
	private static UInt32 sigma_0(UInt32 x) { }
	// RVA: 0x5f65e5c VA: 0x759857de5c
	private static UInt32 sigma_1(UInt32 x) { }
	// RVA: 0x5f65d88 VA: 0x759857dd88
	private static UInt32 Sigma_0(UInt32 x) { }
	// RVA: 0x5f65d1c VA: 0x759857dd1c
	private static UInt32 Sigma_1(UInt32 x) { }
	// RVA: 0x5f65c74 VA: 0x759857dc74
	private static Void SHA256Expand(UInt32* x) { }
	// RVA: 0x5f65eb8 VA: 0x759857deb8
	private static Void .cctor() { }
}
```