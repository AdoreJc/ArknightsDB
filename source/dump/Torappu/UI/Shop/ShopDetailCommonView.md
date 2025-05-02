# ShopDetailCommonView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `GameObject _offsetPart`

- `Text _offsetText`

- `GameObject _originPricePart`

- `Text _originPrice`

- `Image _originIcon`

- `Text _currentPrice`

- `Image _currentPriceIcon`

- `Text _itemDetail`

- `Text _itemDetail_2`

- `Text _itemName`

- `GameObject _timeLimitGameObject`

- `Text _timeLimitText`

- `Image _itemButton`

- `Text _itemButtonText`

- `Image _itemButtonIcon`

- `UnityEvent _disMissEvent`

- `Text _alreadyHaveCount`

- `DetailCommonViewModel m_cacheViewModel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailCommonView : MonoBehaviour, IHotfixable
{
	protected GameObject _offsetPart; // 0x18
	protected Text _offsetText; // 0x20
	protected GameObject _originPricePart; // 0x28
	protected Text _originPrice; // 0x30
	protected Image _originIcon; // 0x38
	protected Text _currentPrice; // 0x40
	protected Image _currentPriceIcon; // 0x48
	protected Text _itemDetail; // 0x50
	protected Text _itemDetail_2; // 0x58
	protected Text _itemName; // 0x60
	protected GameObject _timeLimitGameObject; // 0x68
	protected Text _timeLimitText; // 0x70
	protected Image _itemButton; // 0x78
	protected Text _itemButtonText; // 0x80
	protected Image _itemButtonIcon; // 0x88
	protected UnityEvent _disMissEvent; // 0x90
	protected Text _alreadyHaveCount; // 0x98
	protected DetailCommonViewModel m_cacheViewModel; // 0xa0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_GetMaxPrice; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x242f3dc VA: 0x7594a473dc
	public virtual Void ApplyData(DetailCommonViewModel viewModel, SpriteHub priceTypeHub) { }
	// RVA: 0x2431264 VA: 0x7594a49264
	public virtual Void OnClick() { }
	// RVA: 0x2431950 VA: 0x7594a49950
	public static Int32 GetMaxPrice(ShopDetailPriceType itemType, Int32 price, Int32 maxCount) { }
	// RVA: 0x242ff50 VA: 0x7594a47f50
	public Void .ctor() { }
}
```