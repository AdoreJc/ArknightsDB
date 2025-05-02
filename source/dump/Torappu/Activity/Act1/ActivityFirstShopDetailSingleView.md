# ActivityFirstShopDetailSingleView

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `Text _shopItemName`

- `Text _itemDetailCount`

- `ShopDetailItemPileView _pileView`

- `Text _itemDetail`

- `Text _itemDetail_2`

- `Text _singlePrice`

- `ActivityShopData m_cacheViewModel`


## Methods

- `Void ApplyData(ActivityShopData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstShopDetailSingleView : MonoBehaviour, IHotfixable
{
	private Text _shopItemName; // 0x18
	private Text _itemDetailCount; // 0x20
	private ShopDetailItemPileView _pileView; // 0x28
	protected Text _itemDetail; // 0x30
	protected Text _itemDetail_2; // 0x38
	private Text _singlePrice; // 0x40
	protected ActivityShopData m_cacheViewModel; // 0x48
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x348c4a4 VA: 0x7595aa44a4
	public Void ApplyData(ActivityShopData viewModel) { }
	// RVA: 0x348c710 VA: 0x7595aa4710
	public Void .ctor() { }
}
```