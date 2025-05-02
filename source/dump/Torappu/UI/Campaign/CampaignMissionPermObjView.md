# CampaignMissionPermObjView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Text _textCode`

- `Text _textName`

- `Text _textProgress`

- `Slider _sliderProgress`

- `Text _textRemainBreakFeeAdd`

- `RectTransform _panelLocked`

- `Text _textUnlock`

- `RectTransform _panelFinished`

- `Button _buttonSelf`

- `CampaignPermanentMissionViewModel m_cacheModel`


## Methods

- `Void set_onClicked(Action`1)`

- `Void Render(CampaignPermanentMissionViewModel)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignMissionPermObjView : MonoBehaviour, IHotfixable
{
	private Text _textCode; // 0x18
	private Text _textName; // 0x20
	private Text _textProgress; // 0x28
	private Slider _sliderProgress; // 0x30
	private Text _textRemainBreakFeeAdd; // 0x38
	private RectTransform _panelLocked; // 0x40
	private Text _textUnlock; // 0x48
	private RectTransform _panelFinished; // 0x50
	private Button _buttonSelf; // 0x58
	private CampaignPermanentMissionViewModel m_cacheModel; // 0x60
	private Action`1 <onClicked>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Action`1 onClicked { get; set; }

	// RVA: 0x2dce088 VA: 0x75953e6088
	public Action`1 get_onClicked() { }
	// RVA: 0x2dce0f0 VA: 0x75953e60f0
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x2dce174 VA: 0x75953e6174
	public Void Render(CampaignPermanentMissionViewModel viewModel) { }
	// RVA: 0x2dce428 VA: 0x75953e6428
	public Void EventOnClicked() { }
	// RVA: 0x2dce4c8 VA: 0x75953e64c8
	public Void .ctor() { }
}
```