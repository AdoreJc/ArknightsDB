# NormalGachaTkt

**Namespace:** ` `


## Fields

- `String itemId`

- `Int64 endTime`

- `String gachaPoolId`

- `Boolean isTen`


## Methods

- `Int64 GetEndTime()`

- `Boolean IsValid(Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NormalGachaTkt : IGachaTimeData
{
	public String itemId; // 0x10
	public Int64 endTime; // 0x18
	public String gachaPoolId; // 0x20
	public Boolean isTen; // 0x28


	// RVA: 0x34a2698 VA: 0x7595aba698
	public Int64 GetEndTime() { }
	// RVA: 0x34a26a0 VA: 0x7595aba6a0
	public Boolean IsValid(Int64 curTs) { }
	// RVA: 0x34a26b0 VA: 0x7595aba6b0
	public Void .ctor() { }
}
```