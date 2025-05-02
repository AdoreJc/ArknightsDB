# ActivityReviewAdapter

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `GameObject _itemTemplate`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class ActivityReviewAdapter : LoopScrollAdapter`2, IHotfixable
{
	private GameObject _itemTemplate; // 0x58
	public Action`1 onReviewClicked; // 0x60
	public Action`1 onRewardsGain; // 0x68
	private static DelegateBridge __Hotfix0_UpdateView; // 0x0
	private static DelegateBridge __Hotfix0_CreateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x275b298 VA: 0x7594d73298
	public override Void UpdateView(Int32 position, GameObject view, ActivityReviewItemHolder holder, StoryReviewChapterViewModel data) { }
	// RVA: 0x275b8c4 VA: 0x7594d738c4
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x275ba04 VA: 0x7594d73a04
	public Void .ctor() { }
}
```