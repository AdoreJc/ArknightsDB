# CampaignMissionCommonObjView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Text _textDesc`

- `Text _textProgress`

- `Slider _sliderProgress`

- `Text _textBreakFeeAdd`

- `RectTransform _panelLocked`

- `Text _textUnlock`

- `RectTransform _panelFinished`

- `RectTransform _panelConfirm`

- `Button _buttonSelf`

- `CampaignCommonMissionViewModel m_cacheModel`


## Methods

- `Void set_onClicked(Action`1)`

- `Void Render(CampaignCommonMissionViewModel)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignMissionCommonObjView : MonoBehaviour, IHotfixable
{
	private Text _textDesc; // 0x18
	private Text _textProgress; // 0x20
	private Slider _sliderProgress; // 0x28
	private Text _textBreakFeeAdd; // 0x30
	private RectTransform _panelLocked; // 0x38
	private Text _textUnlock; // 0x40
	private RectTransform _panelFinished; // 0x48
	private RectTransform _panelConfirm; // 0x50
	private Button _buttonSelf; // 0x58
	private CampaignCommonMissionViewModel m_cacheModel; // 0x60
	private Action`1 <onClicked>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Action`1 onClicked { get; set; }

	// RVA: 0x2dcdb9c VA: 0x75953e5b9c
	public Action`1 get_onClicked() { }
	// RVA: 0x2dcdc04 VA: 0x75953e5c04
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x2dcdc88 VA: 0x75953e5c88
	public Void Render(CampaignCommonMissionViewModel viewModel) { }
	// RVA: 0x2dcdf6c VA: 0x75953e5f6c
	public Void EventOnClicked() { }
	// RVA: 0x2dce018 VA: 0x75953e6018
	public Void .ctor() { }
}
```