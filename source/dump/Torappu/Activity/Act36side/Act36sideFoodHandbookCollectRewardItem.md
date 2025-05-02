# Act36sideFoodHandbookCollectRewardItem

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `GameObject _unfinishedPanel`

- `GameObject _finishedPanel`

- `GameObject _claimedPanel`

- `Text _unlockedCount`

- `Text _totalCount`

- `Slider _unlockedSlider`

- `UIPageFinder m_pageFinder`

- `RewardState m_cachedState`


## Methods

- `Void Render(Int32, Int32, RewardState)`

- `Void ClaimReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideFoodHandbookCollectRewardItem : MonoBehaviour, IHotfixable
{
	private GameObject _unfinishedPanel; // 0x18
	private GameObject _finishedPanel; // 0x20
	private GameObject _claimedPanel; // 0x28
	private Text _unlockedCount; // 0x30
	private Text _totalCount; // 0x38
	private Slider _unlockedSlider; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private RewardState m_cachedState; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ClaimReward; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3247220 VA: 0x759585f220
	public Void Render(Int32 unlockedCount, Int32 totalCount, RewardState state) { }
	// RVA: 0x3247378 VA: 0x759585f378
	public Void ClaimReward() { }
	// RVA: 0x324741c VA: 0x759585f41c
	public Void .ctor() { }
}
```