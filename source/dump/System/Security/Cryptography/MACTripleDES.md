# MACTripleDES

**Namespace:** `System.Security.Cryptography`


## Fields

- `ICryptoTransform m_encryptor`

- `CryptoStream _cs`

- `TailStream _ts`

- `Int32 m_bytesPerBlock`

- `TripleDES des`


## Properties

- `PaddingMode Padding`


## Methods

- `PaddingMode get_Padding()`

- `Void set_Padding(PaddingMode)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class MACTripleDES : KeyedHashAlgorithm
{
	private ICryptoTransform m_encryptor; // 0x30
	private CryptoStream _cs; // 0x38
	private TailStream _ts; // 0x40
	private const Int32 m_bitsPerByte; // 0x0
	private Int32 m_bytesPerBlock; // 0x48
	private TripleDES des; // 0x50

	public PaddingMode Padding { get; set; }

	// RVA: 0x5f54c60 VA: 0x759856cc60
	public Void .ctor() { }
	// RVA: 0x5f54de8 VA: 0x759856cde8
	public Void .ctor(Byte[] rgbKey) { }
	// RVA: 0x5f54e40 VA: 0x759856ce40
	public Void .ctor(String strTripleDES, Byte[] rgbKey) { }
	// RVA: 0x5f55044 VA: 0x759856d044
	public override Void Initialize() { }
	// RVA: 0x5f55050 VA: 0x759856d050
	public PaddingMode get_Padding() { }
	// RVA: 0x5f55074 VA: 0x759856d074
	public Void set_Padding(PaddingMode value) { }
	// RVA: 0x5f55100 VA: 0x759856d100
	protected override Void HashCore(Byte[] rgbData, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5f55330 VA: 0x759856d330
	protected override Byte[] HashFinal() { }
	// RVA: 0x5f55518 VA: 0x759856d518
	protected override Void Dispose(Boolean disposing) { }
}
```