# HomeAPUseDiamondView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _restoreAP`

- `Text _detailText`

- `Text _remainText`

- `GameObject _upPart`

- `GameObject _downPart`

- `UIItemCard _itemCard`

- `Transform _itemContainer`

- `Single _itemScale`

- `GameObject _hasLimitObj`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`

- `Boolean m_isInited`


## Methods

- `Void _InitItemIfNot()`

- `Void InitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeAPUseDiamondView : MonoBehaviour, IHotfixable
{
	private Text _restoreAP; // 0x18
	private Text _detailText; // 0x20
	private Text _remainText; // 0x28
	private GameObject _upPart; // 0x30
	private GameObject _downPart; // 0x38
	private UIItemCard _itemCard; // 0x40
	private Transform _itemContainer; // 0x48
	private Single _itemScale; // 0x50
	private GameObject _hasLimitObj; // 0x58
	private UIItemCard m_itemCard; // 0x60
	private UIItemViewModel m_itemModel; // 0x68
	private Boolean m_isInited; // 0x70
	private static DelegateBridge __Hotfix0__InitItemIfNot; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x282c16c VA: 0x7594e4416c
	private Void _InitItemIfNot() { }
	// RVA: 0x282c350 VA: 0x7594e44350
	public Void InitData() { }
	// RVA: 0x282c67c VA: 0x7594e4467c
	public Void .ctor() { }
}
```