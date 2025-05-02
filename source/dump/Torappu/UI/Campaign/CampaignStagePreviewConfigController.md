# CampaignStagePreviewConfigController

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `CampaignAutoDefaultSwitchView _dftAutoBattle`

- `Transform _fastAutoBattleHolder`

- `CampaignAutoFastBattleSwitchView _fastAutoPrefab`

- `GameObject _panelFastTtkCost`

- `GameObject _panelFastTktInfo`

- `Text _textFastTktCount`

- `Boolean m_isInited`

- `CampaignAutoFastBattleSwitchView m_fastAutoBattle`

- `CampAutoSwitchOptions m_autoBattleOptions`

- `Action m_onFastCampInfoClicked`


## Methods

- `Void Init(InitOptions, CampaignSelectStageViewProperty)`

- `Void _UpdateDefaultSwitch(AutoCampConfigModel)`

- `Void _UpdateFastBattleSwitch(AutoCampConfigModel)`

- `Void EventOnFastCampInfoClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignStagePreviewConfigController : DataBinder`1
{
	private CampaignAutoDefaultSwitchView _dftAutoBattle; // 0x20
	private Transform _fastAutoBattleHolder; // 0x28
	private CampaignAutoFastBattleSwitchView _fastAutoPrefab; // 0x30
	private GameObject _panelFastTtkCost; // 0x38
	private GameObject _panelFastTktInfo; // 0x40
	private Text _textFastTktCount; // 0x48
	private Boolean m_isInited; // 0x50
	private CampaignAutoFastBattleSwitchView m_fastAutoBattle; // 0x58
	private CampAutoSwitchOptions m_autoBattleOptions; // 0x60
	private Action m_onFastCampInfoClicked; // 0x78
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__UpdateDefaultSwitch; // 0x10
	private static DelegateBridge __Hotfix0__UpdateFastBattleSwitch; // 0x18
	private static DelegateBridge __Hotfix0_EventOnFastCampInfoClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2de0174 VA: 0x75953f8174
	public Void Init(InitOptions options, CampaignSelectStageViewProperty property) { }
	// RVA: 0x2de0320 VA: 0x75953f8320
	public override Void OnValueChanged(CampaignSelectStageViewProperty property) { }
	// RVA: 0x2de0464 VA: 0x75953f8464
	private Void _UpdateDefaultSwitch(AutoCampConfigModel model) { }
	// RVA: 0x2de0530 VA: 0x75953f8530
	private Void _UpdateFastBattleSwitch(AutoCampConfigModel model) { }
	// RVA: 0x2de06d4 VA: 0x75953f86d4
	public Void EventOnFastCampInfoClicked() { }
	// RVA: 0x2de0758 VA: 0x75953f8758
	public Void .ctor() { }
}
```