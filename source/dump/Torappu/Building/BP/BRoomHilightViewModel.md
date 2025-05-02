# BRoomHilightViewModel

**Namespace:** `Torappu.Building.BP`


## Fields

- `BuildingToDoType m_selectedType`

- `BuildingToDoCategory m_selectedCategory`


## Properties

- `Boolean isHilighted`


## Methods

- `Boolean get_isHilighted()`

- `Void LoadData(List`1, BuildingToDoCategory, BuildingToDoType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BRoomHilightViewModel
{
	private List`1 m_hilightedSlots; // 0x10
	private BuildingToDoType m_selectedType; // 0x18
	private BuildingToDoCategory m_selectedCategory; // 0x1c

	public Boolean isHilighted { get; }
	public List`1 hilightedSlots { get; }

	// RVA: 0x3d16aa4 VA: 0x759632eaa4
	public Boolean get_isHilighted() { }
	// RVA: 0x3d193a4 VA: 0x75963313a4
	public List`1 get_hilightedSlots() { }
	// RVA: 0x3d168fc VA: 0x759632e8fc
	public Void LoadData(List`1 hilightedSlotIds, BuildingToDoCategory selectedCategory, BuildingToDoType selectedType) { }
	// RVA: 0x3d16db0 VA: 0x759632edb0
	public Void .ctor() { }
}
```