# BuildingWorkshopFormulaCostItem

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `GameObject _panelActive`

- `GameObject _panelEmpty`

- `RectTransform _itemContainer`

- `Single _itemScale`

- `Text _textCount`

- `GameObject _panelLack`

- `Color _lackColor`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`


## Methods

- `Void Render(IFormulaItem)`

- `Void _Init()`

- `Void _RenderActive(IFormulaItem)`

- `Void <_Init>b__12_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopFormulaCostItem : MonoBehaviour
{
	private const Int32 MAX_COUNT_LENGTH; // 0x0
	private GameObject _panelActive; // 0x18
	private GameObject _panelEmpty; // 0x20
	private RectTransform _itemContainer; // 0x28
	private Single _itemScale; // 0x30
	private Text _textCount; // 0x38
	private GameObject _panelLack; // 0x40
	private Color _lackColor; // 0x48
	private Boolean m_isInited; // 0x58
	private UIItemCard m_itemCard; // 0x60
	private UIItemViewModel m_itemModel; // 0x68


	// RVA: 0x3d6d76c VA: 0x759638576c
	public Void Render(IFormulaItem cost) { }
	// RVA: 0x3d6d870 VA: 0x7596385870
	private Void _Init() { }
	// RVA: 0x3d6da1c VA: 0x7596385a1c
	private Void _RenderActive(IFormulaItem cost) { }
	// RVA: 0x3d6dd80 VA: 0x7596385d80
	public Void .ctor() { }
	// RVA: 0x3d6ddf4 VA: 0x7596385df4
	private Void <_Init>b__12_0(Int32 _) { }
}
```