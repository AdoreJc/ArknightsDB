# CrisisV2MissionItem

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Color _colorTitleComplete`

- `Color _colorTitleUncomplete`

- `Color _colorDescComplete`

- `Color _colorDescUncomplete`

- `Single _notClaimedAlpha`

- `Single _claimedAlpha`

- `GameObject _unlockPart`

- `TwoStateToggle _jumpToSlotToggle`

- `GameObject _completePart`

- `GameObject _completeOutLight`

- `GameObject _claimedMask`

- `Text _titleText`

- `Text _descText`

- `SimpleLayoutContent _rewardContent`

- `CanvasGroup _rootCanvasGroup`

- `CanvasGroup _breathLightCanvasGroup`

- `CrisisV2MissionItemModel m_viewModel`

- `Boolean m_hasInited`

- `RewardAdapter m_adapter`

- `UIStateFinder m_stateFinder`

- `Tween m_breathLightTween`


## Methods

- `Void Render(CrisisV2MissionItemModel)`

- `Void _InitIfNot()`

- `Void _PlayBreathLightTween(Boolean)`

- `Void OnJumpToSlotClicked()`

- `Void OnClaimSingleMissionClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MissionItem : MonoBehaviour, IHotfixable
{
	private Color _colorTitleComplete; // 0x18
	private Color _colorTitleUncomplete; // 0x28
	private Color _colorDescComplete; // 0x38
	private Color _colorDescUncomplete; // 0x48
	private Single _notClaimedAlpha; // 0x58
	private Single _claimedAlpha; // 0x5c
	private GameObject _unlockPart; // 0x60
	private TwoStateToggle _jumpToSlotToggle; // 0x68
	private GameObject _completePart; // 0x70
	private GameObject _completeOutLight; // 0x78
	private GameObject _claimedMask; // 0x80
	private Text _titleText; // 0x88
	private Text _descText; // 0x90
	private SimpleLayoutContent _rewardContent; // 0x98
	private CanvasGroup _rootCanvasGroup; // 0xa0
	private CanvasGroup _breathLightCanvasGroup; // 0xa8
	private CrisisV2MissionItemModel m_viewModel; // 0xb0
	private Boolean m_hasInited; // 0xb8
	private RewardAdapter m_adapter; // 0xc0
	private UIStateFinder m_stateFinder; // 0xc8
	private Tween m_breathLightTween; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__PlayBreathLightTween; // 0x10
	private static DelegateBridge __Hotfix0_OnJumpToSlotClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnClaimSingleMissionClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2bfc070 VA: 0x7595214070
	public Void Render(CrisisV2MissionItemModel viewModel) { }
	// RVA: 0x2bfc2c8 VA: 0x75952142c8
	private Void _InitIfNot() { }
	// RVA: 0x2bfc398 VA: 0x7595214398
	private Void _PlayBreathLightTween(Boolean isPlay) { }
	// RVA: 0x2bfc63c VA: 0x759521463c
	public Void OnJumpToSlotClicked() { }
	// RVA: 0x2bfc724 VA: 0x7595214724
	public Void OnClaimSingleMissionClicked() { }
	// RVA: 0x2bfc808 VA: 0x7595214808
	public Void .ctor() { }
}
```