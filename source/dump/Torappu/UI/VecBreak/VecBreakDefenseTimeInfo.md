# VecBreakDefenseTimeInfo

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `Int64 startTime`


## Methods

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefenseTimeInfo : IHotfixable, ITimeValidInfo
{
	public Int64 startTime; // 0x10
	private static DelegateBridge __Hotfix0_GetStartTs; // 0x0
	private static DelegateBridge __Hotfix0_GetEndTs; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22cc68c VA: 0x75948e468c
	public Int64 GetStartTs() { }
	// RVA: 0x22cc6f4 VA: 0x75948e46f4
	public Int64 GetEndTs() { }
	// RVA: 0x22cc75c VA: 0x75948e475c
	public Void .ctor() { }
}
```