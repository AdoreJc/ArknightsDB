# PasswordDeriveBytes

**Namespace:** `System.Security.Cryptography`


## Fields

- `Int32 _extraCount`

- `Int32 _prefix`

- `Int32 _iterations`

- `String _hashName`

- `HashAlgorithm _hash`


## Properties

- `String HashName`

- `Int32 IterationCount`


## Methods

- `String get_HashName()`

- `Void set_HashName(String)`

- `Int32 get_IterationCount()`

- `Void set_IterationCount(Int32)`

- `Void set_Salt(Byte[])`

- `Void HashPrefix(CryptoStream)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class PasswordDeriveBytes : DeriveBytes
{
	private Int32 _extraCount; // 0x10
	private Int32 _prefix; // 0x14
	private Int32 _iterations; // 0x18
	private Byte[] _baseValue; // 0x20
	private Byte[] _extra; // 0x28
	private Byte[] _salt; // 0x30
	private String _hashName; // 0x38
	private Byte[] _password; // 0x40
	private HashAlgorithm _hash; // 0x48

	public String HashName { get; set; }
	public Int32 IterationCount { get; set; }
	public Byte[] Salt { get; set; }

	// RVA: 0x5f55be4 VA: 0x759856dbe4
	public Void .ctor(String strPassword, Byte[] rgbSalt) { }
	// RVA: 0x5f55ce0 VA: 0x759856dce0
	public Void .ctor(Byte[] password, Byte[] salt) { }
	// RVA: 0x5f55dcc VA: 0x759856ddcc
	public Void .ctor(String strPassword, Byte[] rgbSalt, String strHashName, Int32 iterations) { }
	// RVA: 0x5f55f18 VA: 0x759856df18
	public Void .ctor(Byte[] password, Byte[] salt, String hashName, Int32 iterations) { }
	// RVA: 0x5f55c6c VA: 0x759856dc6c
	public Void .ctor(String strPassword, Byte[] rgbSalt, CspParameters cspParams) { }
	// RVA: 0x5f55d68 VA: 0x759856dd68
	public Void .ctor(Byte[] password, Byte[] salt, CspParameters cspParams) { }
	// RVA: 0x5f55e6c VA: 0x759856de6c
	public Void .ctor(String strPassword, Byte[] rgbSalt, String strHashName, Int32 iterations, CspParameters cspParams) { }
	// RVA: 0x5f55fb0 VA: 0x759856dfb0
	public Void .ctor(Byte[] password, Byte[] salt, String hashName, Int32 iterations, CspParameters cspParams) { }
	// RVA: 0x5f56458 VA: 0x759856e458
	public String get_HashName() { }
	// RVA: 0x5f562a8 VA: 0x759856e2a8
	public Void set_HashName(String value) { }
	// RVA: 0x5f56460 VA: 0x759856e460
	public Int32 get_IterationCount() { }
	// RVA: 0x5f56018 VA: 0x759856e018
	public Void set_IterationCount(Int32 value) { }
	// RVA: 0x5f56468 VA: 0x759856e468
	public Byte[] get_Salt() { }
	// RVA: 0x5f5613c VA: 0x759856e13c
	public Void set_Salt(Byte[] value) { }
	// RVA: 0x5f564dc VA: 0x759856e4dc
	public override Byte[] GetBytes(Int32 cb) { }
	// RVA: 0x5f56ce8 VA: 0x759856ece8
	public override Void Reset() { }
	// RVA: 0x5f56d14 VA: 0x759856ed14
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x5f56d9c VA: 0x759856ed9c
	public Byte[] CryptDeriveKey(String algname, String alghashname, Int32 keySize, Byte[] rgbIV) { }
	// RVA: 0x5f56690 VA: 0x759856e690
	private Byte[] ComputeBaseValue() { }
	// RVA: 0x5f56818 VA: 0x759856e818
	private Byte[] ComputeBytes(Int32 cb) { }
	// RVA: 0x5f56e48 VA: 0x759856ee48
	private Void HashPrefix(CryptoStream cs) { }
}
```