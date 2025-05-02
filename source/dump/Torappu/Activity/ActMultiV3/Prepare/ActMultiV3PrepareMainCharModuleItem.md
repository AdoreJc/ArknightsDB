# ActMultiV3PrepareMainCharModuleItem

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `GameObject _selectBgGo`

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

- `EquipItemViewModel m_equipModel`

- `UIPageFinder m_pageFinder`


## Methods

- `Void set_onEquipSelect(Action`2)`

- `Void Render(Int32, Boolean, EquipItemViewModel)`

- `Void OnEquipSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainCharModuleItem : MonoBehaviour, IHotfixable
{
	private GameObject _selectBgGo; // 0x18
	private GameObject _normalPartGo; // 0x20
	private GameObject _emptyPartGo; // 0x28
	private GameObject _lockPartGo; // 0x30
	private GameObject _levelGo; // 0x38
	private Text _textLv; // 0x40
	private Text _textEquipName; // 0x48
	private Image _imgEquipIcon; // 0x50
	private Image _imgEquipType; // 0x58
	private CanvasGroup _canvasGroup; // 0x60
	private Single _unselectAlpha; // 0x68
	private Int32 m_cardId; // 0x6c
	private Boolean m_isSelect; // 0x70
	private EquipItemViewModel m_equipModel; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private Action`2 <onEquipSelect>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_onEquipSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onEquipSelect; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnEquipSelect; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`2 onEquipSelect { get; set; }

	// RVA: 0x315f678 VA: 0x7595777678
	private Action`2 get_onEquipSelect() { }
	// RVA: 0x315f6e0 VA: 0x75957776e0
	public Void set_onEquipSelect(Action`2 value) { }
	// RVA: 0x315f764 VA: 0x7595777764
	public Void Render(Int32 cardId, Boolean isSelect, EquipItemViewModel equipItemModel) { }
	// RVA: 0x315f9ec VA: 0x75957779ec
	public Void OnEquipSelect() { }
	// RVA: 0x315fab8 VA: 0x7595777ab8
	public Void .ctor() { }
}
```