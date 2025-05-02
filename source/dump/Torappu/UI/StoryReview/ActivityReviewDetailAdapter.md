# ActivityReviewDetailAdapter

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `GameObject _itemTemplate`

- `Boolean m_ActivityOutOfTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class ActivityReviewDetailAdapter : LoopScrollAdapter`2, IHotfixable
{
	private GameObject _itemTemplate; // 0x58
	public Action`1 onReviewStoryClicked; // 0x60
	public Action`1 onUnlockStoryClicked; // 0x68
	public Action`1 onStoryRead; // 0x70
	public Boolean m_ActivityOutOfTime; // 0x78
	private static DelegateBridge __Hotfix0_CreateView; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x275bd04 VA: 0x7594d73d04
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x275be44 VA: 0x7594d73e44
	public override Void UpdateView(Int32 position, GameObject view, ActivityReviewDetailItemHolder holder, StoryReviewViewModel data) { }
	// RVA: 0x275c140 VA: 0x7594d74140
	public Void .ctor() { }
}
```