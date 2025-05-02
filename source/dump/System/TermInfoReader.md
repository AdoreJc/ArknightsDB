# TermInfoReader

**Namespace:** `System`


## Fields

- `Int32 boolSize`

- `Int32 numSize`

- `Int32 strOffsets`

- `Int32 booleansOffset`

- `Int32 intOffset`


## Methods

- `Void DetermineVersion(Int16)`

- `Void ReadHeader(Byte[], ref)`

- `Void ReadNames(Byte[], ref)`

- `Int32 Get(TermInfoNumbers)`

- `String Get(TermInfoStrings)`

- `Int16 GetInt16(Byte[], Int32)`

- `String GetString(Byte[], Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class TermInfoReader
{
	private Int32 boolSize; // 0x10
	private Int32 numSize; // 0x14
	private Int32 strOffsets; // 0x18
	private Byte[] buffer; // 0x20
	private Int32 booleansOffset; // 0x28
	private Int32 intOffset; // 0x2c


	// RVA: 0x6106d48 VA: 0x759871ed48
	public Void .ctor(String term, String filename) { }
	// RVA: 0x6107030 VA: 0x759871f030
	public Void .ctor(String term, Byte[] buffer) { }
	// RVA: 0x610d074 VA: 0x7598725074
	private Void DetermineVersion(Int16 magic) { }
	// RVA: 0x610cf80 VA: 0x7598724f80
	private Void ReadHeader(Byte[] buffer, ref Int32 position) { }
	// RVA: 0x610d040 VA: 0x7598725040
	private Void ReadNames(Byte[] buffer, ref Int32 position) { }
	// RVA: 0x6107a88 VA: 0x759871fa88
	public Int32 Get(TermInfoNumbers number) { }
	// RVA: 0x61079f8 VA: 0x759871f9f8
	public String Get(TermInfoStrings tstr) { }
	// RVA: 0x610ba3c VA: 0x7598723a3c
	public Byte[] GetStringBytes(TermInfoStrings tstr) { }
	// RVA: 0x610d124 VA: 0x7598725124
	private Int16 GetInt16(Byte[] buffer, Int32 offset) { }
	// RVA: 0x610d174 VA: 0x7598725174
	private String GetString(Byte[] buffer, Int32 offset) { }
	// RVA: 0x610d1f0 VA: 0x75987251f0
	private Byte[] GetStringBytes(Byte[] buffer, Int32 offset) { }
}
```