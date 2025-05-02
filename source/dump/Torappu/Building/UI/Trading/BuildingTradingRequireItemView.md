# BuildingTradingRequireItemView

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `BuildingTradingRequireItemInfo _completeInfo`

- `BuildingTradingRequireItemInfo _uncompleteInfo`

- `UIItemCard _itemPrefab`

- `RectTransform _itemContainer`

- `Single _itemScaler`

- `Animator _animator`

- `Boolean m_isInited`

- `UIItemViewModel m_itemModel`

- `UIItemCard m_itemCard`

- `Boolean m_isOrderComplete`


## Methods

- `Void OnEnable()`

- `Void Render(TradingOrderRequireStruct, Boolean)`

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__13_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingRequireItemView : MonoBehaviour
{
	private const String ANIM_COMPLETE_KEY; // 0x0
	private BuildingTradingRequireItemInfo _completeInfo; // 0x18
	private BuildingTradingRequireItemInfo _uncompleteInfo; // 0x20
	private UIItemCard _itemPrefab; // 0x28
	private RectTransform _itemContainer; // 0x30
	private Single _itemScaler; // 0x38
	private Animator _animator; // 0x40
	private Boolean m_isInited; // 0x48
	private UIItemViewModel m_itemModel; // 0x50
	private UIItemCard m_itemCard; // 0x58
	private Boolean m_isOrderComplete; // 0x60


	// RVA: 0x3d8ab40 VA: 0x75963a2b40
	private Void OnEnable() { }
	// RVA: 0x3d8ab98 VA: 0x75963a2b98
	public Void Render(TradingOrderRequireStruct requireStruct, Boolean isOrderComplete) { }
	// RVA: 0x3d8acdc VA: 0x75963a2cdc
	private Void _InitIfNot() { }
	// RVA: 0x3d8ae78 VA: 0x75963a2e78
	public Void .ctor() { }
	// RVA: 0x3d8aef4 VA: 0x75963a2ef4
	private Void <_InitIfNot>b__13_0(Int32 _) { }
}
```