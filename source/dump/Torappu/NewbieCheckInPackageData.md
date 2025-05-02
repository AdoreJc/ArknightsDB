# NewbieCheckInPackageData

**Namespace:** `Torappu`


## Fields

- `String groupId`

- `Int64 startTime`

- `Int64 endTime`

- `String bindGPGoodId`

- `Int32 checkInDuration`

- `Int32 totalCheckInDay`

- `String iconId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class NewbieCheckInPackageData
{
	public String groupId; // 0x10
	public Int64 startTime; // 0x18
	public Int64 endTime; // 0x20
	public String bindGPGoodId; // 0x28
	public Int32 checkInDuration; // 0x30
	public Int32 totalCheckInDay; // 0x34
	public String iconId; // 0x38
	public Dictionary`2 checkInRewardDict; // 0x40


	// RVA: 0x34a616c VA: 0x7595abe16c
	public Void .ctor() { }
}
```