# ActivityReviewBinder

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `ActivityReviewAdapter _activityReviewAdapter`


## Methods

- `Void SetCallbacks(Action`1, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class ActivityReviewBinder : DataBinder`1, IHotfixable
{
	private ActivityReviewAdapter _activityReviewAdapter; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_SetCallbacks; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x275ba94 VA: 0x7594d73a94
	public override Void OnValueChanged(StoryReviewProperty property) { }
	// RVA: 0x275bb5c VA: 0x7594d73b5c
	public Void SetCallbacks(Action`1 onReviewChapterClicked, Action`1 onChapterRewardsGain) { }
	// RVA: 0x275bc04 VA: 0x7594d73c04
	public Void .ctor() { }
}
```