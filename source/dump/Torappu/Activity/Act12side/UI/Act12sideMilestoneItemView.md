# Act12sideMilestoneItemView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `TwoStateToggle _itemTypeToggle`

- `TwoStateToggle _rewardStateToggle`

- `CanvasGroup _itemCanvasGroup`

- `Single _completedAlpah`

- `RectTransform _rewardRoot`

- `RectTransform _repRewardRoot`

- `Single _rewardScale`

- `GameObject _completePartGo`

- `Text _textGoal`

- `Image _imgNormal`

- `Image _imgActive`

- `Image _imgCompleted`

- `Sprite _spriteNormal1`

- `Sprite _spriteActive1`

- `Sprite _spriteCompleted1`

- `Sprite _spriteNormal2`

- `Sprite _spriteActive2`

- `Sprite _spriteCompleted2`

- `Image _imgTitle`

- `GameObject _repIcon`

- `Act12sideMilestoneItemModel m_itemModel`

- `UIItemCard m_itemCard`

- `UIItemCard m_repItemCard`

- `UIItemViewModel m_rewardViewModel`

- `Act12SideMissionReplicateTweenWrapper m_repTween`

- `Boolean m_isInited`


## Methods

- `Void set_onMilestoneClick(Action`1)`

- `Void Render(Act12sideMilestoneItemModel)`

- `Void _UpdateItemDisplay()`

- `Void _RenderRewardItem(UIItemViewModel)`

- `Void _RenderRepRewardItem(UIItemViewModel)`

- `Void _InitIfNot()`

- `Void OnRewardMilestone()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideMilestoneItemView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _itemTypeToggle; // 0x18
	private TwoStateToggle _rewardStateToggle; // 0x20
	private CanvasGroup _itemCanvasGroup; // 0x28
	private Single _completedAlpah; // 0x30
	private RectTransform _rewardRoot; // 0x38
	private RectTransform _repRewardRoot; // 0x40
	private Single _rewardScale; // 0x48
	private GameObject _completePartGo; // 0x50
	private Text _textGoal; // 0x58
	private Image _imgNormal; // 0x60
	private Image _imgActive; // 0x68
	private Image _imgCompleted; // 0x70
	private Sprite _spriteNormal1; // 0x78
	private Sprite _spriteActive1; // 0x80
	private Sprite _spriteCompleted1; // 0x88
	private Sprite _spriteNormal2; // 0x90
	private Sprite _spriteActive2; // 0x98
	private Sprite _spriteCompleted2; // 0xa0
	private Image _imgTitle; // 0xa8
	private Sprite[] _spriteTitleList; // 0xb0
	private GameObject _repIcon; // 0xb8
	private Act12sideMilestoneItemModel m_itemModel; // 0xc0
	private UIItemCard m_itemCard; // 0xc8
	private UIItemCard m_repItemCard; // 0xd0
	private UIItemViewModel m_rewardViewModel; // 0xd8
	private Act12SideMissionReplicateTweenWrapper m_repTween; // 0xe0
	private Boolean m_isInited; // 0xe8
	private Action`1 <onMilestoneClick>k__BackingField; // 0xf0
	private static DelegateBridge __Hotfix0_get_onMilestoneClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onMilestoneClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__UpdateItemDisplay; // 0x18
	private static DelegateBridge __Hotfix0__RenderRewardItem; // 0x20
	private static DelegateBridge __Hotfix0__RenderRepRewardItem; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_OnRewardMilestone; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Action`1 onMilestoneClick { get; set; }

	// RVA: 0x3464594 VA: 0x7595a7c594
	private Action`1 get_onMilestoneClick() { }
	// RVA: 0x34645fc VA: 0x7595a7c5fc
	public Void set_onMilestoneClick(Action`1 value) { }
	// RVA: 0x3464680 VA: 0x7595a7c680
	public Void Render(Act12sideMilestoneItemModel itemModel) { }
	// RVA: 0x3464a48 VA: 0x7595a7ca48
	private Void _UpdateItemDisplay() { }
	// RVA: 0x3464df8 VA: 0x7595a7cdf8
	private Void _RenderRewardItem(UIItemViewModel model) { }
	// RVA: 0x3465484 VA: 0x7595a7d484
	private Void _RenderRepRewardItem(UIItemViewModel model) { }
	// RVA: 0x34648ec VA: 0x7595a7c8ec
	private Void _InitIfNot() { }
	// RVA: 0x3465790 VA: 0x7595a7d790
	public Void OnRewardMilestone() { }
	// RVA: 0x3465848 VA: 0x7595a7d848
	public Void .ctor() { }
}
```