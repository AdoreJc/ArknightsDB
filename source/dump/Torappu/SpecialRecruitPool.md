# SpecialRecruitPool

**Namespace:** `Torappu`


## Fields

- `String recruitId`

- `String tagName`

- `Int32 tagId`

- `Int32 order`

- `Int64 startDateTime`

- `Int64 endDateTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SpecialRecruitPool : BasedRecruitPool
{
	public String recruitId; // 0x18
	public String tagName; // 0x20
	public Int32 tagId; // 0x28
	public Int32 order; // 0x2c
	public Int64 startDateTime; // 0x30
	public Int64 endDateTime; // 0x38
	public SpecialRecruitCostData[] recruitTimeTable; // 0x40


	// RVA: 0x34a2268 VA: 0x7595aba268
	public Void .ctor() { }
}
```