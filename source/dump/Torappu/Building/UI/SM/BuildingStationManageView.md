# BuildingStationManageView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `CanvasGroup _workPanel`

- `CanvasGroup _dormPanel`

- `BuildingStationManageWorkView _workView`

- `BuildingStationManageDormView _dormView`

- `UIAnimationLocation _switchToWork`

- `UIAnimationLocation _switchToRest`

- `GameObject _switchBtnTrackPoint`

- `Action onSwitch`

- `Boolean m_hasInited`

- `FadeSwitchTween m_workPanelShowTween`

- `FadeSwitchTween m_dormPanelShowTween`

- `UIBiAnimClipSwitchTween m_switchTween`


## Methods

- `Void EventOnSwitchClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingStationManageView : DataBinder`1
{
	private CanvasGroup _workPanel; // 0x20
	private CanvasGroup _dormPanel; // 0x28
	private BuildingStationManageWorkView _workView; // 0x30
	private BuildingStationManageDormView _dormView; // 0x38
	private UIAnimationLocation _switchToWork; // 0x40
	private UIAnimationLocation _switchToRest; // 0x50
	private GameObject _switchBtnTrackPoint; // 0x60
	public Action onSwitch; // 0x68
	private Boolean m_hasInited; // 0x70
	private FadeSwitchTween m_workPanelShowTween; // 0x78
	private FadeSwitchTween m_dormPanelShowTween; // 0x80
	private UIBiAnimClipSwitchTween m_switchTween; // 0x88
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnSwitchClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3db14f0 VA: 0x75963c94f0
	public override Void OnValueChanged(StationManageViewProp property) { }
	// RVA: 0x3db1bd0 VA: 0x75963c9bd0
	public Void EventOnSwitchClicked() { }
	// RVA: 0x3db170c VA: 0x75963c970c
	private Void _InitIfNot() { }
	// RVA: 0x3db1c54 VA: 0x75963c9c54
	public Void .ctor() { }
}
```