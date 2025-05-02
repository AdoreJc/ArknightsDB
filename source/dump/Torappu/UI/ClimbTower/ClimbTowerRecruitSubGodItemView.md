# ClimbTowerRecruitSubGodItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textName`

- `Image _imgIcon`

- `GameObject _selectPanel`

- `Text _textDesc`

- `ClimbTowerRecruitSubGodItemModel m_subCardModel`

- `Boolean m_isSelected`


## Methods

- `Void set_onItemSelected(Action`1)`

- `Void Render(ClimbTowerRecruitSubGodItemModel, Boolean)`

- `Void EventOnSubItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRecruitSubGodItemView : MonoBehaviour, IHotfixable
{
	private Text _textName; // 0x18
	private Image _imgIcon; // 0x20
	private GameObject _selectPanel; // 0x28
	private Text _textDesc; // 0x30
	private ClimbTowerRecruitSubGodItemModel m_subCardModel; // 0x38
	private Boolean m_isSelected; // 0x40
	private Action`1 <onItemSelected>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onItemSelected; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemSelected; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnSubItemClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemSelected { get; set; }

	// RVA: 0x2cac39c VA: 0x75952c439c
	private Action`1 get_onItemSelected() { }
	// RVA: 0x2cac404 VA: 0x75952c4404
	public Void set_onItemSelected(Action`1 value) { }
	// RVA: 0x2cac488 VA: 0x75952c4488
	public Void Render(ClimbTowerRecruitSubGodItemModel subCardModel, Boolean isSelected) { }
	// RVA: 0x2cac790 VA: 0x75952c4790
	public Void EventOnSubItemClick() { }
	// RVA: 0x2cac8dc VA: 0x75952c48dc
	public Void .ctor() { }
}
```