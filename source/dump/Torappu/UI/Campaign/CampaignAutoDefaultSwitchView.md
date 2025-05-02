# CampaignAutoDefaultSwitchView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `GameObject _panelLocked`

- `GameObject _panelUnlock`

- `GameObject _panelFastBattle`

- `TwoStateToggle _toggle`

- `CampAutoSwitchOptions m_options`

- `Boolean m_isInited`

- `AutoBattleOnly m_model`


## Methods

- `Void Init(CampAutoSwitchOptions)`

- `Void UpdateView(AutoCampConfigModel)`

- `Void EventOnAutoBattleClicked()`

- `Void EventOnFastBattleClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignAutoDefaultSwitchView : MonoBehaviour, ICampaignAutoSwitchView, IHotfixable
{
	private GameObject _panelLocked; // 0x18
	private GameObject _panelUnlock; // 0x20
	private GameObject _panelFastBattle; // 0x28
	private TwoStateToggle _toggle; // 0x30
	private CampAutoSwitchOptions m_options; // 0x38
	private Boolean m_isInited; // 0x50
	private AutoBattleOnly m_model; // 0x54
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_EventOnAutoBattleClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnFastBattleClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2ddae7c VA: 0x75953f2e7c
	public Void Init(CampAutoSwitchOptions options) { }
	// RVA: 0x2ddaf34 VA: 0x75953f2f34
	public Void UpdateView(AutoCampConfigModel viewModel) { }
	// RVA: 0x2ddb020 VA: 0x75953f3020
	public Void EventOnAutoBattleClicked() { }
	// RVA: 0x2ddb0a4 VA: 0x75953f30a4
	public Void EventOnFastBattleClicked() { }
	// RVA: 0x2ddb128 VA: 0x75953f3128
	public Void .ctor() { }
}
```