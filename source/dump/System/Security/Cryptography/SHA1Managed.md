# SHA1Managed

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
public class SHA1Managed : SHA1
{
	private Byte[] _buffer; // 0x28
	private Int64 _count; // 0x30
	private UInt32[] _stateSHA1; // 0x38
	private UInt32[] _expandedBuffer; // 0x40


	// RVA: 0x5f645c0 VA: 0x759857c5c0
	public Void .ctor() { }
	// RVA: 0x5f64738 VA: 0x759857c738
	public override Void Initialize() { }
	// RVA: 0x5f6477c VA: 0x759857c77c
	protected override Void HashCore(Byte[] rgb, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f648fc VA: 0x759857c8fc
	protected override Byte[] HashFinal() { }
	// RVA: 0x5f646b4 VA: 0x759857c6b4
	private Void InitializeState() { }
	// RVA: 0x5f64780 VA: 0x759857c780
	private Void _HashData(Byte[] partIn, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f64900 VA: 0x759857c900
	private Byte[] _EndHash() { }
	// RVA: 0x5f64ad8 VA: 0x759857cad8
	private static Void SHATransform(UInt32* expandedBuffer, UInt32* state, Byte* block) { }
	// RVA: 0x5f65050 VA: 0x759857d050
	private static Void SHAExpand(UInt32* x) { }
}
```