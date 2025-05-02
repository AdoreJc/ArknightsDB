# SortKeyBuffer

**Namespace:** `Mono.Globalization.Unicode`


## Fields

- `String source`

- `Int32 l1`

- `Int32 l2`

- `Int32 l3`

- `Int32 l4s`

- `Int32 l4t`

- `Int32 l4k`

- `Int32 l4w`

- `Int32 l5`

- `Int32 lcid`

- `CompareOptions options`

- `Boolean processLevel2`

- `Boolean frenchSort`

- `Boolean frenchSorted`


## Methods

- `Void Reset()`

- `Void AppendLevel5(Byte, Byte)`

- `Void AppendBufferPrimitive(Byte, ref, ref)`

- `SortKey GetResultAndReset()`

- `Int32 GetOptimizedLength(Byte[], Int32, Byte)`

- `SortKey GetResult()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : Mono.Globalization.Unicode
internal class SortKeyBuffer
{
	private Byte[] l1b; // 0x10
	private Byte[] l2b; // 0x18
	private Byte[] l3b; // 0x20
	private Byte[] l4sb; // 0x28
	private Byte[] l4tb; // 0x30
	private Byte[] l4kb; // 0x38
	private Byte[] l4wb; // 0x40
	private Byte[] l5b; // 0x48
	private String source; // 0x50
	private Int32 l1; // 0x58
	private Int32 l2; // 0x5c
	private Int32 l3; // 0x60
	private Int32 l4s; // 0x64
	private Int32 l4t; // 0x68
	private Int32 l4k; // 0x6c
	private Int32 l4w; // 0x70
	private Int32 l5; // 0x74
	private Int32 lcid; // 0x78
	private CompareOptions options; // 0x7c
	private Boolean processLevel2; // 0x80
	private Boolean frenchSort; // 0x81
	private Boolean frenchSorted; // 0x82


	// RVA: 0x5efeffc VA: 0x7598516ffc
	public Void .ctor(Int32 lcid) { }
	// RVA: 0x5f032d4 VA: 0x759851b2d4
	public Void Reset() { }
	// RVA: 0x5eff004 VA: 0x7598517004
	internal Void Initialize(CompareOptions options, Int32 lcid, String s, Boolean frenchSort) { }
	// RVA: 0x5effad4 VA: 0x7598517ad4
	internal Void AppendCJKExtension(Byte lv1msb, Byte lv1lsb) { }
	// RVA: 0x5effc1c VA: 0x7598517c1c
	internal Void AppendKana(Byte category, Byte lv1, Byte lv2, Byte lv3, Boolean isSmallKana, Byte markType, Boolean isKatakana, Boolean isHalfWidth) { }
	// RVA: 0x5eff990 VA: 0x7598517990
	internal Void AppendNormal(Byte category, Byte lv1, Byte lv2, Byte lv3) { }
	// RVA: 0x5f033c8 VA: 0x759851b3c8
	private Void AppendLevel5(Byte category, Byte lv1) { }
	// RVA: 0x5f032e8 VA: 0x759851b2e8
	private Void AppendBufferPrimitive(Byte value, ref Byte[] buf, ref Int32 bidx) { }
	// RVA: 0x5eff594 VA: 0x7598517594
	public SortKey GetResultAndReset() { }
	// RVA: 0x5f0393c VA: 0x759851b93c
	private Int32 GetOptimizedLength(Byte[] data, Int32 len, Byte defaultValue) { }
	// RVA: 0x5f03460 VA: 0x759851b460
	public SortKey GetResult() { }
}
```