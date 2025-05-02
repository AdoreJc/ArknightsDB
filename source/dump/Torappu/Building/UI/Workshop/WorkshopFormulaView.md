# WorkshopFormulaView

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `Transform _outcomeContainer`

- `Single _targetScale`

- `SimpleLayoutContent _costContainer`

- `Text _textName`

- `Text _textCost`

- `GameObject _panelLocked`

- `GameObject _panelHotspot`

- `Text _textUnlockCond`

- `UILongPressButton _btnFormula`

- `Text _apCostLabel`

- `GameObject _apCostPanel`

- `Boolean m_inited`

- `CostAdapter m_costAdapter`

- `UIItemCard m_outcomeItemCard`

- `IWorkshopFormula m_currentFormula`


## Methods

- `Void add_onFormulaClicked(Action`1)`

- `Void remove_onFormulaClicked(Action`1)`

- `Void Setup(IWorkshopFormula)`

- `Void _Init(IWorkshopFormula)`

- `Void _OnFormulaClicked()`

- `Boolean _OnFormulaLongPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class WorkshopFormulaView : MonoBehaviour
{
	private Transform _outcomeContainer; // 0x18
	private Single _targetScale; // 0x20
	private SimpleLayoutContent _costContainer; // 0x28
	private Text _textName; // 0x30
	private Text _textCost; // 0x38
	private GameObject _panelLocked; // 0x40
	private GameObject _panelHotspot; // 0x48
	private Text _textUnlockCond; // 0x50
	private UILongPressButton _btnFormula; // 0x58
	private Text _apCostLabel; // 0x60
	private GameObject _apCostPanel; // 0x68
	private Boolean m_inited; // 0x70
	private CostAdapter m_costAdapter; // 0x78
	private UIItemCard m_outcomeItemCard; // 0x80
	private IWorkshopFormula m_currentFormula; // 0x88
	private Action`1 onFormulaClicked; // 0x90


	// RVA: 0x3d6d364 VA: 0x7596385364
	public Void add_onFormulaClicked(Action`1 value) { }
	// RVA: 0x3d6d2b4 VA: 0x75963852b4
	public Void remove_onFormulaClicked(Action`1 value) { }
	// RVA: 0x3d6ccc8 VA: 0x7596384cc8
	public Void Setup(IWorkshopFormula formula) { }
	// RVA: 0x3d733b4 VA: 0x759638b3b4
	private Void _Init(IWorkshopFormula formula) { }
	// RVA: 0x3d73698 VA: 0x759638b698
	private Void _OnFormulaClicked() { }
	// RVA: 0x3d736b8 VA: 0x759638b6b8
	private Boolean _OnFormulaLongPressed() { }
	// RVA: 0x3d73808 VA: 0x759638b808
	public Void .ctor() { }
}
```