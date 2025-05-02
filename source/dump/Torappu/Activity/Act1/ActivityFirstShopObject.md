# ActivityFirstShopObject

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `Text _shopName`

- `Text _priceCount`

- `Transform _itemContainer`

- `Text _remainCount`

- `GameObject _soldOutPart`

- `CanvasGroup _soldOutCanvas`

- `Single _itemCardScaleFactor`

- `UIActShopEvent sendEvent`

- `ActivityShopData m_cacheShopData`

- `UIItemCard m_itemObj`

- `Boolean m_isInited`


## Methods

- `Void OnClick()`

- `Void _InitIfNot()`

- `Void InitData(ActivityShopData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstShopObject : MonoBehaviour, IHotfixable
{
	private Text _shopName; // 0x18
	private Text _priceCount; // 0x20
	private Transform _itemContainer; // 0x28
	private Text _remainCount; // 0x30
	private GameObject _soldOutPart; // 0x38
	private CanvasGroup _soldOutCanvas; // 0x40
	private Single _itemCardScaleFactor; // 0x48
	public UIActShopEvent sendEvent; // 0x50
	private ActivityShopData m_cacheShopData; // 0x58
	private UIItemCard m_itemObj; // 0x60
	private Boolean m_isInited; // 0x68
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_InitData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x348c780 VA: 0x7595aa4780
	public Void OnClick() { }
	// RVA: 0x348c884 VA: 0x7595aa4884
	private Void _InitIfNot() { }
	// RVA: 0x348c9f4 VA: 0x7595aa49f4
	public Void InitData(ActivityShopData shopData) { }
	// RVA: 0x348ccbc VA: 0x7595aa4cbc
	public Void .ctor() { }
}
```