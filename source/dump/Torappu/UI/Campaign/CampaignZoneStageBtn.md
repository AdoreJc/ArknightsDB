# CampaignZoneStageBtn

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `UIStringEvent onClickEvent`

- `GameObject _selectPart`

- `EasyInstancePool _breakRewardTogglePool`

- `Button _stageButton`

- `RectTransform _trackPointHolder`

- `Text _stageNameText`

- `Text _stageCodeText`

- `Text _stageNameText2`

- `Text _stageCodeText2`

- `GameObject _activePart`

- `GameObject _unopenPart`

- `GameObject _lockedBack`

- `Text _remainTime`

- `Text _lockedState`

- `GameObject _rotateObj`

- `GameObject _trainingObj`

- `Image _backImg`

- `GameObject _isAllOpenObj`

- `GameObject m_trackPoint`

- `CampaignStageMapViewModel m_cacheViewModel`


## Methods

- `Void RenderStage(CampaignStageMapViewModel)`

- `Boolean ApplySelect(String)`

- `Void OnClick()`

- `Void _RenderTrackPoint(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZoneStageBtn : MonoBehaviour, IHotfixable
{
	public UIStringEvent onClickEvent; // 0x18
	private GameObject _selectPart; // 0x20
	private EasyInstancePool _breakRewardTogglePool; // 0x28
	private Button _stageButton; // 0x30
	private RectTransform _trackPointHolder; // 0x38
	private Text _stageNameText; // 0x40
	private Text _stageCodeText; // 0x48
	private Text _stageNameText2; // 0x50
	private Text _stageCodeText2; // 0x58
	private GameObject _activePart; // 0x60
	private GameObject _unopenPart; // 0x68
	private GameObject _lockedBack; // 0x70
	private Text _remainTime; // 0x78
	private Text _lockedState; // 0x80
	private GameObject _rotateObj; // 0x88
	private GameObject _trainingObj; // 0x90
	private Image _backImg; // 0x98
	private GameObject _isAllOpenObj; // 0xa0
	private GameObject m_trackPoint; // 0xa8
	private CampaignStageMapViewModel m_cacheViewModel; // 0xb0
	private static DelegateBridge __Hotfix0_RenderStage; // 0x0
	private static DelegateBridge __Hotfix0_ApplySelect; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0__RenderTrackPoint; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2e4ade4 VA: 0x7595462de4
	public Void RenderStage(CampaignStageMapViewModel viewModel) { }
	// RVA: 0x2e4b89c VA: 0x759546389c
	public Boolean ApplySelect(String stageId) { }
	// RVA: 0x2e54508 VA: 0x759546c508
	public Void OnClick() { }
	// RVA: 0x2e54304 VA: 0x759546c304
	private Void _RenderTrackPoint(Boolean hasUnconfirmed) { }
	// RVA: 0x2e545a4 VA: 0x759546c5a4
	public Void .ctor() { }
}
```