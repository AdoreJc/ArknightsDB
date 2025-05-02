# Act1ArcadeBadgeBookItemViewModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `String badgeId`

- `BadgeType badgeType`

- `Int32 sortId`

- `String name`

- `String buffRangeDesc`

- `Boolean hasScore`

- `String scoreZoneId`

- `Int32 score`

- `Int32 currentTier`


## Methods

- `Int32 CompareTo(Act1ArcadeBadgeBookItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookItemViewModel : IComparable`1, IHotfixable
{
	public String badgeId; // 0x10
	public BadgeType badgeType; // 0x18
	public Int32 sortId; // 0x1c
	public String name; // 0x20
	public String buffRangeDesc; // 0x28
	public Boolean hasScore; // 0x30
	public String scoreZoneId; // 0x38
	public List`1 tiers; // 0x40
	public Int32 score; // 0x48
	public Int32 currentTier; // 0x4c
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x33fc08c VA: 0x7595a1408c
	public Int32 CompareTo(Act1ArcadeBadgeBookItemViewModel other) { }
	// RVA: 0x33fc140 VA: 0x7595a14140
	public Void .ctor() { }
}
```