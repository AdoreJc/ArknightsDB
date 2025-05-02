# ActArchiveEndbookItemData

**Namespace:** `Torappu`


## Fields

- `String endBookId`

- `Int32 sortId`

- `String enrollId`

- `Boolean isLast`

- `String endbookName`

- `String unlockDesc`

- `String textId`


## Methods

- `Boolean ShouldSerializeenrollId()`

- `Boolean ShouldSerializeisLast()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActArchiveEndbookItemData
{
	public String endBookId; // 0x10
	public Int32 sortId; // 0x18
	public String enrollId; // 0x20
	public Boolean isLast; // 0x28
	public String endbookName; // 0x30
	public String unlockDesc; // 0x38
	public String textId; // 0x40


	// RVA: 0x33b41c8 VA: 0x75959cc1c8
	public Boolean ShouldSerializeenrollId() { }
	// RVA: 0x33b41e8 VA: 0x75959cc1e8
	public Boolean ShouldSerializeisLast() { }
	// RVA: 0x33b41f0 VA: 0x75959cc1f0
	public Void .ctor() { }
}
```