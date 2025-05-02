# ClimbTowerButtonHolderMenuObject

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `CanvasGroup _canvasRoot`

- `Int32 m_currIndex`

- `Boolean m_hasInited`

- `Boolean m_tacticalBuffWindowShow`

- `ClimbTowerMenuButton m_prefab`

- `SwitchTween m_switchTween`

- `FadeSwitchTween m_showSwitchTween`

- `Action m_callback`


## Properties

- `ClimbTowerMenuButton currInst`


## Methods

- `ClimbTowerMenuButton get_currInst()`

- `Void set_currInst(ClimbTowerMenuButton)`

- `Void _InitIfNot()`

- `Void _OnBtnClicked()`

- `Void OnTacticalBuffWindowShowStatusUpdated(Boolean)`

- `Void UpdateButton(ClimbTowerMenuButton, IClimbTowerMenuButtonDataSource, Action, Boolean)`

- `IEnumerator EnsureButton()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerButtonHolderMenuObject : ClimbTowerMenuObject
{
	private CanvasGroup[] _canvasList; // 0x20
	private CanvasGroup _canvasRoot; // 0x28
	private Int32 m_currIndex; // 0x30
	private Boolean m_hasInited; // 0x34
	private Boolean m_tacticalBuffWindowShow; // 0x35
	private ClimbTowerMenuButton m_prefab; // 0x38
	private ClimbTowerMenuButton[] m_instance; // 0x40
	private SwitchTween m_switchTween; // 0x48
	private FadeSwitchTween m_showSwitchTween; // 0x50
	private Action m_callback; // 0x58
	private static DelegateBridge __Hotfix0_get_currInst; // 0x0
	private static DelegateBridge __Hotfix0_set_currInst; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_OnTacticalBuffWindowShowStatusUpdated; // 0x28
	private static DelegateBridge __Hotfix0_UpdateButton; // 0x30
	private static DelegateBridge __Hotfix0_EnsureButton; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private ClimbTowerMenuButton currInst { get; set; }

	// RVA: 0x2c7ef58 VA: 0x7595296f58
	private ClimbTowerMenuButton get_currInst() { }
	// RVA: 0x2c7efe4 VA: 0x7595296fe4
	private Void set_currInst(ClimbTowerMenuButton value) { }
	// RVA: 0x2c7f0ac VA: 0x75952970ac
	private Void _InitIfNot() { }
	// RVA: 0x2c7f2ac VA: 0x75952972ac
	private Void _OnBtnClicked() { }
	// RVA: 0x2c7f540 VA: 0x7595297540
	public override Void Render(ClimbTowerMenuViewModel viewModel) { }
	// RVA: 0x2c7f5b8 VA: 0x75952975b8
	public Void OnTacticalBuffWindowShowStatusUpdated(Boolean isShow) { }
	// RVA: 0x2c7f658 VA: 0x7595297658
	public Void UpdateButton(ClimbTowerMenuButton buttonPrefab, IClimbTowerMenuButtonDataSource dataSource, Action callback, Boolean fastMode) { }
	// RVA: 0x2c7faa0 VA: 0x7595297aa0
	public IEnumerator EnsureButton() { }
	// RVA: 0x2c7fb74 VA: 0x7595297b74
	public Void .ctor() { }
}
```