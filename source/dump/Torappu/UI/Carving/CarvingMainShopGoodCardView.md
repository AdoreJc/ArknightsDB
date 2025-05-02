# CarvingMainShopGoodCardView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Color _notEnoughSelectTextColor`

- `Color _notEnoughNotSelectTextColor`

- `Color _enoughSelectTextColor`

- `Color _enoughNotSelectTextColor`

- `Text _priceTxt`

- `GameObject _priceBgEnough`

- `GameObject _priceBgNotEnough`

- `CanvasGroup _cardGroup`

- `RectTransform _cardContent`

- `CarvingMainCardView _cardViewPrefab`

- `Single _cardScaler`

- `UIColorGraphic _colorGraphic`

- `GameObject _emptyObj`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Int32 m_cachedPos`

- `CarvingMainCardView m_cardView`

- `FadeSwitchTween m_fadeSwitchTween`


## Methods

- `Void Render(CarvingMainShopGoodCardItemModel, Boolean)`

- `Void _InitIfNot()`

- `Void OnClickSelectItemBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainShopGoodCardView : MonoBehaviour, IHotfixable
{
	private Color _notEnoughSelectTextColor; // 0x18
	private Color _notEnoughNotSelectTextColor; // 0x28
	private Color _enoughSelectTextColor; // 0x38
	private Color _enoughNotSelectTextColor; // 0x48
	private Text _priceTxt; // 0x58
	private GameObject _priceBgEnough; // 0x60
	private GameObject _priceBgNotEnough; // 0x68
	private CanvasGroup _cardGroup; // 0x70
	private RectTransform _cardContent; // 0x78
	private CarvingMainCardView _cardViewPrefab; // 0x80
	private Single _cardScaler; // 0x88
	private UIColorGraphic _colorGraphic; // 0x90
	private GameObject _emptyObj; // 0x98
	private Boolean m_isInited; // 0xa0
	private UIPageFinder m_pageFinder; // 0xa8
	private Int32 m_cachedPos; // 0xb8
	private CarvingMainCardView m_cardView; // 0xc0
	private FadeSwitchTween m_fadeSwitchTween; // 0xc8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClickSelectItemBtn; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2db6d00 VA: 0x75953ced00
	public Void Render(CarvingMainShopGoodCardItemModel model, Boolean isEnough) { }
	// RVA: 0x2db6f74 VA: 0x75953cef74
	private Void _InitIfNot() { }
	// RVA: 0x2db7100 VA: 0x75953cf100
	public Void OnClickSelectItemBtn() { }
	// RVA: 0x2db71f0 VA: 0x75953cf1f0
	public Void .ctor() { }
}
```