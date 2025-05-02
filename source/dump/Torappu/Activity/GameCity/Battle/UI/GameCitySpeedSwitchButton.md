# GameCitySpeedSwitchButton

**Namespace:** `Torappu.Activity.GameCity.Battle.UI`


## Fields

- `UIBattleSwitchToggle _speedToggle`

- `Button _speedButton`

- `Graphic _slowMotionImage`


## Properties

- `Boolean isInteractive`


## Methods

- `Boolean get_isInteractive()`

- `Void OnInit()`

- `Void OnSpeedButtonClick()`

- `Void ActiveSpeedButton(Boolean)`

- `Void _OnSpeedLevelChanged(Object)`

- `Void _ToggleSpeedLevel(SpeedLevel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.GameCity.Battle.UI
public class GameCitySpeedSwitchButton : MonoBehaviour, IHotfixable
{
	private UIBattleSwitchToggle _speedToggle; // 0x18
	private Button _speedButton; // 0x20
	private Graphic _slowMotionImage; // 0x28
	private static DelegateBridge __Hotfix0_get_isInteractive; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnSpeedButtonClick; // 0x10
	private static DelegateBridge __Hotfix0_ActiveSpeedButton; // 0x18
	private static DelegateBridge __Hotfix0__OnSpeedLevelChanged; // 0x20
	private static DelegateBridge __Hotfix0__ToggleSpeedLevel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean isInteractive { get; }

	// RVA: 0x33eae6c VA: 0x7595a02e6c
	public Boolean get_isInteractive() { }
	// RVA: 0x33eaee0 VA: 0x7595a02ee0
	public Void OnInit() { }
	// RVA: 0x33eafe8 VA: 0x7595a02fe8
	public Void OnSpeedButtonClick() { }
	// RVA: 0x33eb0bc VA: 0x7595a030bc
	public Void ActiveSpeedButton(Boolean active) { }
	// RVA: 0x33eb1c4 VA: 0x7595a031c4
	private Void _OnSpeedLevelChanged(Object arg) { }
	// RVA: 0x33eb284 VA: 0x7595a03284
	private Void _ToggleSpeedLevel(SpeedLevel level) { }
	// RVA: 0x33eb32c VA: 0x7595a0332c
	public Void .ctor() { }
}
```