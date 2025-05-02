# TemplateShopResHolder

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `Sprite _priceIcon`

- `Sprite _priceIconWithShadow`

- `Color _priceColor`

- `Color _resBarColor`

- `Sprite _resBarCoinWithIcon`

- `Boolean _textColorBlackFlag`

- `Sprite _titleImg`

- `Sprite _bannerImg`

- `Sprite _backImg`

- `Sprite _shopIcon`

- `Sprite _groupBG`

- `AutoPackSpriteHub _groupBkgHub`


## Methods

- `Sprite GetPriceIcon()`

- `Color GetPriceColor()`

- `Sprite GetPriceColoredIconWithShadow()`

- `Sprite GetResBarIcon()`

- `Color GetResBarColor()`

- `Color GetTextColor()`

- `Sprite GetTitleImg()`

- `Sprite GetBannerImg()`

- `Sprite GetBackImg()`

- `Sprite GetShopIcon()`

- `Boolean ShouldUseCustomRarityBg()`

- `AutoPackSpriteHub GetCustomGroupBgHub()`

- `Boolean ShouldUseGroupBg()`

- `Sprite GetCustomGroupBg()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopResHolder : MonoBehaviour, IHotfixable
{
	private Sprite _priceIcon; // 0x18
	private Sprite _priceIconWithShadow; // 0x20
	private Color _priceColor; // 0x28
	private Color _resBarColor; // 0x38
	private Sprite _resBarCoinWithIcon; // 0x48
	private Boolean _textColorBlackFlag; // 0x50
	private Sprite _titleImg; // 0x58
	private Sprite _bannerImg; // 0x60
	private Sprite _backImg; // 0x68
	private Sprite _shopIcon; // 0x70
	private Sprite[] _customRarityBgList; // 0x78
	private Sprite _groupBG; // 0x80
	private AutoPackSpriteHub _groupBkgHub; // 0x88
	private static DelegateBridge __Hotfix0_GetPriceIcon; // 0x0
	private static DelegateBridge __Hotfix0_GetPriceColor; // 0x8
	private static DelegateBridge __Hotfix0_GetPriceColoredIconWithShadow; // 0x10
	private static DelegateBridge __Hotfix0_GetResBarIcon; // 0x18
	private static DelegateBridge __Hotfix0_GetResBarColor; // 0x20
	private static DelegateBridge __Hotfix0_GetTextColor; // 0x28
	private static DelegateBridge __Hotfix0_GetTitleImg; // 0x30
	private static DelegateBridge __Hotfix0_GetBannerImg; // 0x38
	private static DelegateBridge __Hotfix0_GetBackImg; // 0x40
	private static DelegateBridge __Hotfix0_GetShopIcon; // 0x48
	private static DelegateBridge __Hotfix0_ShouldUseCustomRarityBg; // 0x50
	private static DelegateBridge __Hotfix0_GetCustomRarityBgList; // 0x58
	private static DelegateBridge __Hotfix0_GetCustomGroupBgHub; // 0x60
	private static DelegateBridge __Hotfix0_ShouldUseGroupBg; // 0x68
	private static DelegateBridge __Hotfix0_GetCustomGroupBg; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2358f24 VA: 0x7594970f24
	public Sprite GetPriceIcon() { }
	// RVA: 0x2358f8c VA: 0x7594970f8c
	public Color GetPriceColor() { }
	// RVA: 0x2358ff4 VA: 0x7594970ff4
	public Sprite GetPriceColoredIconWithShadow() { }
	// RVA: 0x235905c VA: 0x759497105c
	public Sprite GetResBarIcon() { }
	// RVA: 0x23590c4 VA: 0x75949710c4
	public Color GetResBarColor() { }
	// RVA: 0x235912c VA: 0x759497112c
	public Color GetTextColor() { }
	// RVA: 0x23591dc VA: 0x75949711dc
	public Sprite GetTitleImg() { }
	// RVA: 0x23559b8 VA: 0x759496d9b8
	public Sprite GetBannerImg() { }
	// RVA: 0x2355a20 VA: 0x759496da20
	public Sprite GetBackImg() { }
	// RVA: 0x23557a0 VA: 0x759496d7a0
	public Sprite GetShopIcon() { }
	// RVA: 0x2359244 VA: 0x7594971244
	public Boolean ShouldUseCustomRarityBg() { }
	// RVA: 0x23592d0 VA: 0x75949712d0
	public Sprite[] GetCustomRarityBgList() { }
	// RVA: 0x2359338 VA: 0x7594971338
	public AutoPackSpriteHub GetCustomGroupBgHub() { }
	// RVA: 0x23593a0 VA: 0x75949713a0
	public Boolean ShouldUseGroupBg() { }
	// RVA: 0x2359438 VA: 0x7594971438
	public Sprite GetCustomGroupBg() { }
	// RVA: 0x23583d8 VA: 0x75949703d8
	public Void .ctor() { }
}
```