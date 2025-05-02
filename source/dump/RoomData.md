# RoomData

**Namespace:** ` `


## Fields

- `RoomType id`

- `String name`

- `String description`

- `String defaultPrefabId`

- `Boolean canLevelDown`

- `Int32 maxCount`

- `RoomCategory category`

- `GridPosition size`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoomData
{
	public RoomType id; // 0x10
	public String name; // 0x18
	public String description; // 0x20
	public String defaultPrefabId; // 0x28
	public Boolean canLevelDown; // 0x30
	public Int32 maxCount; // 0x34
	public RoomCategory category; // 0x38
	public GridPosition size; // 0x3c
	public PhaseData[] phases; // 0x48


	// RVA: 0x33c78fc VA: 0x75959df8fc
	public Void .ctor() { }
}
```