# SixStarMilestoneItemView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _textStageName`

- `GameObject _panelFirstItem`

- `GameObject _panelUnlockStage`

- `GameObject _panelUncomplete`

- `GameObject _panelComplete`

- `GameObject _panelRewardConfirmed`

- `GameObject _panelUnlockStageUncomplete`

- `CanvasGroup _canvasGroupReward`

- `CanvasGroup _canvasGroupItemCard`

- `RectTransform _itemCardContainer`

- `Single _scaleItemCard`

- `UIItemCard m_itemCard`

- `UICompDialogFinder m_dialogFinder`

- `Boolean m_hasInited`


## Methods

- `Void Render(SixStarMilestoneItemViewModel, Boolean)`

- `Void EventOnClaimAllClicked()`

- `Void _InitIfNot()`

- `Void _EventOnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarMilestoneItemView : MonoBehaviour, IHotfixable
{
	private const Single ALPHA_REWARD_UNCOMPLETE; // 0x0
	private const Single ALPHA_ITEM_CARD_UNCOMPLETE; // 0x0
	private const Single ALPHA_COMPLETE; // 0x0
	private Text[] _textPoint; // 0x18
	private Text _textStageName; // 0x20
	private GameObject _panelFirstItem; // 0x28
	private GameObject _panelUnlockStage; // 0x30
	private GameObject[] _panelRewardItem; // 0x38
	private GameObject _panelUncomplete; // 0x40
	private GameObject _panelComplete; // 0x48
	private GameObject[] _panelRewardFinish; // 0x50
	private GameObject _panelRewardConfirmed; // 0x58
	private GameObject _panelUnlockStageUncomplete; // 0x60
	private CanvasGroup _canvasGroupReward; // 0x68
	private CanvasGroup _canvasGroupItemCard; // 0x70
	private RectTransform _itemCardContainer; // 0x78
	private Single _scaleItemCard; // 0x80
	private UIItemCard m_itemCard; // 0x88
	private UICompDialogFinder m_dialogFinder; // 0x90
	private Boolean m_hasInited; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClaimAllClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__EventOnItemCardClicked; // 0x18
	private static DelegateBridge __Hotfix0__SetGroupActiveIfNecessary; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2f49a28 VA: 0x7595561a28
	public Void Render(SixStarMilestoneItemViewModel viewModel, Boolean isFirstItem) { }
	// RVA: 0x2f4af04 VA: 0x7595562f04
	public Void EventOnClaimAllClicked() { }
	// RVA: 0x2f4ac1c VA: 0x7595562c1c
	private Void _InitIfNot() { }
	// RVA: 0x2f4afa8 VA: 0x7595562fa8
	private Void _EventOnItemCardClicked(Int32 _) { }
	// RVA: 0x2f4ae24 VA: 0x7595562e24
	private static Void _SetGroupActiveIfNecessary(GameObject[] gameObject, Boolean isActive) { }
	// RVA: 0x2f4b0b0 VA: 0x75955630b0
	public Void .ctor() { }
}
```