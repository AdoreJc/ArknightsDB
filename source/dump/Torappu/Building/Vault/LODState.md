# LODState

**Namespace:** `Torappu.Building.Vault`


## Fields

- `Int32 m_lodValue`

- `LODLEVEL m_level`

- `Boolean m_dirty`


## Properties

- `Boolean dirty`

- `Int32 lodValue`

- `LODLEVEL lodLevel`


## Methods

- `Boolean get_dirty()`

- `Int32 get_lodValue()`

- `Void set_lodValue(Int32)`

- `LODLEVEL get_lodLevel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class LODState
{
	private Int32 m_lodValue; // 0x10
	private LODLEVEL m_level; // 0x14
	private Boolean m_dirty; // 0x18

	public Boolean dirty { get; }
	public Int32 lodValue { get; set; }
	public LODLEVEL lodLevel { get; }

	// RVA: 0x38464e8 VA: 0x7595e5e4e8
	public Boolean get_dirty() { }
	// RVA: 0x38464f0 VA: 0x7595e5e4f0
	public Int32 get_lodValue() { }
	// RVA: 0x38464f8 VA: 0x7595e5e4f8
	public Void set_lodValue(Int32 value) { }
	// RVA: 0x3846514 VA: 0x7595e5e514
	public LODLEVEL get_lodLevel() { }
	// RVA: 0x38465b0 VA: 0x7595e5e5b0
	public Void .ctor() { }
}
```