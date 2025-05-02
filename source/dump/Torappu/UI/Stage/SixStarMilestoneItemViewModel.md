# SixStarMilestoneItemViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String itemId`

- `Int32 point`

- `Int32 sortId`

- `PlayerSixStarMilestoneState state`

- `SixStarMilestoneRewardType rewardType`

- `String stageName`


## Methods

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarMilestoneItemViewModel : IHotfixable, IComparable
{
	public String itemId; // 0x10
	public Int32 point; // 0x18
	public Int32 sortId; // 0x1c
	public PlayerSixStarMilestoneState state; // 0x20
	public SixStarMilestoneRewardType rewardType; // 0x24
	public String stageName; // 0x28
	public List`1 rewardList; // 0x30
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2f4b54c VA: 0x759556354c
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x2f4b418 VA: 0x7595563418
	public Void .ctor() { }
}
```