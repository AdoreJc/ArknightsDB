# CartCompViewModel

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String compId`

- `Int32 sortId`

- `Int32 count`

- `Int32 inUseCount`

- `Int32 selectUsedCount`

- `CartAccessoryType type`

- `String name`

- `Boolean currentSelect`

- `Int32 rarityLevel`

- `Boolean isObtained`

- `String detailText`

- `String detailExhibitText`


## Properties

- `String rarityResName`


## Methods

- `String get_rarityResName()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class CartCompViewModel
{
	private const String RARITY_RES_FORMAT; // 0x0
	public String compId; // 0x10
	public Int32 sortId; // 0x18
	public List`1 availPosList; // 0x20
	public Int32 count; // 0x28
	public Int32 inUseCount; // 0x2c
	public Int32 selectUsedCount; // 0x30
	public CartAccessoryType type; // 0x34
	public String name; // 0x38
	public Boolean currentSelect; // 0x40
	public Int32 rarityLevel; // 0x44
	public Boolean isObtained; // 0x48
	public String detailText; // 0x50
	public String detailExhibitText; // 0x58

	public String rarityResName { get; }

	// RVA: 0x32ee010 VA: 0x7595906010
	public String get_rarityResName() { }
	// RVA: 0x32f16f0 VA: 0x75959096f0
	public Void .ctor() { }
}
```