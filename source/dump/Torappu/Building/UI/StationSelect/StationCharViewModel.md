# StationCharViewModel

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `BuildingCharModel buildingChar`

- `CharacterCardViewModel commonChar`

- `RoomType roomType`

- `RoomCategory roomCategory`

- `Int64 apForSort`

- `StationedCharState stateForSort`

- `Boolean isShowPreQueueTag`

- `Boolean <hasActiveBuff>k__BackingField`

- `Int32 <buffSortId>k__BackingField`


## Properties

- `Boolean hasActiveBuff`

- `Int32 buffSortId`


## Methods

- `Boolean get_hasActiveBuff()`

- `Void set_hasActiveBuff(Boolean)`

- `Int32 get_buffSortId()`

- `Void set_buffSortId(Int32)`

- `Void LoadData(BuildingCharModel, RoomType)`

- `Void UpdateForSort()`

- `Boolean FilterWithBuff(BuffCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class StationCharViewModel
{
	public BuildingCharModel buildingChar; // 0x10
	public CharacterCardViewModel commonChar; // 0x80
	public RoomType roomType; // 0x88
	public RoomCategory roomCategory; // 0x8c
	public Int64 apForSort; // 0x90
	public StationedCharState stateForSort; // 0x98
	public Boolean isShowPreQueueTag; // 0x9c
	public List`1 unlockedBuffs; // 0xa0
	private Boolean <hasActiveBuff>k__BackingField; // 0xa8
	private Int32 <buffSortId>k__BackingField; // 0xac

	public Boolean hasActiveBuff { get; set; }
	public Int32 buffSortId { get; set; }

	// RVA: 0x3d94eec VA: 0x75963aceec
	public Boolean get_hasActiveBuff() { }
	// RVA: 0x3d94ef4 VA: 0x75963acef4
	private Void set_hasActiveBuff(Boolean value) { }
	// RVA: 0x3d94f00 VA: 0x75963acf00
	public Int32 get_buffSortId() { }
	// RVA: 0x3d94f08 VA: 0x75963acf08
	private Void set_buffSortId(Int32 value) { }
	// RVA: 0x3d94f10 VA: 0x75963acf10
	public Void LoadData(BuildingCharModel charModel, RoomType roomId) { }
	// RVA: 0x3d956b4 VA: 0x75963ad6b4
	public Void UpdateForSort() { }
	// RVA: 0x3d9574c VA: 0x75963ad74c
	public Boolean FilterWithBuff(BuffCategory category) { }
	// RVA: 0x3d957fc VA: 0x75963ad7fc
	public Void .ctor() { }
}
```