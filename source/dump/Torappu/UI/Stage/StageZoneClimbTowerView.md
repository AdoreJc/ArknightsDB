# StageZoneClimbTowerView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `TwoStateToggle _toggleBtn`

- `CanvasGroup _climbTowerBtnCanvas`

- `TwoStateToggle _toggleInBattle`

- `TwoStateToggle _toggleBattleHard`

- `Text _towerName`

- `Text _towerSubName`

- `Image _towerIcon`

- `Image _towerIconBlack`

- `Text _seasonNum`

- `Text _seasonName`

- `Text _textSeasonRemainTime`

- `UIAtlasImage _imgRemainTimeBkg`

- `Action <onClicked>k__BackingField`

- `Action <onRotateStageClicked>k__BackingField`

- `UIPage <page>k__BackingField`


## Properties

- `Action onClicked`

- `Action onRotateStageClicked`

- `UIPage page`


## Methods

- `Action get_onClicked()`

- `Void set_onClicked(Action)`

- `Action get_onRotateStageClicked()`

- `Void set_onRotateStageClicked(Action)`

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void EventOnClicked()`

- `Void EventOnRotateStageClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneClimbTowerView : DataBinder`1
{
	private TwoStateToggle _toggleBtn; // 0x20
	private CanvasGroup _climbTowerBtnCanvas; // 0x28
	private TwoStateToggle _toggleInBattle; // 0x30
	private TwoStateToggle _toggleBattleHard; // 0x38
	private Text _towerName; // 0x40
	private Text _towerSubName; // 0x48
	private Image _towerIcon; // 0x50
	private Image _towerIconBlack; // 0x58
	private Text _seasonNum; // 0x60
	private Text _seasonName; // 0x68
	private Text _textSeasonRemainTime; // 0x70
	private UIAtlasImage _imgRemainTimeBkg; // 0x78
	private EndTimeCountDownBgStyle[] _endTimeStyles; // 0x80
	private Action <onClicked>k__BackingField; // 0x88
	private Action <onRotateStageClicked>k__BackingField; // 0x90
	private UIPage <page>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onRotateStageClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onRotateStageClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_page; // 0x20
	private static DelegateBridge __Hotfix0_set_page; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnRotateStageClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Action onClicked { get; set; }
	public Action onRotateStageClicked { get; set; }
	private UIPage page { get; set; }

	// RVA: 0x2ef7ecc VA: 0x759550fecc
	public Action get_onClicked() { }
	// RVA: 0x2ef7f34 VA: 0x759550ff34
	public Void set_onClicked(Action value) { }
	// RVA: 0x2ef7fb8 VA: 0x759550ffb8
	public Action get_onRotateStageClicked() { }
	// RVA: 0x2ef8020 VA: 0x7595510020
	public Void set_onRotateStageClicked(Action value) { }
	// RVA: 0x2ef80a4 VA: 0x75955100a4
	private UIPage get_page() { }
	// RVA: 0x2ef810c VA: 0x759551010c
	public Void set_page(UIPage value) { }
	// RVA: 0x2ef8190 VA: 0x7595510190
	public override Void OnValueChanged(StageZoneWeeklyRewardProperty property) { }
	// RVA: 0x2ef85e0 VA: 0x75955105e0
	public Void EventOnClicked() { }
	// RVA: 0x2ef867c VA: 0x759551067c
	public Void EventOnRotateStageClicked() { }
	// RVA: 0x2ef8718 VA: 0x7595510718
	public Void .ctor() { }
}
```