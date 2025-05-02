# MiniActReviewListAdapter

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `GameObject _itemTemplate`


## Methods

- `Void set_onReviewChapterClick(Action`1)`

- `Void set_onChapterRewardGain(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActReviewListAdapter : RecycleLoopScrollAdapter`2
{
	private GameObject _itemTemplate; // 0x68
	private Action`1 <onReviewChapterClick>k__BackingField; // 0x70
	private Action`1 <onChapterRewardGain>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onReviewChapterClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onReviewChapterClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onChapterRewardGain; // 0x10
	private static DelegateBridge __Hotfix0_set_onChapterRewardGain; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onReviewChapterClick { get; set; }
	private Action`1 onChapterRewardGain { get; set; }

	// RVA: 0x2748780 VA: 0x7594d60780
	private Action`1 get_onReviewChapterClick() { }
	// RVA: 0x2748470 VA: 0x7594d60470
	public Void set_onReviewChapterClick(Action`1 value) { }
	// RVA: 0x27487e8 VA: 0x7594d607e8
	private Action`1 get_onChapterRewardGain() { }
	// RVA: 0x27484f4 VA: 0x7594d604f4
	public Void set_onChapterRewardGain(Action`1 value) { }
	// RVA: 0x2748850 VA: 0x7594d60850
	public override Void UpdateView(Int32 position, GameObject view, MiniActReviewListItemHolder holder, StoryReviewChapterViewModel data) { }
	// RVA: 0x27489b4 VA: 0x7594d609b4
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x2748a70 VA: 0x7594d60a70
	public Void .ctor() { }
}
```