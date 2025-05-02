# STCharEquip

**Namespace:** ` `


## Fields

- `Int32 <hide>k__BackingField`

- `Int32 <locked>k__BackingField`

- `Int32 <level>k__BackingField`


## Properties

- `Int32 hide`

- `Int32 locked`

- `Int32 level`


## Methods

- `Int32 get_hide()`

- `Void set_hide(Int32)`

- `Int32 get_locked()`

- `Void set_locked(Int32)`

- `Int32 get_level()`

- `Void set_level(Int32)`

- `Void Read(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class STCharEquip : IStreamDeserialize
{
	private Int32 <hide>k__BackingField; // 0x10
	private Int32 <locked>k__BackingField; // 0x14
	private Int32 <level>k__BackingField; // 0x18

	public Int32 hide { get; set; }
	public Int32 locked { get; set; }
	public Int32 level { get; set; }

	// RVA: 0x35a03f0 VA: 0x7595bb83f0
	public Int32 get_hide() { }
	// RVA: 0x35a03f8 VA: 0x7595bb83f8
	private Void set_hide(Int32 value) { }
	// RVA: 0x35a0400 VA: 0x7595bb8400
	public Int32 get_locked() { }
	// RVA: 0x35a0408 VA: 0x7595bb8408
	private Void set_locked(Int32 value) { }
	// RVA: 0x35a0410 VA: 0x7595bb8410
	public Int32 get_level() { }
	// RVA: 0x35a0418 VA: 0x7595bb8418
	private Void set_level(Int32 value) { }
	// RVA: 0x35a0420 VA: 0x7595bb8420
	public Void Read(IStreamReader from) { }
	// RVA: 0x35a058c VA: 0x7595bb858c
	public Void .ctor() { }
}
```