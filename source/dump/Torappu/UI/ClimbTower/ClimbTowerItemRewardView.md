# ClimbTowerItemRewardView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String _rewardProgressFormat`

- `Text _textLowerProgress`

- `Slider _sliderLowerProgress`

- `Text _textLowerItemName`

- `Text _textHigherProgress`

- `Slider _sliderHigherProgress`

- `Text _textHigherItemName`

- `Text _textCountDown`

- `TwoStateToggle _toggleBtnBkg`

- `Action <onClicked>k__BackingField`


## Properties

- `Action onClicked`


## Methods

- `Action get_onClicked()`

- `Void set_onClicked(Action)`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerItemRewardView : DataBinder`1, IHotfixable
{
	private String _rewardProgressFormat; // 0x20
	private Text _textLowerProgress; // 0x28
	private Slider _sliderLowerProgress; // 0x30
	private Text _textLowerItemName; // 0x38
	private Text _textHigherProgress; // 0x40
	private Slider _sliderHigherProgress; // 0x48
	private Text _textHigherItemName; // 0x50
	private Text _textCountDown; // 0x58
	private TwoStateToggle _toggleBtnBkg; // 0x60
	private Action <onClicked>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action onClicked { get; set; }

	// RVA: 0x2c69c98 VA: 0x7595281c98
	private Action get_onClicked() { }
	// RVA: 0x2c69d00 VA: 0x7595281d00
	public Void set_onClicked(Action value) { }
	// RVA: 0x2c69d84 VA: 0x7595281d84
	public Void OnClicked() { }
	// RVA: 0x2c69e20 VA: 0x7595281e20
	public override Void OnValueChanged(ClimbTowerItemRewardProperty property) { }
	// RVA: 0x2c6a12c VA: 0x759528212c
	public Void .ctor() { }
}
```