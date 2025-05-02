# BlockedEnemyManager

**Namespace:** ` `


## Fields

- `Int32 m_totalVolume`


## Properties

- `Int32 count`

- `Int32 totalVolume`

- `Enemy Item`


## Methods

- `Int32 get_count()`

- `Int32 get_totalVolume()`

- `Enemy get_Item(Int32)`

- `Void set_Item(Int32, Enemy)`

- `Void Add(Enemy)`

- `Boolean Remove(Enemy)`

- `Void Clear()`

- `Boolean Contains(Enemy)`

- `Int32 GetRemainingVolume(Int32)`

- `Boolean CheckVolumeNotExceeded(Enemy, Int32)`

- `Boolean TryPickOneToRemoveIfVolumeExceeded(Int32, out)`

- `Void RecalculateVolume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BlockedEnemyManager
{
	private Int32 m_totalVolume; // 0x10
	private List`1 m_blockedEnemies; // 0x18

	public Int32 count { get; }
	public Int32 totalVolume { get; }
	public List`1 exposedRawList { get; }
	public Enemy Item { get; set; }

	// RVA: 0x1bf76f8 VA: 0x759420f6f8
	public Int32 get_count() { }
	// RVA: 0x1bf7740 VA: 0x759420f740
	public Int32 get_totalVolume() { }
	// RVA: 0x1bf7748 VA: 0x759420f748
	public List`1 get_exposedRawList() { }
	// RVA: 0x1bf7750 VA: 0x759420f750
	public Enemy get_Item(Int32 index) { }
	// RVA: 0x1bf77a8 VA: 0x759420f7a8
	public Void set_Item(Int32 index, Enemy value) { }
	// RVA: 0x1bf7810 VA: 0x759420f810
	public Void Add(Enemy enemy) { }
	// RVA: 0x1bf7958 VA: 0x759420f958
	public Boolean Remove(Enemy enemy) { }
	// RVA: 0x1bf79dc VA: 0x759420f9dc
	public Void Clear() { }
	// RVA: 0x1bf7a50 VA: 0x759420fa50
	public Boolean Contains(Enemy enemy) { }
	// RVA: 0x1bf7aa8 VA: 0x759420faa8
	public Int32 GetRemainingVolume(Int32 maxVolume) { }
	// RVA: 0x1bf7ab8 VA: 0x759420fab8
	public Boolean CheckVolumeNotExceeded(Enemy enemy, Int32 maxVolume) { }
	// RVA: 0x1bf7af0 VA: 0x759420faf0
	public Boolean TryPickOneToRemoveIfVolumeExceeded(Int32 newMaxVolume, out Enemy candidate) { }
	// RVA: 0x1bf7ba0 VA: 0x759420fba0
	public Void RecalculateVolume() { }
	// RVA: 0x1bf7d00 VA: 0x759420fd00
	public Void .ctor() { }
}
```