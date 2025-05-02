# HashCodeBuilder

**Namespace:** `Torappu`


## Fields

- `UInt32 m_curHash`


## Methods

- `Void Clear()`

- `UInt32 GetCombinedHash()`

- `Void Append(String)`

- `Void Append(Int32)`

- `Void Append(UInt32)`

- `Void Append(Int64)`

- `Void Append(UInt64)`

- `Void Append(Char)`

- `Void Append(Byte)`

- `Void Append(Single)`

- `Void Append(Vector2)`

- `Void Append(Vector3)`

- `Void Append(GridPosition)`

- `Void _AppendNextHash(UInt32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class HashCodeBuilder
{
	private const Single FLOAT_MULTIPLIER; // 0x0
	private UInt32 m_curHash; // 0x10


	// RVA: 0x2f480ec VA: 0x75955600ec
	public Void Clear() { }
	// RVA: 0x2f480f4 VA: 0x75955600f4
	public UInt32 GetCombinedHash() { }
	// RVA: 0x2f480fc VA: 0x75955600fc
	public Void Append(String value) { }
	// RVA: 0x2f481e0 VA: 0x75955601e0
	public Void Append(Int32 value) { }
	// RVA: 0x2f48204 VA: 0x7595560204
	public Void Append(UInt32 value) { }
	// RVA: 0x2f48228 VA: 0x7595560228
	public Void Append(Int64 value) { }
	// RVA: 0x2f48260 VA: 0x7595560260
	public Void Append(UInt64 value) { }
	// RVA: 0x2f48298 VA: 0x7595560298
	public Void Append(Char value) { }
	// RVA: 0x2f482c0 VA: 0x75955602c0
	public Void Append(Byte value) { }
	// RVA: 0x2f482e8 VA: 0x75955602e8
	public Void Append(Single value) { }
	// RVA: 0x2f483f8 VA: 0x75955603f8
	public Void Append(Vector2 pos) { }
	// RVA: 0x2f48420 VA: 0x7595560420
	public Void Append(Vector3 pos) { }
	// RVA: 0x2f48458 VA: 0x7595560458
	public Void Append(GridPosition pos) { }
	// RVA: 0x2f481bc VA: 0x75955601bc
	private Void _AppendNextHash(UInt32 value) { }
	// RVA: 0x2f48490 VA: 0x7595560490
	private static UInt32 _CombineHash(UInt32 seed, UInt32 append) { }
	// RVA: 0x2f48134 VA: 0x7595560134
	private static UInt32 _ComputeELFHash(String chars) { }
	// RVA: 0x2f484ac VA: 0x75955604ac
	public Void .ctor() { }
}
```