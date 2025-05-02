# ClimbTowerInitGodItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textName`

- `Text _textDesc`

- `Image _imgIcon`

- `GameObject _selectPanel`

- `CanvasGroup _group`

- `GameObject _panelTowerName`

- `Text _textBindTowerName`

- `Int32 m_position`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(Int32, ClimbTowerInitGodCardModel, Boolean)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerInitGodItemView : MonoBehaviour, IHotfixable
{
	private const Single SELECT_ALPHA; // 0x0
	private const Single UNSELECT_ALPHA; // 0x0
	private Text _textName; // 0x18
	private Text _textDesc; // 0x20
	private Image _imgIcon; // 0x28
	private GameObject _selectPanel; // 0x30
	private CanvasGroup _group; // 0x38
	private GameObject _panelTowerName; // 0x40
	private Text _textBindTowerName; // 0x48
	private Int32 m_position; // 0x50
	private Action`1 <onItemClick>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClick { get; set; }

	// RVA: 0x2cac224 VA: 0x75952c4224
	private Action`1 get_onItemClick() { }
	// RVA: 0x2cabfd0 VA: 0x75952c3fd0
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x2cac054 VA: 0x75952c4054
	public Void Render(Int32 position, ClimbTowerInitGodCardModel godCardModel, Boolean isSelected) { }
	// RVA: 0x2cac28c VA: 0x75952c428c
	public Void EventOnItemClick() { }
	// RVA: 0x2cac32c VA: 0x75952c432c
	public Void .ctor() { }
}
```