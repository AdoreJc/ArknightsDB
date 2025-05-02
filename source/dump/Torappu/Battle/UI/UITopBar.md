# UITopBar

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _pauseMask`

- `UISwitchToggle _pauseButton`

- `UISpeedSwitcher _speedSwitcher`

- `Toggle _showAllRangeToggle`

- `Button _systemMenuButton`

- `BasicStatus _twoPartStatus`

- `BasicStatus _threePartStatus`

- `SpeedLevel _maxSpeedLevel`

- `BasicStatus m_currentBasicStatus`


## Properties

- `UISwitchToggle pauseButton`

- `UISpeedSwitcher speedSwitcher`

- `Image pauseMask`

- `Button systemMenuButton`

- `BasicStatus twoPartStatus`

- `SpeedLevel speedLevel`

- `BasicStatus currentBasicStatus`


## Methods

- `UISwitchToggle get_pauseButton()`

- `UISpeedSwitcher get_speedSwitcher()`

- `Image get_pauseMask()`

- `Button get_systemMenuButton()`

- `BasicStatus get_twoPartStatus()`

- `SpeedLevel get_speedLevel()`

- `Void set_speedLevel(SpeedLevel)`

- `Void _OnSpeedLevelChanged(Object)`

- `BasicStatus get_currentBasicStatus()`

- `Void set_currentBasicStatus(BasicStatus)`

- `Void UpdateInfo(BattleController)`

- `Void UpdateDisableMask(BattleFunctionDisableMask)`

- `Void SetPaused(Boolean, Boolean)`

- `Void OnGameInit()`

- `Void OnGameReady()`

- `Void _OnBackPressed()`

- `Void OnPauseButtonClicked()`

- `Void OnSpeedSwitcherClicked()`

- `Void OnShowAllRangeToggled()`

- `Void OnMenuButtonClicked()`

- `Void OnUIStateChanged(IUIStateNode)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UITopBar : MonoBehaviour, IHotfixable
{
	private Image _pauseMask; // 0x18
	private UISwitchToggle _pauseButton; // 0x20
	private UISpeedSwitcher _speedSwitcher; // 0x28
	private Toggle _showAllRangeToggle; // 0x30
	private Button _systemMenuButton; // 0x38
	private BasicStatus _twoPartStatus; // 0x40
	private BasicStatus _threePartStatus; // 0x48
	private SpeedLevel _maxSpeedLevel; // 0x50
	private BasicStatus m_currentBasicStatus; // 0x58
	private static DelegateBridge __Hotfix0_get_pauseButton; // 0x0
	private static DelegateBridge __Hotfix0_get_speedSwitcher; // 0x8
	private static DelegateBridge __Hotfix0_get_pauseMask; // 0x10
	private static DelegateBridge __Hotfix0_get_systemMenuButton; // 0x18
	private static DelegateBridge __Hotfix0_get_twoPartStatus; // 0x20
	private static DelegateBridge __Hotfix0_get_speedLevel; // 0x28
	private static DelegateBridge __Hotfix0_set_speedLevel; // 0x30
	private static DelegateBridge __Hotfix0__OnSpeedLevelChanged; // 0x38
	private static DelegateBridge __Hotfix0_get_currentBasicStatus; // 0x40
	private static DelegateBridge __Hotfix0_set_currentBasicStatus; // 0x48
	private static DelegateBridge __Hotfix0_UpdateInfo; // 0x50
	private static DelegateBridge __Hotfix0_UpdateDisableMask; // 0x58
	private static DelegateBridge __Hotfix0_SetPaused; // 0x60
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x68
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x70
	private static DelegateBridge __Hotfix0__OnBackPressed; // 0x78
	private static DelegateBridge __Hotfix0_OnPauseButtonClicked; // 0x80
	private static DelegateBridge __Hotfix0_OnSpeedSwitcherClicked; // 0x88
	private static DelegateBridge __Hotfix0_OnShowAllRangeToggled; // 0x90
	private static DelegateBridge __Hotfix0_OnMenuButtonClicked; // 0x98
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public UISwitchToggle pauseButton { get; }
	public UISpeedSwitcher speedSwitcher { get; }
	public Image pauseMask { get; }
	public Button systemMenuButton { get; }
	public BasicStatus twoPartStatus { get; }
	public SpeedLevel speedLevel { get; set; }
	public BasicStatus currentBasicStatus { get; set; }

	// RVA: 0x2050470 VA: 0x7594668470
	public UISwitchToggle get_pauseButton() { }
	// RVA: 0x20504d8 VA: 0x75946684d8
	public UISpeedSwitcher get_speedSwitcher() { }
	// RVA: 0x2050540 VA: 0x7594668540
	public Image get_pauseMask() { }
	// RVA: 0x20505a8 VA: 0x75946685a8
	public Button get_systemMenuButton() { }
	// RVA: 0x2050610 VA: 0x7594668610
	public BasicStatus get_twoPartStatus() { }
	// RVA: 0x2050678 VA: 0x7594668678
	public SpeedLevel get_speedLevel() { }
	// RVA: 0x2050704 VA: 0x7594668704
	private Void set_speedLevel(SpeedLevel value) { }
	// RVA: 0x20507a8 VA: 0x75946687a8
	private Void _OnSpeedLevelChanged(Object unused) { }
	// RVA: 0x2050a14 VA: 0x7594668a14
	public BasicStatus get_currentBasicStatus() { }
	// RVA: 0x2050a7c VA: 0x7594668a7c
	public Void set_currentBasicStatus(BasicStatus value) { }
	// RVA: 0x2050b00 VA: 0x7594668b00
	public Void UpdateInfo(BattleController controller) { }
	// RVA: 0x2050cd8 VA: 0x7594668cd8
	public Void UpdateDisableMask(BattleFunctionDisableMask disableMask) { }
	// RVA: 0x2050ef4 VA: 0x7594668ef4
	public Void SetPaused(Boolean value, Boolean quiet) { }
	// RVA: 0x20510bc VA: 0x75946690bc
	public Void OnGameInit() { }
	// RVA: 0x20512c8 VA: 0x75946692c8
	public Void OnGameReady() { }
	// RVA: 0x205152c VA: 0x759466952c
	private Void _OnBackPressed() { }
	// RVA: 0x20516ac VA: 0x75946696ac
	public Void OnPauseButtonClicked() { }
	// RVA: 0x20517d0 VA: 0x75946697d0
	public Void OnSpeedSwitcherClicked() { }
	// RVA: 0x20518b4 VA: 0x75946698b4
	public Void OnShowAllRangeToggled() { }
	// RVA: 0x20519b0 VA: 0x75946699b0
	public Void OnMenuButtonClicked() { }
	// RVA: 0x2051b08 VA: 0x7594669b08
	public Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x2051d3c VA: 0x7594669d3c
	public Void .ctor() { }
}
```