# SandboxV2MonthRushData

**Namespace:** `Torappu`


## Fields

- `String monthlyRushId`

- `Int64 startTime`

- `Int64 endTime`

- `Boolean isLast`

- `Int32 sortId`

- `String rushGroupKey`

- `String monthlyRushName`

- `String monthlyRushDes`

- `String weatherId`

- `String nodeId`

- `String conditionGroup`

- `String conditionDesc`


## Methods

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2MonthRushData : ITimeValidInfo, IHotfixable
{
	public String monthlyRushId; // 0x10
	public Int64 startTime; // 0x18
	public Int64 endTime; // 0x20
	public Boolean isLast; // 0x28
	public Int32 sortId; // 0x2c
	public String rushGroupKey; // 0x30
	public String monthlyRushName; // 0x38
	public String monthlyRushDes; // 0x40
	public String weatherId; // 0x48
	public String nodeId; // 0x50
	public String conditionGroup; // 0x58
	public String conditionDesc; // 0x60
	public List`1 rewardItemList; // 0x68
	private static DelegateBridge __Hotfix0_GetStartTs; // 0x0
	private static DelegateBridge __Hotfix0_GetEndTs; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x34f2234 VA: 0x7595b0a234
	public Int64 GetStartTs() { }
	// RVA: 0x34f229c VA: 0x7595b0a29c
	public Int64 GetEndTs() { }
	// RVA: 0x34f2304 VA: 0x7595b0a304
	public Void .ctor() { }
}
```