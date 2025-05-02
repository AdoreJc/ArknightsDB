# ClimbTowerMenuProfessionItem

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ProfessionCategory _profession`

- `Text _textNum`

- `GameObject _pnlRaycastBlocker`

- `ClimbTowerMenu m_bindMenu`


## Properties

- `ClimbTowerMenu bindMenu`

- `ProfessionCategory profession`


## Methods

- `Void set_bindMenu(ClimbTowerMenu)`

- `ProfessionCategory get_profession()`

- `Void Render(Int32, Action`1)`

- `Void OnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerMenuProfessionItem : MonoBehaviour, IHotfixable
{
	private ProfessionCategory _profession; // 0x18
	private Text _textNum; // 0x20
	private GameObject _pnlRaycastBlocker; // 0x28
	private Action`1 m_callback; // 0x30
	private ClimbTowerMenu m_bindMenu; // 0x38
	private static DelegateBridge __Hotfix0_set_bindMenu; // 0x0
	private static DelegateBridge __Hotfix0_get_profession; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnBtnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public ClimbTowerMenu bindMenu { set; }
	public ProfessionCategory profession { get; }

	// RVA: 0x2c834f4 VA: 0x759529b4f4
	public Void set_bindMenu(ClimbTowerMenu value) { }
	// RVA: 0x2c83578 VA: 0x759529b578
	public ProfessionCategory get_profession() { }
	// RVA: 0x2c835e0 VA: 0x759529b5e0
	public Void Render(Int32 count, Action`1 callback) { }
	// RVA: 0x2c836e8 VA: 0x759529b6e8
	public Void OnBtnClicked() { }
	// RVA: 0x2c837dc VA: 0x759529b7dc
	public Void .ctor() { }
}
```