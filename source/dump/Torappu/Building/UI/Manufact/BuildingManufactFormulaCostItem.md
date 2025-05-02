# BuildingManufactFormulaCostItem

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `GameObject _panelActive`

- `GameObject _panelEmpty`

- `RectTransform _itemContainer`

- `Single _itemScale`

- `Text _textCount`

- `GameObject _panelLack`

- `Color _lackColor`

- `Boolean m_isInited`

- `FormulaCostStruct m_cacheCost`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`


## Methods

- `Void Render(FormulaCostStruct)`

- `Void _Init()`

- `Void _RenderActive(FormulaCostStruct)`

- `Void <_Init>b__13_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactFormulaCostItem : MonoBehaviour
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
	private FormulaCostStruct m_cacheCost; // 0x60
	private UIItemCard m_itemCard; // 0x78
	private UIItemViewModel m_itemModel; // 0x80


	// RVA: 0x3e09734 VA: 0x7596421734
	public Void Render(FormulaCostStruct cost) { }
	// RVA: 0x3e0980c VA: 0x759642180c
	private Void _Init() { }
	// RVA: 0x3e099b8 VA: 0x75964219b8
	private Void _RenderActive(FormulaCostStruct cost) { }
	// RVA: 0x3e09b38 VA: 0x7596421b38
	public Void .ctor() { }
	// RVA: 0x3e09bac VA: 0x7596421bac
	private Void <_Init>b__13_0(Int32 _) { }
}
```