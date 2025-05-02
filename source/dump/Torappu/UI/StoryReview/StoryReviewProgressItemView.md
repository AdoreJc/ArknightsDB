# StoryReviewProgressItemView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `Slider _progressSlider`

- `Text _progressText`

- `Button _rewardInfoBtn`

- `UIPageFinder m_pageFinder`


## Methods

- `Void RenderProgress(Int32, Int32, ItemBundle[])`

- `Void OnRewardInfoClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewProgressItemView : MonoBehaviour, IHotfixable
{
	private Slider _progressSlider; // 0x18
	private Text _progressText; // 0x20
	private Button _rewardInfoBtn; // 0x28
	private List`1 m_cachedRewards; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private static DelegateBridge __Hotfix0_RenderProgress; // 0x0
	private static DelegateBridge __Hotfix0_OnRewardInfoClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x275e6dc VA: 0x7594d766dc
	public Void RenderProgress(Int32 progress, Int32 total, ItemBundle[] rewards) { }
	// RVA: 0x275f974 VA: 0x7594d77974
	public Void OnRewardInfoClicked() { }
	// RVA: 0x275fd9c VA: 0x7594d77d9c
	public Void .ctor() { }
}
```