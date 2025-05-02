# OrgData

**Namespace:** ` `


## Fields

- `String orgId`

- `String orgName`

- `String orgEnName`

- `Int64 openTime`

- `ItemBundle prestigeItem`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class OrgData
{
	public String orgId; // 0x10
	public String orgName; // 0x18
	public String orgEnName; // 0x20
	public Int64 openTime; // 0x28
	public List`1 principalIdList; // 0x30
	public List`1 prestigeList; // 0x38
	public Dictionary`2 agendaCount2PrestigeItemMap; // 0x40
	public List`1 orgSectionList; // 0x48
	public ItemBundle prestigeItem; // 0x50


	// RVA: 0x33b4db8 VA: 0x75959ccdb8
	public Void .ctor() { }
}
```