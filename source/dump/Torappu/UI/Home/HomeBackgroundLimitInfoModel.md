# HomeBackgroundLimitInfoModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `Int64 startTime`

- `Int64 endTime`

- `String limitDesc`

- `Boolean displayAfterEndTime`


## Methods

- `Int32 CompareTo(HomeBackgroundLimitInfoModel)`

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeBackgroundLimitInfoModel : IHotfixable, IComparable`1, ITimeValidInfo
{
	public Int64 startTime; // 0x10
	public Int64 endTime; // 0x18
	public String limitDesc; // 0x20
	public Boolean displayAfterEndTime; // 0x28
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge __Hotfix0_GetStartTs; // 0x8
	private static DelegateBridge __Hotfix0_GetEndTs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2834cb0 VA: 0x7594e4ccb0
	public Int32 CompareTo(HomeBackgroundLimitInfoModel other) { }
	// RVA: 0x2834d3c VA: 0x7594e4cd3c
	public Int64 GetStartTs() { }
	// RVA: 0x2834da4 VA: 0x7594e4cda4
	public Int64 GetEndTs() { }
	// RVA: 0x2834e0c VA: 0x7594e4ce0c
	public Void .ctor() { }
}
```