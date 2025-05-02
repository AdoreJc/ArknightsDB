# CampaignAutoFastBattleSwitchView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `UIAnimationLocation _animFastOn`

- `TwoStateToggle _toggleAutoBattle`

- `GameObject _storyBtnFastBtl`

- `GameObject _storyAreaSwitch`

- `GameObject _storyAreaStartBtl`

- `CampAutoSwitchOptions m_options`

- `Boolean m_isInited`

- `EnableFastBattle m_model`

- `AnimationSwitchTween m_fastSwitch`

- `String m_lastStageId`


## Methods

- `Void Init(CampAutoSwitchOptions)`

- `Void UpdateView(AutoCampConfigModel)`

- `Void _TryRaiseAVGSignalAndRegisterObjs()`

- `Void EventOnAutoBattleClicked()`

- `Void EventOnFastBattleClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignAutoFastBattleSwitchView : MonoBehaviour, ICampaignAutoSwitchView, IHotfixable
{
	private UIAnimationLocation _animFastOn; // 0x18
	private TwoStateToggle _toggleAutoBattle; // 0x28
	private GameObject _storyBtnFastBtl; // 0x30
	private GameObject _storyAreaSwitch; // 0x38
	private GameObject _storyAreaStartBtl; // 0x40
	private CampAutoSwitchOptions m_options; // 0x48
	private Boolean m_isInited; // 0x60
	private EnableFastBattle m_model; // 0x64
	private AnimationSwitchTween m_fastSwitch; // 0x68
	private String m_lastStageId; // 0x70
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0__TryRaiseAVGSignalAndRegisterObjs; // 0x10
	private static DelegateBridge __Hotfix0_EventOnAutoBattleClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnFastBattleClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2ddb198 VA: 0x75953f3198
	public Void Init(CampAutoSwitchOptions options) { }
	// RVA: 0x2ddb2dc VA: 0x75953f32dc
	public Void UpdateView(AutoCampConfigModel viewModel) { }
	// RVA: 0x2ddb448 VA: 0x75953f3448
	private Void _TryRaiseAVGSignalAndRegisterObjs() { }
	// RVA: 0x2ddb58c VA: 0x75953f358c
	public Void EventOnAutoBattleClicked() { }
	// RVA: 0x2ddb610 VA: 0x75953f3610
	public Void EventOnFastBattleClicked() { }
	// RVA: 0x2ddb694 VA: 0x75953f3694
	public Void .ctor() { }
}
```