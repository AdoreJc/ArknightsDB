# SandboxV2QuestTrackerItemViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String questId`

- `Int32 selectedNodeIndex`

- `String title`

- `String desc`

- `String targetDesc`

- `String progress`

- `String target`

- `Boolean showProgress`

- `SandboxV2QuestLineBadgeType badgeType`

- `SandboxV2QuestRouteType routeType`

- `String routeParam`

- `Int32 questLineSortId`

- `Int32 unlockSortId`


## Methods

- `Int32 CompareTo(SandboxV2QuestTrackerItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2QuestTrackerItemViewModel : IHotfixable, IComparable`1
{
	public String questId; // 0x10
	public List`1 nodeFloats; // 0x18
	public Int32 selectedNodeIndex; // 0x20
	public String title; // 0x28
	public String desc; // 0x30
	public String targetDesc; // 0x38
	public String progress; // 0x40
	public String target; // 0x48
	public Boolean showProgress; // 0x50
	public SandboxV2QuestLineBadgeType badgeType; // 0x54
	public SandboxV2QuestRouteType routeType; // 0x58
	public String routeParam; // 0x60
	public Int32 questLineSortId; // 0x68
	public Int32 unlockSortId; // 0x6c
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25598f8 VA: 0x7594b718f8
	public Int32 CompareTo(SandboxV2QuestTrackerItemViewModel other) { }
	// RVA: 0x25599a8 VA: 0x7594b719a8
	public Void .ctor() { }
}
```