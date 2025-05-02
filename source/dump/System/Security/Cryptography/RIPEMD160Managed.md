# RIPEMD160Managed

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
public class RIPEMD160Managed : RIPEMD160
{
	private Byte[] _buffer; // 0x28
	private Int64 _count; // 0x30
	private UInt32[] _stateMD160; // 0x38
	private UInt32[] _blockDWords; // 0x40


	// RVA: 0x5f542a4 VA: 0x759856c2a4
	public Void .ctor() { }
	// RVA: 0x5f5bf2c VA: 0x7598573f2c
	public override Void Initialize() { }
	// RVA: 0x5f5bf70 VA: 0x7598573f70
	protected override Void HashCore(Byte[] rgb, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f5c0f0 VA: 0x75985740f0
	protected override Byte[] HashFinal() { }
	// RVA: 0x5f5bea8 VA: 0x7598573ea8
	private Void InitializeState() { }
	// RVA: 0x5f5bf74 VA: 0x7598573f74
	private Void _HashData(Byte[] partIn, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f5c0f4 VA: 0x75985740f4
	private Byte[] _EndHash() { }
	// RVA: 0x5f5c2d0 VA: 0x75985742d0
	private static Void MDTransform(UInt32* blockDWords, UInt32* state, Byte* block) { }
	// RVA: 0x5f5da10 VA: 0x7598575a10
	private static UInt32 F(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x5f5da1c VA: 0x7598575a1c
	private static UInt32 G(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x5f5da2c VA: 0x7598575a2c
	private static UInt32 H(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x5f5da38 VA: 0x7598575a38
	private static UInt32 I(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x5f5da48 VA: 0x7598575a48
	private static UInt32 J(UInt32 x, UInt32 y, UInt32 z) { }
}
```