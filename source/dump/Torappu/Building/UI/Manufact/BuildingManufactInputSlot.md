# BuildingManufactInputSlot

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `GameObject _panelActive`

- `GameObject _panelInactive`

- `Text _textName`

- `Text _textCount`

- `Text _textCost`

- `Text _textReserve`

- `RectTransform _itemCardContainer`

- `Single _itemScale`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `MItemInputSlotStruct m_itemStruct`

- `UIItemViewModel m_itemViewModel`


## Methods

- `Void Start()`

- `Void _Init()`

- `Void _UpdateActive()`

- `Void _UpdateAutoLayouts()`

- `Void <_Init>b__16_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactInputSlot : DataBinder`1
{
	private const Int32 LARGE_NUMBER; // 0x0
	private GameObject _panelActive; // 0x20
	private GameObject _panelInactive; // 0x28
	private Text _textName; // 0x30
	private Text _textCount; // 0x38
	private Text _textCost; // 0x40
	private Text _textReserve; // 0x48
	private RectTransform _itemCardContainer; // 0x50
	private Single _itemScale; // 0x58
	private RectTransform[] _autoLayouts; // 0x60
	private Boolean m_isInited; // 0x68
	private UIItemCard m_itemCard; // 0x70
	private MItemInputSlotStruct m_itemStruct; // 0x78
	private UIItemViewModel m_itemViewModel; // 0x90
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__Init; // 0x10
	private static DelegateBridge __Hotfix0__UpdateActive; // 0x18
	private static DelegateBridge __Hotfix0__UpdateAutoLayouts; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3e0ab6c VA: 0x7596422b6c
	private Void Start() { }
	// RVA: 0x3e0acd4 VA: 0x7596422cd4
	public override Void OnValueChanged(MItemInputSlotProperty property) { }
	// RVA: 0x3e0ae80 VA: 0x7596422e80
	private Void _Init() { }
	// RVA: 0x3e0b068 VA: 0x7596423068
	private Void _UpdateActive() { }
	// RVA: 0x3e0abd4 VA: 0x7596422bd4
	private Void _UpdateAutoLayouts() { }
	// RVA: 0x3e0b2e4 VA: 0x75964232e4
	public Void .ctor() { }
	// RVA: 0x3e0b3bc VA: 0x75964233bc
	private Void <_Init>b__16_0(Int32 _) { }
}
```