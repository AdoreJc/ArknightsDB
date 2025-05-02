# SkinSelectPriceViewObj

**Namespace:** `Torappu.UI.Skin`


## Fields

- `Text _price`

- `Text _originPrice`

- `GameObject _originPricePart`

- `Image _priceIcon`


## Methods

- `Void Render(ShopSkinItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinSelectPriceViewObj : MonoBehaviour, IHotfixable
{
	private Text _price; // 0x18
	private Text _originPrice; // 0x20
	private GameObject _originPricePart; // 0x28
	private Image _priceIcon; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x23d5e54 VA: 0x75949ede54
	public Void Render(ShopSkinItemViewModel skinShopViewModel) { }
	// RVA: 0x23d61a4 VA: 0x75949ee1a4
	public Void .ctor() { }
}
```