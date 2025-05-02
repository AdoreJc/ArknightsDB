# StageUseDiamondView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _restoreAP`

- `Text _remainDiamond`

- `Text _detailText`

- `Text _remainText`

- `GameObject _upPart`

- `GameObject _downPart`

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
// Namespace : Torappu.UI.Stage
public class StageUseDiamondView : MonoBehaviour, IHotfixable
{
	private Text _restoreAP; // 0x18
	private Text _remainDiamond; // 0x20
	private Text _detailText; // 0x28
	private Text _remainText; // 0x30
	private GameObject _upPart; // 0x38
	private GameObject _downPart; // 0x40
	private Transform _itemContainer; // 0x48
	private Single _itemScale; // 0x50
	private GameObject _hasLimitObj; // 0x58
	private UIItemCard m_itemCard; // 0x60
	private UIItemViewModel m_itemModel; // 0x68
	private Boolean m_isInited; // 0x70
	private static DelegateBridge __Hotfix0__InitItemIfNot; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2f8be54 VA: 0x75955a3e54
	private Void _InitItemIfNot() { }
	// RVA: 0x2f8c068 VA: 0x75955a4068
	public Void InitData() { }
	// RVA: 0x2f8c3c0 VA: 0x75955a43c0
	public Void .ctor() { }
}
```