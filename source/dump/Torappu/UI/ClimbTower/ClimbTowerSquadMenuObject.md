# ClimbTowerSquadMenuObject

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textSquadCount`

- `CanvasGroup _canvasNormal`

- `CanvasGroup _canvasSelected`

- `CanvasGroup _canvasSelectedOutline`

- `GameObject _panelFold`

- `GameObject _raycastBlocker`

- `ShowSwitchTween m_selectedSwitchTween`

- `FadeSwitchTween m_outlineSwitchTween`

- `Boolean m_hasInited`

- `Boolean m_tacticalBuffWindowShow`

- `ButtonState m_state`


## Properties

- `ButtonState state`


## Methods

- `ButtonState get_state()`

- `Void _InitIfNot()`

- `Void _RefreshCanvas(Boolean)`

- `Void OnTacticalBuffWindowShowStatusUpdated(Boolean)`

- `Void SetState(ButtonState, Boolean)`

- `Void OnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadMenuObject : ClimbTowerMenuObject
{
	private Text _textSquadCount; // 0x20
	private CanvasGroup _canvasNormal; // 0x28
	private CanvasGroup _canvasSelected; // 0x30
	private CanvasGroup _canvasSelectedOutline; // 0x38
	private GameObject _panelFold; // 0x40
	private GameObject _raycastBlocker; // 0x48
	private ShowSwitchTween m_selectedSwitchTween; // 0x50
	private FadeSwitchTween m_outlineSwitchTween; // 0x58
	private Boolean m_hasInited; // 0x60
	private Boolean m_tacticalBuffWindowShow; // 0x61
	private ButtonState m_state; // 0x64
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RefreshCanvas; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_OnTacticalBuffWindowShowStatusUpdated; // 0x20
	private static DelegateBridge __Hotfix0_SetState; // 0x28
	private static DelegateBridge __Hotfix0_OnBtnClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public ButtonState state { get; }

	// RVA: 0x2c85640 VA: 0x759529d640
	public ButtonState get_state() { }
	// RVA: 0x2c856a8 VA: 0x759529d6a8
	private Void _InitIfNot() { }
	// RVA: 0x2c85874 VA: 0x759529d874
	private Void _RefreshCanvas(Boolean fastMode) { }
	// RVA: 0x2c859b0 VA: 0x759529d9b0
	public override Void Render(ClimbTowerMenuViewModel viewModel) { }
	// RVA: 0x2c85a70 VA: 0x759529da70
	public Void OnTacticalBuffWindowShowStatusUpdated(Boolean isShow) { }
	// RVA: 0x2c85af8 VA: 0x759529daf8
	public Void SetState(ButtonState state, Boolean fastMode) { }
	// RVA: 0x2c85b84 VA: 0x759529db84
	public Void OnBtnClicked() { }
	// RVA: 0x2c86084 VA: 0x759529e084
	public Void .ctor() { }
}
```