# CrypticConverter_B

**Namespace:** `Torappu.DB`


## Fields

- `UInt32 m_seed`

- `FastRandom random`


## Properties

- `UInt32 seed`


## Methods

- `Void set_seed(UInt32)`

- `UInt32 get_seed()`

- `UInt32 _Rand()`

- `UInt32 _Crypt(UInt32, UInt32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB
public class CrypticConverter_B : CrypticConverter
{
	private const UInt64 MOD; // 0x0
	private const String SEED_HASH_STR; // 0x0
	private UInt32 m_seed; // 0x20
	private FastRandom random; // 0x28

	public UInt32 seed { get; set; }

	// RVA: 0x3719748 VA: 0x7595d31748
	public Void set_seed(UInt32 value) { }
	// RVA: 0x37197c4 VA: 0x7595d317c4
	public UInt32 get_seed() { }
	// RVA: 0x37178a0 VA: 0x7595d2f8a0
	public Void .ctor() { }
	// RVA: 0x37197cc VA: 0x7595d317cc
	protected override Byte[] EncodeInternal(Byte[] src) { }
	// RVA: 0x3719b2c VA: 0x7595d31b2c
	protected override Void DecodeInternal(Stream src, Stream dst) { }
	// RVA: 0x3719ae0 VA: 0x7595d31ae0
	private UInt32 _Rand() { }
	// RVA: 0x3719b04 VA: 0x7595d31b04
	private UInt32 _Crypt(UInt32 word, UInt32 key) { }
}
```