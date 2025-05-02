# SHA1Internal

**Namespace:** `System.Security.Cryptography`


## Fields

- `UInt64 count`

- `Int32 _ProcessingBufferCount`


## Methods

- `Void HashCore(Byte[], Int32, Int32)`

- `Void Initialize()`

- `Void ProcessBlock(Byte[], UInt32)`

- `Void ProcessFinalBlock(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
internal class SHA1Internal
{
	private const Int32 BLOCK_SIZE_BYTES; // 0x0
	private UInt32[] _H; // 0x10
	private UInt64 count; // 0x18
	private Byte[] _ProcessingBuffer; // 0x20
	private Int32 _ProcessingBufferCount; // 0x28
	private UInt32[] buff; // 0x30


	// RVA: 0x5f7492c VA: 0x759858c92c
	public Void .ctor() { }
	// RVA: 0x5f74a74 VA: 0x759858ca74
	public Void HashCore(Byte[] rgb, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f7508c VA: 0x759858d08c
	public Byte[] HashFinal() { }
	// RVA: 0x5f749ec VA: 0x759858c9ec
	public Void Initialize() { }
	// RVA: 0x5f74b74 VA: 0x759858cb74
	private Void ProcessBlock(Byte[] inputBuffer, UInt32 inputOffset) { }
	// RVA: 0x5f75320 VA: 0x759858d320
	private static Void InitialiseBuff(UInt32[] buff, Byte[] input, UInt32 inputOffset) { }
	// RVA: 0x5f759c0 VA: 0x759858d9c0
	private static Void FillBuff(UInt32[] buff) { }
	// RVA: 0x5f75164 VA: 0x759858d164
	private Void ProcessFinalBlock(Byte[] inputBuffer, Int32 inputOffset, Int32 inputCount) { }
	// RVA: 0x5f75bf4 VA: 0x759858dbf4
	internal Void AddLength(UInt64 length, Byte[] buffer, Int32 position) { }
}
```