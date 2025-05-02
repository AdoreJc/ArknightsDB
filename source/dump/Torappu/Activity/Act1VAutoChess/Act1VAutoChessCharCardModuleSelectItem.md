# Act1VAutoChessCharCardModuleSelectItem

**Namespace:** `Torappu.Activity.Act1VAutoChess`


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

- `String m_chessId`

- `Int32 m_chessLv`

- `EquipItemViewModel m_equipModel`

- `UIPageFinder m_pageFinder`


## Methods

- `Void set_onEquipSelect(Action`3)`

- `Void Render(String, Int32, Boolean, EquipItemViewModel)`

- `Void OnEquipSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessCharCardModuleSelectItem : MonoBehaviour, IHotfixable
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
	private String m_chessId; // 0x78
	private Int32 m_chessLv; // 0x80
	private EquipItemViewModel m_equipModel; // 0x88
	private UIPageFinder m_pageFinder; // 0x90
	private Action`3 <onEquipSelect>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_onEquipSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onEquipSelect; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnEquipSelect; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`3 onEquipSelect { get; set; }

	// RVA: 0x3321f58 VA: 0x7595939f58
	private Action`3 get_onEquipSelect() { }
	// RVA: 0x3321fc0 VA: 0x7595939fc0
	public Void set_onEquipSelect(Action`3 value) { }
	// RVA: 0x3322044 VA: 0x759593a044
	public Void Render(String chessId, Int32 chessLv, Boolean isSelect, EquipItemViewModel equipItemModel) { }
	// RVA: 0x33222f0 VA: 0x759593a2f0
	public Void OnEquipSelect() { }
	// RVA: 0x33223b8 VA: 0x759593a3b8
	public Void .ctor() { }
}
```