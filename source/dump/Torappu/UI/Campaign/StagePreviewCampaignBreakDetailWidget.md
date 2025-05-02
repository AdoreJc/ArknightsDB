# StagePreviewCampaignBreakDetailWidget

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Single _itemCardScale`

- `Text _killCntText`

- `Text _descriptionText`

- `Text _progressText`

- `Slider _progressSlider`

- `SimpleLayoutContent _rewardContainer`

- `RectTransform _lastFeeUpReward`

- `Button _ableToClick`

- `RewardAdapter m_rewardAdapter`

- `BreakLadderViewModel m_breakModel`


## Methods

- `Void set_onConfirmed(Action`1)`

- `Void Render(BreakLadderViewModel, CampaignStateViewModel)`

- `Void OnConfirmButtonClicked()`

- `Void _RenderRewards(IList`1, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class StagePreviewCampaignBreakDetailWidget : MonoBehaviour, IHotfixable
{
	private Single _itemCardScale; // 0x18
	private Text _killCntText; // 0x20
	private Text _descriptionText; // 0x28
	private Text _progressText; // 0x30
	private Slider _progressSlider; // 0x38
	private SimpleLayoutContent _rewardContainer; // 0x40
	private RectTransform _lastFeeUpReward; // 0x48
	private RectTransform[] _states; // 0x50
	private Button _ableToClick; // 0x58
	private RewardAdapter m_rewardAdapter; // 0x60
	private BreakLadderViewModel m_breakModel; // 0x68
	private Action`1 m_onConfirmed; // 0x70
	private static DelegateBridge __Hotfix0_set_onConfirmed; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnConfirmButtonClicked; // 0x10
	private static DelegateBridge __Hotfix0__RenderRewards; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Action`1 onConfirmed { set; }

	// RVA: 0x2de1254 VA: 0x75953f9254
	public Void set_onConfirmed(Action`1 value) { }
	// RVA: 0x2de12d8 VA: 0x75953f92d8
	public Void Render(BreakLadderViewModel breakModel, CampaignStateViewModel campModel) { }
	// RVA: 0x2de1914 VA: 0x75953f9914
	public Void OnConfirmButtonClicked() { }
	// RVA: 0x2de17d0 VA: 0x75953f97d0
	private Void _RenderRewards(IList`1 items, Boolean hasCampFeeUp) { }
	// RVA: 0x2de19b0 VA: 0x75953f99b0
	public Void .ctor() { }
}
```