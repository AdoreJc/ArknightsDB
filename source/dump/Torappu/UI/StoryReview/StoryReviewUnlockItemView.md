# StoryReviewUnlockItemView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `Text _unlockContent`

- `GameObject _coinConditionPanel`

- `GameObject _stageConditionPanel`

- `Button _unlockBtn`

- `Transform _customContainer`

- `GameObject _originBg`

- `StoryReviewLockedInfoView _lockInfoTypeInland`

- `StoryReviewLockedInfoView _lockInfoTypeJp`

- `StoryReviewLockedInfoView _lockInfoTypeKr`

- `StoryReviewLockedInfoView _lockInfoTypeEn`

- `StoryReviewLockedInfoView _lockInfoTypeTc`

- `String m_cachedStoryReviewId`

- `UIItemViewModel m_cacheItemViewModel`

- `StoryReviewLockedInfoView m_lockInfoInUse`

- `Boolean m_isLockInfoInited`


## Methods

- `Void ApplyData(StoryReviewViewModel, Boolean, GameObject)`

- `Void _TryRenderCustomPart(GameObject)`

- `Void _SetUnlockCoinCount(Int32)`

- `Void _RenderItem(ItemData)`

- `UIItemCard _EnsureItemCard(UIItemViewModel)`

- `String _GetUnlockCondition(PlayerStageState)`

- `StoryReviewLockedInfoView _PickLockInfoByCulture()`

- `Void EventOnStoryClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewUnlockItemView : MonoBehaviour, IHotfixable
{
	private Text _unlockContent; // 0x18
	private GameObject _coinConditionPanel; // 0x20
	private GameObject _stageConditionPanel; // 0x28
	private Button _unlockBtn; // 0x30
	private Transform _customContainer; // 0x38
	private GameObject _originBg; // 0x40
	private StoryReviewLockedInfoView _lockInfoTypeInland; // 0x48
	private StoryReviewLockedInfoView _lockInfoTypeJp; // 0x50
	private StoryReviewLockedInfoView _lockInfoTypeKr; // 0x58
	private StoryReviewLockedInfoView _lockInfoTypeEn; // 0x60
	private StoryReviewLockedInfoView _lockInfoTypeTc; // 0x68
	public Action`1 onClicked; // 0x70
	private String m_cachedStoryReviewId; // 0x78
	private UIItemViewModel m_cacheItemViewModel; // 0x80
	private StoryReviewLockedInfoView m_lockInfoInUse; // 0x88
	private Boolean m_isLockInfoInited; // 0x90
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__TryRenderCustomPart; // 0x8
	private static DelegateBridge __Hotfix0__SetUnlockCoinCount; // 0x10
	private static DelegateBridge __Hotfix0__RenderItem; // 0x18
	private static DelegateBridge __Hotfix0__EnsureItemCard; // 0x20
	private static DelegateBridge __Hotfix0__GetUnlockCondition; // 0x28
	private static DelegateBridge __Hotfix0__PickLockInfoByCulture; // 0x30
	private static DelegateBridge __Hotfix0_EventOnStoryClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x275e2b4 VA: 0x7594d762b4
	public Void ApplyData(StoryReviewViewModel storyModel, Boolean outOfTime, GameObject customPrefab) { }
	// RVA: 0x2761d9c VA: 0x7594d79d9c
	private Void _TryRenderCustomPart(GameObject prefab) { }
	// RVA: 0x2761b9c VA: 0x7594d79b9c
	private Void _SetUnlockCoinCount(Int32 count) { }
	// RVA: 0x2761a54 VA: 0x7594d79a54
	private Void _RenderItem(ItemData item) { }
	// RVA: 0x27622d0 VA: 0x7594d7a2d0
	private UIItemCard _EnsureItemCard(UIItemViewModel itemModel) { }
	// RVA: 0x2761c7c VA: 0x7594d79c7c
	private String _GetUnlockCondition(PlayerStageState stageState) { }
	// RVA: 0x2761e7c VA: 0x7594d79e7c
	private StoryReviewLockedInfoView _PickLockInfoByCulture() { }
	// RVA: 0x27623b4 VA: 0x7594d7a3b4
	public Void EventOnStoryClicked() { }
	// RVA: 0x276243c VA: 0x7594d7a43c
	public Void .ctor() { }
}
```