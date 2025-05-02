# ClimbTowerTrainItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String _towerId`

- `Text _textTowerCodeName`

- `CanvasGroup _panelSelected`

- `GameObject _panelComplete`

- `GameObject _panelInBattle`

- `FadeSwitchTween m_completeSwitchTween`


## Properties

- `String towerId`


## Methods

- `String get_towerId()`

- `Void set_onTowerSelected(Action`1)`

- `Void set_onDetailClicked(Action`1)`

- `Void Render(ClimbTowerTrainItemViewModel, Boolean)`

- `Void OnTowerSelected()`

- `Void OnDetailClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrainItemView : MonoBehaviour, IHotfixable
{
	private String _towerId; // 0x18
	private Text _textTowerCodeName; // 0x20
	private CanvasGroup _panelSelected; // 0x28
	private GameObject _panelComplete; // 0x30
	private GameObject _panelInBattle; // 0x38
	private FadeSwitchTween m_completeSwitchTween; // 0x40
	private Action`1 <onTowerSelected>k__BackingField; // 0x48
	private Action`1 <onDetailClicked>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_towerId; // 0x0
	private static DelegateBridge __Hotfix0_get_onTowerSelected; // 0x8
	private static DelegateBridge __Hotfix0_set_onTowerSelected; // 0x10
	private static DelegateBridge __Hotfix0_get_onDetailClicked; // 0x18
	private static DelegateBridge __Hotfix0_set_onDetailClicked; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_OnTowerSelected; // 0x30
	private static DelegateBridge __Hotfix0_OnDetailClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String towerId { get; }
	private Action`1 onTowerSelected { get; set; }
	private Action`1 onDetailClicked { get; set; }

	// RVA: 0x2c6a96c VA: 0x759528296c
	public String get_towerId() { }
	// RVA: 0x2c6a9d4 VA: 0x75952829d4
	private Action`1 get_onTowerSelected() { }
	// RVA: 0x2c6aa3c VA: 0x7595282a3c
	public Void set_onTowerSelected(Action`1 value) { }
	// RVA: 0x2c6aac0 VA: 0x7595282ac0
	private Action`1 get_onDetailClicked() { }
	// RVA: 0x2c6ab28 VA: 0x7595282b28
	public Void set_onDetailClicked(Action`1 value) { }
	// RVA: 0x2c6abac VA: 0x7595282bac
	public Void Render(ClimbTowerTrainItemViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x2c6ad1c VA: 0x7595282d1c
	public Void OnTowerSelected() { }
	// RVA: 0x2c6adcc VA: 0x7595282dcc
	public Void OnDetailClicked() { }
	// RVA: 0x2c6ae88 VA: 0x7595282e88
	public Void .ctor() { }
}
```