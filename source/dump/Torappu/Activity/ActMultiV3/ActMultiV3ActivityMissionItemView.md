# ActMultiV3ActivityMissionItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _inProgressGo`

- `GameObject _completedGo`

- `UIButton _confirmButton`

- `GameObject _confirmedGo`

- `Text _missionDesc`

- `Color _inProgressDescColor`

- `Color _completedDescColor`

- `Image _fillProgressImage`

- `Color _inProgressFillColor`

- `Color _completedFillColor`

- `Text _progressText`

- `Color _completedProgressColor`

- `TwoStateToggle _titleBgToggle`

- `Text _titleText`

- `Image _rewardIcon`

- `Text _rewardCountText`

- `Color _inProgressRewardCountColor`

- `Color _completedRewardCountColor`

- `String m_cachedMissionId`

- `UIStateFinder m_finder`


## Methods

- `Void Render(ActMultiV3MissionViewModel)`

- `Void OnClickConfirmMissionBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ActivityMissionItemView : MonoBehaviour, IHotfixable
{
	private GameObject _inProgressGo; // 0x18
	private GameObject _completedGo; // 0x20
	private UIButton _confirmButton; // 0x28
	private GameObject _confirmedGo; // 0x30
	private Text _missionDesc; // 0x38
	private Color _inProgressDescColor; // 0x40
	private Color _completedDescColor; // 0x50
	private Image _fillProgressImage; // 0x60
	private Color _inProgressFillColor; // 0x68
	private Color _completedFillColor; // 0x78
	private Text _progressText; // 0x88
	private Color _completedProgressColor; // 0x90
	private TwoStateToggle _titleBgToggle; // 0xa0
	private Text _titleText; // 0xa8
	private Image _rewardIcon; // 0xb0
	private Text _rewardCountText; // 0xb8
	private Color _inProgressRewardCountColor; // 0xc0
	private Color _completedRewardCountColor; // 0xd0
	private String m_cachedMissionId; // 0xe0
	private UIStateFinder m_finder; // 0xe8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickConfirmMissionBtn; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x311a840 VA: 0x7595732840
	public Void Render(ActMultiV3MissionViewModel model) { }
	// RVA: 0x311ad68 VA: 0x7595732d68
	public Void OnClickConfirmMissionBtn() { }
	// RVA: 0x311ae68 VA: 0x7595732e68
	public Void .ctor() { }
}
```