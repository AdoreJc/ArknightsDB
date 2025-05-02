# CampaignFeeView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Text _textCountDown`

- `Text _textProgress`

- `Slider _sliderProgress`

- `Image _imageNotFull`

- `Image _imageHasUnconfirmed`

- `Action <onClicked>k__BackingField`


## Properties

- `Action onClicked`


## Methods

- `Action get_onClicked()`

- `Void set_onClicked(Action)`

- `Void EventOnClicked()`

- `Void _Render(CampaignFeeViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignFeeView : DataBinder`1
{
	private const String TEXT_PROGRESS_FORMAT; // 0x0
	private Text _textCountDown; // 0x20
	private Text _textProgress; // 0x28
	private Slider _sliderProgress; // 0x30
	private Image _imageNotFull; // 0x38
	private Image _imageHasUnconfirmed; // 0x40
	private Action <onClicked>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Action onClicked { get; set; }

	// RVA: 0x2dcd1ec VA: 0x75953e51ec
	public Action get_onClicked() { }
	// RVA: 0x2dcd254 VA: 0x75953e5254
	public Void set_onClicked(Action value) { }
	// RVA: 0x2dcd2d8 VA: 0x75953e52d8
	public override Void OnValueChanged(CampaignFeeViewProperty prop) { }
	// RVA: 0x2dcd584 VA: 0x75953e5584
	public Void EventOnClicked() { }
	// RVA: 0x2dcd37c VA: 0x75953e537c
	private Void _Render(CampaignFeeViewModel viewModel) { }
	// RVA: 0x2dcd620 VA: 0x75953e5620
	public Void .ctor() { }
}
```