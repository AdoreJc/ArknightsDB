# Act5D0MileStoneHolder

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `Text _curMilestoneToken`

- `Text _curBonusCond`

- `Text _curBonusName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0MileStoneHolder : MileStoneHolder
{
	private Text _curMilestoneToken; // 0x30
	private Text _curBonusCond; // 0x38
	private Text _curBonusName; // 0x40
	private static DelegateBridge __Hotfix0_OnRefreshHolderInfo; // 0x0
	private static DelegateBridge __Hotfix0_GetScrollToTargetIndex; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31c16d0 VA: 0x75957d96d0
	protected override Void OnRefreshHolderInfo(List`1 viewModelList, Int32 count, String spReward) { }
	// RVA: 0x31c1964 VA: 0x75957d9964
	protected override Single GetScrollToTargetIndex(Int32 firstAbleGet) { }
	// RVA: 0x31c1ab8 VA: 0x75957d9ab8
	public Void .ctor() { }
}
```