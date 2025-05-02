# ClimbTowerTrapMenuObject

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textTrapCount`

- `GameObject _panelCurse`

- `Image _imgCard`

- `CanvasGroup _canvasNormal`

- `CanvasGroup _canvasSelected`

- `CanvasGroup _canvasSelectedOutline`

- `CanvasGroup _canvasRoot`

- `GameObject _raycastBlocker`

- `SelectedSwitchTween m_selectedSwitchTween`

- `FadeSwitchTween m_outlineSwitchTween`

- `AvailableSwitchTween m_availableSwitchTween`

- `Boolean m_hasInited`

- `Boolean m_tacticalBuffWindowShow`

- `ButtonState m_state`

- `Int32 m_cachedTrapCount`


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
public class ClimbTowerTrapMenuObject : ClimbTowerMenuObject
{
	private Text _textTrapCount; // 0x20
	private GameObject _panelCurse; // 0x28
	private Image _imgCard; // 0x30
	private CanvasGroup _canvasNormal; // 0x38
	private CanvasGroup _canvasSelected; // 0x40
	private CanvasGroup _canvasSelectedOutline; // 0x48
	private CanvasGroup _canvasRoot; // 0x50
	private GameObject _raycastBlocker; // 0x58
	private SelectedSwitchTween m_selectedSwitchTween; // 0x60
	private FadeSwitchTween m_outlineSwitchTween; // 0x68
	private AvailableSwitchTween m_availableSwitchTween; // 0x70
	private Boolean m_hasInited; // 0x78
	private Boolean m_tacticalBuffWindowShow; // 0x79
	private ButtonState m_state; // 0x7c
	private Int32 m_cachedTrapCount; // 0x80
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RefreshCanvas; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_OnTacticalBuffWindowShowStatusUpdated; // 0x20
	private static DelegateBridge __Hotfix0_SetState; // 0x28
	private static DelegateBridge __Hotfix0_OnBtnClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public ButtonState state { get; }

	// RVA: 0x2c8601c VA: 0x759529e01c
	public ButtonState get_state() { }
	// RVA: 0x2c87814 VA: 0x759529f814
	private Void _InitIfNot() { }
	// RVA: 0x2c87ac8 VA: 0x759529fac8
	private Void _RefreshCanvas(Boolean fastMode) { }
	// RVA: 0x2c87c18 VA: 0x759529fc18
	public override Void Render(ClimbTowerMenuViewModel viewModel) { }
	// RVA: 0x2c87e70 VA: 0x759529fe70
	public Void OnTacticalBuffWindowShowStatusUpdated(Boolean isShow) { }
	// RVA: 0x2c87ef8 VA: 0x759529fef8
	public Void SetState(ButtonState state, Boolean fastMode) { }
	// RVA: 0x2c87f84 VA: 0x759529ff84
	public Void OnBtnClicked() { }
	// RVA: 0x2c88314 VA: 0x75952a0314
	public Void .ctor() { }
}
```