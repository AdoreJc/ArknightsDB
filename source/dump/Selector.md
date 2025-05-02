# Selector

**Namespace:** ` `


## Fields

- `ProfessionCategory professionMask`

- `BuildableType buildableMask`

- `PlayerSideMask playerSideMask`

- `SideType sideType`


## Methods

- `Selector Duplicate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Selector
{
	public ProfessionCategory professionMask; // 0x10
	public BuildableType buildableMask; // 0x14
	public PlayerSideMask playerSideMask; // 0x18
	public SideType sideType; // 0x1c
	public List`1 charIdFilter; // 0x20
	public List`1 enemyIdFilter; // 0x28
	public List`1 enemyIdExcludeFilter; // 0x30
	public List`1 enemyLevelTypeFilter; // 0x38
	public List`1 enemyActionHiddenGroupFilter; // 0x40
	public List`1 skillIdFilter; // 0x48
	public List`1 tileKeyFilter; // 0x50
	public List`1 groupTagFilter; // 0x58
	public List`1 filterTagFilter; // 0x60
	public List`1 filterTagExcludeFilter; // 0x68
	public List`1 subProfessionExcludeFilter; // 0x70
	public List`1 mapTagFilter; // 0x78


	// RVA: 0x34b1818 VA: 0x7595ac9818
	public Selector Duplicate() { }
	// RVA: 0x34b1d84 VA: 0x7595ac9d84
	public Void .ctor() { }
}
```