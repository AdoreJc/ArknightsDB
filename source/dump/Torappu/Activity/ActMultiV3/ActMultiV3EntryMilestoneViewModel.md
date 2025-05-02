# ActMultiV3EntryMilestoneViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Int32 currPoint`

- `Int32 currRank`

- `Boolean isMaxRank`

- `Int32 currRankStartPoint`

- `Int32 nextRankStartPoint`

- `Boolean hasUnreceivedReward`


## Methods

- `Void _CalculateRank(ActMultiV3Data, PlayerMultiV3Activity)`

- `Void LoadData(String, PlayerMultiV3Activity, ActMultiV3Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3EntryMilestoneViewModel : IHotfixable
{
	public Int32 currPoint; // 0x10
	public Int32 currRank; // 0x14
	public Boolean isMaxRank; // 0x18
	public Int32 currRankStartPoint; // 0x1c
	public Int32 nextRankStartPoint; // 0x20
	public Boolean hasUnreceivedReward; // 0x24
	private static DelegateBridge __Hotfix0__CalculateRank; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30f0d28 VA: 0x7595708d28
	private Void _CalculateRank(ActMultiV3Data actData, PlayerMultiV3Activity playerActivity) { }
	// RVA: 0x30f0f34 VA: 0x7595708f34
	public Void LoadData(String actId, PlayerMultiV3Activity playerActivity, ActMultiV3Data actData) { }
	// RVA: 0x30f10c8 VA: 0x75957090c8
	public Void .ctor() { }
}
```