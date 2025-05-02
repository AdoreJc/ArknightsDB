# Card

**Namespace:** ` `


## Fields

- `Int32 inst_id`

- `Int32 char_inst_id`

- `String char_id`

- `Int32 level`

- `Int32 phase`

- `Int32 favor_point`

- `Int32 potential_rank`

- `String tmpl_id`

- `Int32 skill_index`

- `Int32 skill_level`

- `Int32 spec_skill_level`

- `String skin_id`

- `String equip_id`

- `Int32 equip_level`


## Methods

- `Void Read(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Card : IStreamDeserialize
{
	public Int32 inst_id; // 0x10
	public Int32 char_inst_id; // 0x14
	public String char_id; // 0x18
	public Int32 level; // 0x20
	public Int32 phase; // 0x24
	public Int32 favor_point; // 0x28
	public Int32 potential_rank; // 0x2c
	public String tmpl_id; // 0x30
	public Int32 skill_index; // 0x38
	public Int32 skill_level; // 0x3c
	public Int32 spec_skill_level; // 0x40
	public String skin_id; // 0x48
	public String equip_id; // 0x50
	public Int32 equip_level; // 0x58


	// RVA: 0x359897c VA: 0x7595bb097c
	public Void Read(IStreamReader from) { }
	// RVA: 0x3598f34 VA: 0x7595bb0f34
	public Void .ctor() { }
}
```