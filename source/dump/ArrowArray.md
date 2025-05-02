# ArrowArray

**Namespace:** ` `


## Fields

- `Mesh <mesh>k__BackingField`

- `Int32 <columnCount>k__BackingField`

- `Int32 <rowCount>k__BackingField`


## Properties

- `Mesh mesh`

- `Int32 columnCount`

- `Int32 rowCount`


## Methods

- `Mesh get_mesh()`

- `Void set_mesh(Mesh)`

- `Int32 get_columnCount()`

- `Void set_columnCount(Int32)`

- `Int32 get_rowCount()`

- `Void set_rowCount(Int32)`

- `Void BuildMesh(Int32, Int32)`

- `Void Release()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
private class ArrowArray
{
	private Mesh <mesh>k__BackingField; // 0x10
	private Int32 <columnCount>k__BackingField; // 0x18
	private Int32 <rowCount>k__BackingField; // 0x1c

	public Mesh mesh { get; set; }
	public Int32 columnCount { get; set; }
	public Int32 rowCount { get; set; }

	// RVA: 0x6667134 VA: 0x7598c7f134
	public Mesh get_mesh() { }
	// RVA: 0x666713c VA: 0x7598c7f13c
	private Void set_mesh(Mesh value) { }
	// RVA: 0x6667144 VA: 0x7598c7f144
	public Int32 get_columnCount() { }
	// RVA: 0x666714c VA: 0x7598c7f14c
	private Void set_columnCount(Int32 value) { }
	// RVA: 0x6667154 VA: 0x7598c7f154
	public Int32 get_rowCount() { }
	// RVA: 0x666715c VA: 0x7598c7f15c
	private Void set_rowCount(Int32 value) { }
	// RVA: 0x6666ae8 VA: 0x7598c7eae8
	public Void BuildMesh(Int32 columns, Int32 rows) { }
	// RVA: 0x6666ac4 VA: 0x7598c7eac4
	public Void Release() { }
	// RVA: 0x6666abc VA: 0x7598c7eabc
	public Void .ctor() { }
}
```