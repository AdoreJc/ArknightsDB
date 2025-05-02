# LinkageTenGachaTkt

**Namespace:** ` `


## Fields

- `String itemId`

- `Int64 endTime`

- `String gachaPoolId`


## Methods

- `Int64 GetEndTime()`

- `Boolean IsValid(Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LinkageTenGachaTkt : IGachaTimeData
{
	public String itemId; // 0x10
	public Int64 endTime; // 0x18
	public String gachaPoolId; // 0x20


	// RVA: 0x34a2678 VA: 0x7595aba678
	public Int64 GetEndTime() { }
	// RVA: 0x34a2680 VA: 0x7595aba680
	public Boolean IsValid(Int64 curTs) { }
	// RVA: 0x34a2690 VA: 0x7595aba690
	public Void .ctor() { }
}
```