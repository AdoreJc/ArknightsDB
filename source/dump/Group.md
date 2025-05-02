# Group

**Namespace:** ` `


## Fields

- `String id`

- `String groupName`

- `Int32 maxLine`

- `Int32 minUnAvailLine`

- `Int32 maxAvailLine`

- `Int32 percent`

- `String firstLockItemId`

- `Boolean isAllUnlock`

- `Boolean isAreaUnlock`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Group
{
	public String id; // 0x10
	public String groupName; // 0x18
	public ListDict`2 items; // 0x20
	public Int32 maxLine; // 0x28
	public Int32 minUnAvailLine; // 0x2c
	public Int32 maxAvailLine; // 0x30
	public Int32 percent; // 0x34
	public String firstLockItemId; // 0x38
	public Boolean isAllUnlock; // 0x40
	public Boolean isAreaUnlock; // 0x41


	// RVA: 0x3274abc VA: 0x759588cabc
	public Void .ctor() { }
}
```