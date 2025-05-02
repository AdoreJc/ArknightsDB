# STCharSkill

**Namespace:** ` `


## Fields

- `Int32 <unlock>k__BackingField`

- `Int32 <specializeLevel>k__BackingField`


## Properties

- `Int32 unlock`

- `Int32 specializeLevel`


## Methods

- `Int32 get_unlock()`

- `Void set_unlock(Int32)`

- `Int32 get_specializeLevel()`

- `Void set_specializeLevel(Int32)`

- `Void Read(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class STCharSkill : IStreamDeserialize
{
	private Int32 <unlock>k__BackingField; // 0x10
	private Int32 <specializeLevel>k__BackingField; // 0x14

	public Int32 unlock { get; set; }
	public Int32 specializeLevel { get; set; }

	// RVA: 0x35a02bc VA: 0x7595bb82bc
	public Int32 get_unlock() { }
	// RVA: 0x35a02c4 VA: 0x7595bb82c4
	private Void set_unlock(Int32 value) { }
	// RVA: 0x35a02cc VA: 0x7595bb82cc
	public Int32 get_specializeLevel() { }
	// RVA: 0x35a02d4 VA: 0x7595bb82d4
	private Void set_specializeLevel(Int32 value) { }
	// RVA: 0x35a02dc VA: 0x7595bb82dc
	public Void Read(IStreamReader from) { }
	// RVA: 0x35a03e8 VA: 0x7595bb83e8
	public Void .ctor() { }
}
```