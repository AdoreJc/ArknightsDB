# GameCityPauseButton

**Namespace:** `Torappu.Activity.GameCity.Battle.UI`


## Fields

- `UIBattleSwitchToggle _pauseToggle`

- `Button _pauseButton`


## Properties

- `UIBattleSwitchToggle pauseToggle`


## Methods

- `UIBattleSwitchToggle get_pauseToggle()`

- `Void OnPauseButtonClick()`

- `Void ActivePauseButton(Boolean)`

- `Void _OnPauseToggled(Object)`

- `Void Start()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.GameCity.Battle.UI
public class GameCityPauseButton : MonoBehaviour, IHotfixable
{
	private UIBattleSwitchToggle _pauseToggle; // 0x18
	private Button _pauseButton; // 0x20
	private static DelegateBridge __Hotfix0_get_pauseToggle; // 0x0
	private static DelegateBridge __Hotfix0_OnPauseButtonClick; // 0x8
	private static DelegateBridge __Hotfix0_ActivePauseButton; // 0x10
	private static DelegateBridge __Hotfix0__OnPauseToggled; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public UIBattleSwitchToggle pauseToggle { get; }

	// RVA: 0x33ea288 VA: 0x7595a02288
	public UIBattleSwitchToggle get_pauseToggle() { }
	// RVA: 0x33ea2f0 VA: 0x7595a022f0
	public Void OnPauseButtonClick() { }
	// RVA: 0x33ea3c0 VA: 0x7595a023c0
	public Void ActivePauseButton(Boolean active) { }
	// RVA: 0x33ea44c VA: 0x7595a0244c
	private Void _OnPauseToggled(Object arg) { }
	// RVA: 0x33ea51c VA: 0x7595a0251c
	private Void Start() { }
	// RVA: 0x33ea678 VA: 0x7595a02678
	private Void OnDestroy() { }
	// RVA: 0x33ea7d4 VA: 0x7595a027d4
	public Void .ctor() { }
}
```