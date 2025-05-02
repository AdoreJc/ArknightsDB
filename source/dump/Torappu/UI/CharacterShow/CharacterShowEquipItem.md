# CharacterShowEquipItem

**Namespace:** `Torappu.UI.CharacterShow`


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

- `UIColorGraphic _colorGraphic`

- `Single _skillUnselectAlpha`

- `UIStateFinder m_stateFinder`

- `CharacterShowEquipModel m_equipModel`


## Methods

- `Void Render(CharacterShowEquipModel, Boolean, Boolean)`

- `Void _SetEquipItemShowType(Boolean, Boolean, Boolean, Boolean)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowEquipItem : MonoBehaviour, IHotfixable
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
	private UIColorGraphic _colorGraphic; // 0x88
	private Single _skillUnselectAlpha; // 0x90
	private UIStateFinder m_stateFinder; // 0x98
	private CharacterShowEquipModel m_equipModel; // 0xa8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__SetEquipItemShowType; // 0x8
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2ce5714 VA: 0x75952fd714
	public Void Render(CharacterShowEquipModel equipModel, Boolean isSelected, Boolean isSelectedVisible) { }
	// RVA: 0x2ce6b44 VA: 0x75952feb44
	private Void _SetEquipItemShowType(Boolean isEmpty, Boolean isUnlock, Boolean isSelected, Boolean isSelectedVisible) { }
	// RVA: 0x2ce6c34 VA: 0x75952fec34
	public Void EventOnItemClick() { }
	// RVA: 0x2ce6d3c VA: 0x75952fed3c
	public Void .ctor() { }
}
```