# MedalGroupData

**Namespace:** `Torappu`


## Fields

- `String groupId`

- `String groupName`

- `String groupDesc`

- `Int32 sortId`

- `String groupBackColor`

- `Int64 groupGetTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class MedalGroupData
{
	public String groupId; // 0x10
	public String groupName; // 0x18
	public String groupDesc; // 0x20
	public List`1 medalId; // 0x28
	public Int32 sortId; // 0x30
	public String groupBackColor; // 0x38
	public Int64 groupGetTime; // 0x40
	public List`1 sharedExpireTimes; // 0x48


	// RVA: 0x34a50fc VA: 0x7595abd0fc
	public virtual Boolean ShouldSerializesharedExpireTimes() { }
	// RVA: 0x34a5104 VA: 0x7595abd104
	public Void .ctor() { }
}
```