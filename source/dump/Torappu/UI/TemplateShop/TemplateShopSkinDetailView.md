# TemplateShopSkinDetailView

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `Transform _imageContainer`

- `Text _skinName`

- `Text _charName`

- `Text _skinDetail`

- `Text _skinUsage`

- `Image _skinBar`

- `Text _skinItemInfo`

- `Text _priceText`

- `Text _priceText2`

- `Image _priceIcon`

- `Image _priceIcon2`

- `UIItemCard _itemCard`

- `Transform _itemContainer`

- `Single _itemScale`

- `Image _buttonImage`

- `Image _brandImage`

- `Text _constText`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `String m_cacheId`

- `UICharacterIllust m_illust`


## Methods

- `Void _InitedIfNot()`

- `Void RenderSkinWithSkinId(String)`

- `Void OnOpenSkinDetail()`

- `Void Render(TemplateCommonShopGoodViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopSkinDetailView : MonoBehaviour, IHotfixable
{
	private Transform _imageContainer; // 0x18
	private Text _skinName; // 0x20
	private Text _charName; // 0x28
	private Text _skinDetail; // 0x30
	private Text _skinUsage; // 0x38
	private Image _skinBar; // 0x40
	private Text _skinItemInfo; // 0x48
	private Text _priceText; // 0x50
	private Text _priceText2; // 0x58
	private Image _priceIcon; // 0x60
	private Image _priceIcon2; // 0x68
	private UIItemCard _itemCard; // 0x70
	private Transform _itemContainer; // 0x78
	private Single _itemScale; // 0x80
	private Image _buttonImage; // 0x88
	private Image _brandImage; // 0x90
	private Text _constText; // 0x98
	private Boolean m_isInited; // 0xa0
	private UIItemCard m_itemCard; // 0xa8
	private String m_cacheId; // 0xb0
	private UICharacterIllust m_illust; // 0xb8
	private static DelegateBridge __Hotfix0__InitedIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderSkinWithSkinId; // 0x8
	private static DelegateBridge __Hotfix0_OnOpenSkinDetail; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x23602c0 VA: 0x75949782c0
	private Void _InitedIfNot() { }
	// RVA: 0x236044c VA: 0x759497844c
	public Void RenderSkinWithSkinId(String skinId) { }
	// RVA: 0x2360810 VA: 0x7594978810
	public Void OnOpenSkinDetail() { }
	// RVA: 0x2357a0c VA: 0x759496fa0c
	public Void Render(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x236087c VA: 0x759497887c
	public Void .ctor() { }
}
```