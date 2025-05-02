# SortAndFilterState

**Namespace:** ` `


## Fields

- `FurnitureSortingOption <sortingOption>k__BackingField`

- `SortingMethod <sortingMethod>k__BackingField`


## Properties

- `FurnitureSortingOption sortingOption`

- `SortingMethod sortingMethod`


## Methods

- `FurnitureSortingOption get_sortingOption()`

- `Void set_sortingOption(FurnitureSortingOption)`

- `SortingMethod get_sortingMethod()`

- `Void set_sortingMethod(SortingMethod)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SortAndFilterState : ISortAndFilterState
{
	private FurnitureSortingOption <sortingOption>k__BackingField; // 0x10
	private SortingMethod <sortingMethod>k__BackingField; // 0x14
	public List`1 filters; // 0x18

	public FurnitureSortingOption sortingOption { get; set; }
	public SortingMethod sortingMethod { get; set; }

	// RVA: 0x380d564 VA: 0x7595e25564
	public FurnitureSortingOption get_sortingOption() { }
	// RVA: 0x380d56c VA: 0x7595e2556c
	public Void set_sortingOption(FurnitureSortingOption value) { }
	// RVA: 0x380d574 VA: 0x7595e25574
	public SortingMethod get_sortingMethod() { }
	// RVA: 0x380d57c VA: 0x7595e2557c
	public Void set_sortingMethod(SortingMethod value) { }
	// RVA: 0x380d584 VA: 0x7595e25584
	public IEnumerable`1 EnumSortingSetting() { }
	// RVA: 0x380d3a0 VA: 0x7595e253a0
	public Void .ctor() { }
}
```