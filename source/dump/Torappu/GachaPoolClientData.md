# GachaPoolClientData

**Namespace:** `Torappu`


## Fields

- `String gachaPoolId`

- `Int32 gachaIndex`

- `Int64 openTime`

- `Int64 endTime`

- `String gachaPoolName`

- `String gachaPoolSummary`

- `String gachaPoolDetail`

- `String guaranteeName`

- `Int32 guarantee5Avail`

- `Int32 guarantee5Count`

- `String LMTGSID`

- `String CDPrimColor`

- `String CDSecColor`

- `String freeBackColor`

- `GachaRuleType gachaRuleType`

- `JObject dynMeta`

- `String linkageRuleId`

- `JObject linkageParam`

- `JObject limitParam`


## Methods

- `Boolean IsValid(Int64)`

- `Int64 GetEndTime()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GachaPoolClientData : IComparable`1, IGachaTimeData
{
	public String gachaPoolId; // 0x10
	public Int32 gachaIndex; // 0x18
	public Int64 openTime; // 0x20
	public Int64 endTime; // 0x28
	public String gachaPoolName; // 0x30
	public String gachaPoolSummary; // 0x38
	public String gachaPoolDetail; // 0x40
	public String guaranteeName; // 0x48
	public Int32 guarantee5Avail; // 0x50
	public Int32 guarantee5Count; // 0x54
	public String LMTGSID; // 0x58
	public String CDPrimColor; // 0x60
	public String CDSecColor; // 0x68
	public String freeBackColor; // 0x70
	public GachaRuleType gachaRuleType; // 0x78
	public JObject dynMeta; // 0x80
	public String linkageRuleId; // 0x88
	public JObject linkageParam; // 0x90
	public JObject limitParam; // 0x98


	// RVA: 0x34a21c4 VA: 0x7595aba1c4
	public virtual Int32 CompareTo(GachaPoolClientData otherModel) { }
	// RVA: 0x34a21e4 VA: 0x7595aba1e4
	public Boolean IsValid(Int64 curTs) { }
	// RVA: 0x34a2208 VA: 0x7595aba208
	public Int64 GetEndTime() { }
	// RVA: 0x34a2210 VA: 0x7595aba210
	public Void .ctor() { }
}
```