# BuildingManufactFormulaItemView

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `RectTransform _itemContainer`

- `Single _targetScale`

- `SimpleLayoutContent _costContainer`

- `GameObject _panelClickSpot`

- `GameObject _panelLocked`

- `Text _textName`

- `UIBicolorText _textTime`

- `Text _textUnlockCond`

- `UILongPressButton _btnFormula`

- `Text _textWeight`

- `MFormulaViewModel m_cachedFormula`

- `Boolean m_isSelected`

- `Boolean m_isInited`

- `CostAdapter m_costAdapter`

- `UIItemCard m_targetItemCard`

- `UIItemViewModel m_targetItemModel`


## Methods

- `Void Render(MFormulaViewModel, Boolean)`

- `Void _Init(MFormulaViewModel)`

- `Void _OnFormulaClicked()`

- `Boolean _OnFormulaLongPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactFormulaItemView : MonoBehaviour
{
	private RectTransform _itemContainer; // 0x18
	private Single _targetScale; // 0x20
	private SimpleLayoutContent _costContainer; // 0x28
	private GameObject _panelClickSpot; // 0x30
	private GameObject _panelLocked; // 0x38
	private Text _textName; // 0x40
	private UIBicolorText _textTime; // 0x48
	private Text _textUnlockCond; // 0x50
	private UILongPressButton _btnFormula; // 0x58
	private Text _textWeight; // 0x60
	public Action`1 onFormulaClicked; // 0x68
	private MFormulaViewModel m_cachedFormula; // 0x70
	private Boolean m_isSelected; // 0x78
	private Boolean m_isInited; // 0x79
	private CostAdapter m_costAdapter; // 0x80
	private UIItemCard m_targetItemCard; // 0x88
	private UIItemViewModel m_targetItemModel; // 0x90


	// RVA: 0x3e09c2c VA: 0x7596421c2c
	public Void Render(MFormulaViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x3e09f14 VA: 0x7596421f14
	private Void _Init(MFormulaViewModel viewModel) { }
	// RVA: 0x3e0a208 VA: 0x7596422208
	private Void _OnFormulaClicked() { }
	// RVA: 0x3e0a228 VA: 0x7596422228
	private Boolean _OnFormulaLongPressed() { }
	// RVA: 0x3e0a268 VA: 0x7596422268
	public Void .ctor() { }
}
```