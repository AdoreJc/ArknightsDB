# Rfc2898DeriveBytes

**Namespace:** `System.Security.Cryptography`


## Fields

- `UInt32 _iterations`

- `HMAC _hmac`

- `Int32 _blockSize`

- `UInt32 _block`

- `Int32 _startIndex`

- `Int32 _endIndex`


## Properties

- `HashAlgorithmName HashAlgorithm`

- `Int32 IterationCount`


## Methods

- `HashAlgorithmName get_HashAlgorithm()`

- `Int32 get_IterationCount()`

- `Void set_IterationCount(Int32)`

- `Void set_Salt(Byte[])`

- `HMAC OpenHmac()`

- `Void Initialize()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class Rfc2898DeriveBytes : DeriveBytes
{
	private const Int32 MinimumSaltSize; // 0x0
	private readonly Byte[] _password; // 0x10
	private Byte[] _salt; // 0x18
	private UInt32 _iterations; // 0x20
	private HMAC _hmac; // 0x28
	private Int32 _blockSize; // 0x30
	private Byte[] _buffer; // 0x38
	private UInt32 _block; // 0x40
	private Int32 _startIndex; // 0x44
	private Int32 _endIndex; // 0x48
	private readonly HashAlgorithmName <HashAlgorithm>k__BackingField; // 0x50

	public HashAlgorithmName HashAlgorithm { get; }
	public Int32 IterationCount { get; set; }
	public Byte[] Salt { get; set; }

	// RVA: 0x5f46048 VA: 0x759855e048
	public HashAlgorithmName get_HashAlgorithm() { }
	// RVA: 0x5f46050 VA: 0x759855e050
	public Void .ctor(Byte[] password, Byte[] salt, Int32 iterations) { }
	// RVA: 0x5f46098 VA: 0x759855e098
	public Void .ctor(Byte[] password, Byte[] salt, Int32 iterations, HashAlgorithmName hashAlgorithm) { }
	// RVA: 0x5f46548 VA: 0x759855e548
	public Void .ctor(String password, Byte[] salt) { }
	// RVA: 0x5f46584 VA: 0x759855e584
	public Void .ctor(String password, Byte[] salt, Int32 iterations) { }
	// RVA: 0x5f465cc VA: 0x759855e5cc
	public Void .ctor(String password, Byte[] salt, Int32 iterations, HashAlgorithmName hashAlgorithm) { }
	// RVA: 0x5f46630 VA: 0x759855e630
	public Void .ctor(String password, Int32 saltSize) { }
	// RVA: 0x5f4666c VA: 0x759855e66c
	public Void .ctor(String password, Int32 saltSize, Int32 iterations) { }
	// RVA: 0x5f466b4 VA: 0x759855e6b4
	public Void .ctor(String password, Int32 saltSize, Int32 iterations, HashAlgorithmName hashAlgorithm) { }
	// RVA: 0x5f46880 VA: 0x759855e880
	public Int32 get_IterationCount() { }
	// RVA: 0x5f46888 VA: 0x759855e888
	public Void set_IterationCount(Int32 value) { }
	// RVA: 0x5f46908 VA: 0x759855e908
	public Byte[] get_Salt() { }
	// RVA: 0x5f46914 VA: 0x759855e914
	public Void set_Salt(Byte[] value) { }
	// RVA: 0x5f469d8 VA: 0x759855e9d8
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x5f46adc VA: 0x759855eadc
	public override Byte[] GetBytes(Int32 cb) { }
	// RVA: 0x5f47160 VA: 0x759855f160
	public Byte[] CryptDeriveKey(String algname, String alghashname, Int32 keySize, Byte[] rgbIV) { }
	// RVA: 0x5f471a0 VA: 0x759855f1a0
	public override Void Reset() { }
	// RVA: 0x5f46284 VA: 0x759855e284
	private HMAC OpenHmac() { }
	// RVA: 0x5f464c0 VA: 0x759855e4c0
	private Void Initialize() { }
	// RVA: 0x5f46ca4 VA: 0x759855eca4
	private Byte[] Func() { }
}
```