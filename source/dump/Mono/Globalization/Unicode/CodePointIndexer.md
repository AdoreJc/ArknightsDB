# CodePointIndexer

**Namespace:** `Mono.Globalization.Unicode`


## Fields

- `Int32 defaultIndex`

- `Int32 defaultCP`


## Methods

- `Int32 ToIndex(Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : Mono.Globalization.Unicode
internal class CodePointIndexer
{
	private readonly TableRange[] ranges; // 0x10
	public readonly Int32 TotalCount; // 0x18
	private Int32 defaultIndex; // 0x1c
	private Int32 defaultCP; // 0x20


	// RVA: 0x5efb238 VA: 0x7598513238
	public Void .ctor(Int32[] starts, Int32[] ends, Int32 defaultIndex, Int32 defaultCP) { }
	// RVA: 0x5efb3b8 VA: 0x75985133b8
	public Int32 ToIndex(Int32 cp) { }
}
```