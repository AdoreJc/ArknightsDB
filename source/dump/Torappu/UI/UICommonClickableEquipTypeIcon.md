# UICommonClickableEquipTypeIcon

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _emptyPartGo`

- `GameObject _normalPartGo`

- `GameObject _lockPartGo`

- `GameObject _selectedPartGo`

- `Image _imgEquipIcon`

- `Image _imgShining`

- `GameObject _panelSingleType`

- `GameObject _panelMultiType`

- `Text _textSingleTypeDesc`

- `Text _textMultiTypeDesc`

- `Image _imgMultiType`

- `Text _textName`

- `GameObject _levelPanelGo`

- `Text _textLevel`

- `GameObject _imgBack`

- `UIColorGraphic _colorGraphic`

- `Single _unselectAlpha`

- `UIClickableEquipItemModel m_equipModel`


## Methods

- `Void set_onEquipClicked(Action`1)`

- `Void Render(UIClickableEquipItemModel, Boolean, InputParam)`

- `Void _SetEquipItemShowType(Boolean, Boolean, Boolean)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICommonClickableEquipTypeIcon : MonoBehaviour, IHotfixable
{
	private GameObject _emptyPartGo; // 0x18
	private GameObject _normalPartGo; // 0x20
	private GameObject _lockPartGo; // 0x28
	private GameObject _selectedPartGo; // 0x30
	private Image _imgEquipIcon; // 0x38
	private Image _imgShining; // 0x40
	private GameObject _panelSingleType; // 0x48
	private GameObject _panelMultiType; // 0x50
	private Text _textSingleTypeDesc; // 0x58
	private Text _textMultiTypeDesc; // 0x60
	private Image _imgMultiType; // 0x68
	private Text _textName; // 0x70
	private GameObject _levelPanelGo; // 0x78
	private Text _textLevel; // 0x80
	private GameObject _imgBack; // 0x88
	private UIColorGraphic _colorGraphic; // 0x90
	private Single _unselectAlpha; // 0x98
	private UIClickableEquipItemModel m_equipModel; // 0xa0
	private Action`1 <onEquipClicked>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_get_onEquipClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onEquipClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__SetEquipItemShowType; // 0x18
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onEquipClicked { get; set; }

	// RVA: 0x2290b98 VA: 0x75948a8b98
	private Action`1 get_onEquipClicked() { }
	// RVA: 0x2290c00 VA: 0x75948a8c00
	public Void set_onEquipClicked(Action`1 value) { }
	// RVA: 0x2290c84 VA: 0x75948a8c84
	public Void Render(UIClickableEquipItemModel equipModel, Boolean isSelected, InputParam param) { }
	// RVA: 0x2291014 VA: 0x75948a9014
	private Void _SetEquipItemShowType(Boolean isEmpty, Boolean isUnlock, Boolean isSelected) { }
	// RVA: 0x22910f8 VA: 0x75948a90f8
	public Void EventOnItemClick() { }
	// RVA: 0x22911b0 VA: 0x75948a91b0
	public Void .ctor() { }
}
```