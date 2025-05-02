# StageZoneWeeklyRecordView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String _rewardProgressFormat`

- `Text _textDiamondProgress`

- `Text _textDiamondCountDown`

- `Slider _sliderDiamondProgress`

- `CanvasGroup _diamondCanvasGroup`

- `Text _textTowerLowerItemProgress`

- `Slider _sliderTowerLowerItemProgress`

- `Text _textTowerHigherItemProgress`

- `Slider _sliderTowerHigherItemProgress`

- `Text _textTowerItemCountDown`

- `CanvasGroup _towerCanvasGroup`

- `Text _textItemGroupName`

- `GameObject _panelTower`


## Methods

- `Boolean _TryRenderCampaignView(StageZoneCampaignViewModel)`

- `Boolean _TryRenderTowerView(StageZoneClimbTowerViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneWeeklyRecordView : DataBinder`1
{
	private String _rewardProgressFormat; // 0x20
	private Text _textDiamondProgress; // 0x28
	private Text _textDiamondCountDown; // 0x30
	private Slider _sliderDiamondProgress; // 0x38
	private CanvasGroup _diamondCanvasGroup; // 0x40
	private Text _textTowerLowerItemProgress; // 0x48
	private Slider _sliderTowerLowerItemProgress; // 0x50
	private Text _textTowerHigherItemProgress; // 0x58
	private Slider _sliderTowerHigherItemProgress; // 0x60
	private Text _textTowerItemCountDown; // 0x68
	private CanvasGroup _towerCanvasGroup; // 0x70
	private Text _textItemGroupName; // 0x78
	private GameObject _panelTower; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__TryRenderCampaignView; // 0x8
	private static DelegateBridge __Hotfix0__TryRenderTowerView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2ef87a8 VA: 0x75955107a8
	public override Void OnValueChanged(StageZoneWeeklyRewardProperty property) { }
	// RVA: 0x2ef8880 VA: 0x7595510880
	private Boolean _TryRenderCampaignView(StageZoneCampaignViewModel viewModel) { }
	// RVA: 0x2ef8a18 VA: 0x7595510a18
	private Boolean _TryRenderTowerView(StageZoneClimbTowerViewModel viewModel) { }
	// RVA: 0x2ef8cb4 VA: 0x7595510cb4
	public Void .ctor() { }
}
```