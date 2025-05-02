# ClimbTowerSquadMultiEditEquipItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `GameObject _selectBgGo`

- `GameObject _iconSelectGo`

- `GameObject _normalPartGo`

- `GameObject _emptyPartGo`

- `GameObject _lockPartGo`

- `GameObject _levelGo`

- `Text _textLv`

- `Text _textEquipName`

- `Image _imgEquipIcon`

- `Image _imgEquipType`

- `CanvasGroup _canvasGroup`

- `Single _unselectAlpha`

- `Int32 m_cardId`

- `Boolean m_isSelect`

- `ClimbTowerEquipItemModel m_equipModel`


## Methods

- `Void set_onEquipSelect(Action`2)`

- `Void Render(Int32, Boolean, ClimbTowerEquipItemModel)`

- `Void _HideAll()`

- `Void OnEquipSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadMultiEditEquipItemView : MonoBehaviour, IHotfixable
{
	private GameObject _selectBgGo; // 0x18
	private GameObject _iconSelectGo; // 0x20
	private GameObject _normalPartGo; // 0x28
	private GameObject _emptyPartGo; // 0x30
	private GameObject _lockPartGo; // 0x38
	private GameObject _levelGo; // 0x40
	private Text _textLv; // 0x48
	private Text _textEquipName; // 0x50
	private Image _imgEquipIcon; // 0x58
	private Image _imgEquipType; // 0x60
	private CanvasGroup _canvasGroup; // 0x68
	private Single _unselectAlpha; // 0x70
	private Int32 m_cardId; // 0x74
	private Boolean m_isSelect; // 0x78
	private ClimbTowerEquipItemModel m_equipModel; // 0x80
	private Action`2 <onEquipSelect>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_onEquipSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onEquipSelect; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__HideAll; // 0x18
	private static DelegateBridge __Hotfix0_OnEquipSelect; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`2 onEquipSelect { get; set; }

	// RVA: 0x2cc3b20 VA: 0x75952dbb20
	private Action`2 get_onEquipSelect() { }
	// RVA: 0x2cc332c VA: 0x75952db32c
	public Void set_onEquipSelect(Action`2 value) { }
	// RVA: 0x2cc33b0 VA: 0x75952db3b0
	public Void Render(Int32 cardId, Boolean isSelect, ClimbTowerEquipItemModel equipItemModel) { }
	// RVA: 0x2cc3b88 VA: 0x75952dbb88
	private Void _HideAll() { }
	// RVA: 0x2cc3c38 VA: 0x75952dbc38
	public Void OnEquipSelect() { }
	// RVA: 0x2cc3d04 VA: 0x75952dbd04
	public Void .ctor() { }
}
```