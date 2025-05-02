# ArcadeBadgeData

**Namespace:** ` `


## Fields

- `String badgeId`

- `BadgeType badgeType`

- `Int32 sortId`

- `String badgeName`

- `String buffRangeDesc`

- `Boolean hasScore`

- `String scoreZone`


## Methods

- `Boolean ShouldSerializebuffRangeDesc()`

- `Boolean ShouldSerializescoreZone()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ArcadeBadgeData
{
	public String badgeId; // 0x10
	public BadgeType badgeType; // 0x18
	public Int32 sortId; // 0x1c
	public String badgeName; // 0x20
	public String buffRangeDesc; // 0x28
	public Boolean hasScore; // 0x30
	public String scoreZone; // 0x38
	public ListDict`2 tiers; // 0x40


	// RVA: 0x33b8ea8 VA: 0x75959d0ea8
	public Boolean ShouldSerializebuffRangeDesc() { }
	// RVA: 0x33b8ec8 VA: 0x75959d0ec8
	public Boolean ShouldSerializescoreZone() { }
	// RVA: 0x33b8ee8 VA: 0x75959d0ee8
	public Void .ctor() { }
}
```