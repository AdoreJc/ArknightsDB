# StoryReviewLockedInfoView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `Text _unlockCoinCount`

- `Transform _itemContainer`

- `Single _itemScale`

- `UIItemCard m_itemCard`


## Methods

- `Void ApplyUnlockCount(Int32)`

- `UIItemCard EnsureItemCard(UIItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewLockedInfoView : MonoBehaviour, IHotfixable
{
	private Text _unlockCoinCount; // 0x18
	private Transform _itemContainer; // 0x20
	private Single _itemScale; // 0x28
	private UIItemCard m_itemCard; // 0x30
	private static DelegateBridge __Hotfix0_ApplyUnlockCount; // 0x0
	private static DelegateBridge __Hotfix0_EnsureItemCard; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x275f1ec VA: 0x7594d771ec
	public Void ApplyUnlockCount(Int32 count) { }
	// RVA: 0x275f328 VA: 0x7594d77328
	public UIItemCard EnsureItemCard(UIItemViewModel cacheItemViewModel) { }
	// RVA: 0x275f5cc VA: 0x7594d775cc
	public Void .ctor() { }
}
```