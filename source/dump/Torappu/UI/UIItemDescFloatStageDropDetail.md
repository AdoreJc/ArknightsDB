# UIItemDescFloatStageDropDetail

**Namespace:** `Torappu.UI`


## Fields

- `Text _stageName`

- `Button _gotoButton`

- `GameObject _unlockButton`

- `GameObject _notPassButton`

- `RectTransform _autoLayout`

- `String m_stageId`

- `String m_zoneId`

- `Boolean m_isCampaign`

- `Boolean m_isClimbTower`

- `Boolean m_enableDropRoute`


## Methods

- `Void set_onRouteClicked(Action`1)`

- `Void Render(PlayerStage, StageData, OccPer, Boolean)`

- `Void RenderWeekly(String, Boolean)`

- `Void RenderCampaign(List`1, Boolean)`

- `Void RenderClimbTower(Boolean)`

- `Void _RecordCache(String, String, StageType)`

- `Void _SetButtonsGotoMode()`

- `Void _SetButtonsUnlockMode()`

- `Void EventOnGoToButtonClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemDescFloatStageDropDetail : MonoBehaviour, IHotfixable
{
	private Text _stageName; // 0x18
	private Button _gotoButton; // 0x20
	private GameObject _unlockButton; // 0x28
	private GameObject _notPassButton; // 0x30
	private GameObject[] _occPerGameObject; // 0x38
	private RectTransform _autoLayout; // 0x40
	private String m_stageId; // 0x48
	private String m_zoneId; // 0x50
	private Boolean m_isCampaign; // 0x58
	private Boolean m_isClimbTower; // 0x59
	private Boolean m_enableDropRoute; // 0x5a
	private Action`1 <onRouteClicked>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onRouteClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onRouteClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_RenderWeekly; // 0x18
	private static DelegateBridge __Hotfix0_RenderCampaign; // 0x20
	private static DelegateBridge __Hotfix0_RenderClimbTower; // 0x28
	private static DelegateBridge __Hotfix0__RecordCache; // 0x30
	private static DelegateBridge __Hotfix0__SetButtonsGotoMode; // 0x38
	private static DelegateBridge __Hotfix0__SetButtonsUnlockMode; // 0x40
	private static DelegateBridge __Hotfix0_EventOnGoToButtonClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action`1 onRouteClicked { get; set; }

	// RVA: 0x2192368 VA: 0x75947aa368
	private Action`1 get_onRouteClicked() { }
	// RVA: 0x21923d0 VA: 0x75947aa3d0
	public Void set_onRouteClicked(Action`1 value) { }
	// RVA: 0x2192454 VA: 0x75947aa454
	public Void Render(PlayerStage playerStage, StageData stageData, OccPer occPercent, Boolean enableDropRoute) { }
	// RVA: 0x21927c4 VA: 0x75947aa7c4
	public Void RenderWeekly(String zoneId, Boolean enableDropRoute) { }
	// RVA: 0x2192ad4 VA: 0x75947aaad4
	public Void RenderCampaign(List`1 stages, Boolean enbableDropRoute) { }
	// RVA: 0x2192c20 VA: 0x75947aac20
	public Void RenderClimbTower(Boolean enableDropRoute) { }
	// RVA: 0x21926f8 VA: 0x75947aa6f8
	private Void _RecordCache(String zoneId, String stageId, StageType type) { }
	// RVA: 0x21925a4 VA: 0x75947aa5a4
	private Void _SetButtonsGotoMode() { }
	// RVA: 0x2192658 VA: 0x75947aa658
	private Void _SetButtonsUnlockMode() { }
	// RVA: 0x2192d90 VA: 0x75947aad90
	public Void EventOnGoToButtonClicked() { }
	// RVA: 0x2192eb0 VA: 0x75947aaeb0
	public Void .ctor() { }
}
```