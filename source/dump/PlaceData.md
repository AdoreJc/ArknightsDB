# PlaceData

**Namespace:** ` `


## Fields

- `String placeId`

- `String placeDesc`

- `String lockEventId`

- `String zoneId`

- `String visibleCondType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PlaceData
{
	public String placeId; // 0x10
	public String placeDesc; // 0x18
	public String lockEventId; // 0x20
	public String zoneId; // 0x28
	public String visibleCondType; // 0x30
	public List`1 visibleParams; // 0x38


	// RVA: 0x33b5458 VA: 0x75959cd458
	public virtual Boolean ShouldSerializevisibleCondType() { }
	// RVA: 0x33b5468 VA: 0x75959cd468
	public virtual Boolean ShouldSerializevisibleParams() { }
	// RVA: 0x33b54bc VA: 0x75959cd4bc
	public Void .ctor() { }
}
```