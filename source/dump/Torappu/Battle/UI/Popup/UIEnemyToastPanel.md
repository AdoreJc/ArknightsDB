# UIEnemyToastPanel

**Namespace:** `Torappu.Battle.UI.Popup`


## Fields

- `Image _enemyIcon`

- `Text _enemyName`

- `Text _enemyDesc`

- `Slider _processSlider`

- `UISwitchToggle _pauseToggle`

- `Boolean m_pause`


## Methods

- `Void OnDestroy()`

- `Void OnPauseButtonClicked()`

- `Void <>xLuaBaseProxy_OnInit(UIToastController)`

- `Void <>xLuaBaseProxy_SetPaused(Boolean)`

- `Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode)`

- `Void <>xLuaBaseProxy_OnUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Popup
public class UIEnemyToastPanel : UIToastSubPanel
{
	private Image _enemyIcon; // 0x28
	private Text _enemyName; // 0x30
	private Text _enemyDesc; // 0x38
	private Slider _processSlider; // 0x40
	private UISwitchToggle _pauseToggle; // 0x48
	private Boolean m_pause; // 0x50
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnShow; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_SetPaused; // 0x18
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnPauseButtonClicked; // 0x28
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x20c76dc VA: 0x75946df6dc
	public override Void OnInit(UIToastController controller) { }
	// RVA: 0x20c7798 VA: 0x75946df798
	public override Void OnShow(Options options) { }
	// RVA: 0x20c797c VA: 0x75946df97c
	private Void OnDestroy() { }
	// RVA: 0x20c79f4 VA: 0x75946df9f4
	public override Void SetPaused(Boolean value) { }
	// RVA: 0x20c7b5c VA: 0x75946dfb5c
	public override Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x20c7c78 VA: 0x75946dfc78
	public Void OnPauseButtonClicked() { }
	// RVA: 0x20c7e64 VA: 0x75946dfe64
	public override Void OnUpdate() { }
	// RVA: 0x20c7fa8 VA: 0x75946dffa8
	public Void .ctor() { }
	// RVA: 0x20c8018 VA: 0x75946e0018
	private Void <>xLuaBaseProxy_OnInit(UIToastController P0) { }
	// RVA: 0x20c8020 VA: 0x75946e0020
	private Void <>xLuaBaseProxy_SetPaused(Boolean P0) { }
	// RVA: 0x20c802c VA: 0x75946e002c
	private Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode P0) { }
	// RVA: 0x20c8034 VA: 0x75946e0034
	private Void <>xLuaBaseProxy_OnUpdate() { }
}
```