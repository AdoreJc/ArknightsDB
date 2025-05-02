# StageZoneCampaignView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _textRotateRemainTime`

- `UIAtlasImage _imgRemainTimeBkg`

- `Image _imageRotateZone`

- `Image _imageRotateZoneBlack`

- `Text _textRotateZoneName`

- `Text _textRotateStageName`

- `CanvasGroup _canvasBtnRotate`

- `GameObject _panelRotateUnlock`

- `Text _textRotateUnlock`

- `Action <onRendered>k__BackingField`

- `Action <onClicked>k__BackingField`

- `Action <onRotateStageClicked>k__BackingField`


## Properties

- `Action onRendered`

- `Action onClicked`

- `Action onRotateStageClicked`


## Methods

- `Action get_onRendered()`

- `Void set_onRendered(Action)`

- `Action get_onClicked()`

- `Void set_onClicked(Action)`

- `Action get_onRotateStageClicked()`

- `Void set_onRotateStageClicked(Action)`

- `Void EventOnClicked()`

- `Void EventOnRotateStageClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneCampaignView : DataBinder`1, IHotfixable
{
	private Text _textRotateRemainTime; // 0x20
	private UIAtlasImage _imgRemainTimeBkg; // 0x28
	private EndTimeCountDownBgStyle[] _endTimeStyles; // 0x30
	private Image _imageRotateZone; // 0x38
	private Image _imageRotateZoneBlack; // 0x40
	private Text _textRotateZoneName; // 0x48
	private Text _textRotateStageName; // 0x50
	private CanvasGroup _canvasBtnRotate; // 0x58
	private GameObject _panelRotateUnlock; // 0x60
	private Text _textRotateUnlock; // 0x68
	private Action <onRendered>k__BackingField; // 0x70
	private Action <onClicked>k__BackingField; // 0x78
	private Action <onRotateStageClicked>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_onRendered; // 0x0
	private static DelegateBridge __Hotfix0_set_onRendered; // 0x8
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onRotateStageClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onRotateStageClicked; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnRotateStageClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Action onRendered { get; set; }
	public Action onClicked { get; set; }
	public Action onRotateStageClicked { get; set; }

	// RVA: 0x2ef76ac VA: 0x759550f6ac
	public Action get_onRendered() { }
	// RVA: 0x2ef7714 VA: 0x759550f714
	public Void set_onRendered(Action value) { }
	// RVA: 0x2ef7798 VA: 0x759550f798
	public Action get_onClicked() { }
	// RVA: 0x2ef7800 VA: 0x759550f800
	public Void set_onClicked(Action value) { }
	// RVA: 0x2ef7884 VA: 0x759550f884
	public Action get_onRotateStageClicked() { }
	// RVA: 0x2ef78ec VA: 0x759550f8ec
	public Void set_onRotateStageClicked(Action value) { }
	// RVA: 0x2ef7970 VA: 0x759550f970
	public override Void OnValueChanged(StageZoneWeeklyRewardProperty property) { }
	// RVA: 0x2ef7d04 VA: 0x759550fd04
	public Void EventOnClicked() { }
	// RVA: 0x2ef7da0 VA: 0x759550fda0
	public Void EventOnRotateStageClicked() { }
	// RVA: 0x2ef7e3c VA: 0x759550fe3c
	public Void .ctor() { }
}
```