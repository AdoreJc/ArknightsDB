# StoryReviewRewardsItemView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `Transform _itemContainer`

- `Single _itemScale`

- `Text _nameText`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_cacheItemViewModel`


## Methods

- `UIItemCard _EnsureItemCard()`

- `Void RenderItem(ItemBundle)`

- `Void <_EnsureItemCard>b__5_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewRewardsItemView : MonoBehaviour, IHotfixable
{
	private Transform _itemContainer; // 0x18
	private Single _itemScale; // 0x20
	private Text _nameText; // 0x28
	private UIItemCard m_itemCard; // 0x30
	private UIItemViewModel m_cacheItemViewModel; // 0x38
	private static DelegateBridge __Hotfix0__EnsureItemCard; // 0x0
	private static DelegateBridge __Hotfix0_RenderItem; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x276044c VA: 0x7594d7844c
	private UIItemCard _EnsureItemCard() { }
	// RVA: 0x2760328 VA: 0x7594d78328
	public Void RenderItem(ItemBundle item) { }
	// RVA: 0x2760674 VA: 0x7594d78674
	public Void .ctor() { }
	// RVA: 0x27606f0 VA: 0x7594d786f0
	private Void <_EnsureItemCard>b__5_0(Int32 _) { }
}
```