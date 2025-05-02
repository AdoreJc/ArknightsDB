# SkinShopPerItemView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Image _portraitImage`

- `Transform _dynContainer`

- `Image _groupImage`

- `Text _timeLimitText`

- `GameObject _backImg`

- `GameObject _backImgDyn`

- `GameObject _backShadowDyn`

- `GameObject _timeLimitObj`

- `GameObject _offsetPart`

- `Text _offsetText`

- `Text _skinName`

- `Text _charName`

- `GameObject _giftFloatPart`

- `Image _giftFloatImage`

- `GameObject _giftSidePart`

- `Image _giftSideImage`

- `Text _giftSideText`

- `GameObject _cashPart`

- `Text _offsetPriceCash`

- `Text _currentPriceCash`

- `GameObject _diamondPart`

- `Text _offsetPriceDiamond`

- `Text _currentPriceDiamond`

- `GameObject _soldOutPart`

- `GameObject _objVoucherPart`

- `UIColorGraphic _colorGraphic`

- `UIStringEvent clickEvent`

- `UICharacterDynPortrait m_dynPortrait`

- `CharUISkinStruct m_cacheStruct`

- `SkinShopViewModel m_cacheViewModel`


## Properties

- `Boolean isAvailable`


## Methods

- `Boolean get_isAvailable()`

- `Void EnterDetailEvent()`

- `Void OnClick()`

- `Void Render(SkinShopViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class SkinShopPerItemView : MonoBehaviour, IHotfixable
{
	private Image _portraitImage; // 0x18
	private Transform _dynContainer; // 0x20
	private Image _groupImage; // 0x28
	private Text _timeLimitText; // 0x30
	private GameObject _backImg; // 0x38
	private GameObject _backImgDyn; // 0x40
	private GameObject _backShadowDyn; // 0x48
	private GameObject _timeLimitObj; // 0x50
	private GameObject _offsetPart; // 0x58
	private Text _offsetText; // 0x60
	private Text _skinName; // 0x68
	private Text _charName; // 0x70
	private GameObject _giftFloatPart; // 0x78
	private Image _giftFloatImage; // 0x80
	private GameObject _giftSidePart; // 0x88
	private Image _giftSideImage; // 0x90
	private Text _giftSideText; // 0x98
	private GameObject _cashPart; // 0xa0
	private Text _offsetPriceCash; // 0xa8
	private Text _currentPriceCash; // 0xb0
	private GameObject _diamondPart; // 0xb8
	private Text _offsetPriceDiamond; // 0xc0
	private Text _currentPriceDiamond; // 0xc8
	private GameObject _soldOutPart; // 0xd0
	private GameObject _objVoucherPart; // 0xd8
	private UIColorGraphic _colorGraphic; // 0xe0
	public UIStringEvent clickEvent; // 0xe8
	private UICharacterDynPortrait m_dynPortrait; // 0xf0
	private CharUISkinStruct m_cacheStruct; // 0xf8
	private SkinShopViewModel m_cacheViewModel; // 0x108
	private static DelegateBridge __Hotfix0_get_isAvailable; // 0x0
	private static DelegateBridge __Hotfix0_EnterDetailEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isAvailable { get; }

	// RVA: 0x246b9d0 VA: 0x7594a839d0
	public Boolean get_isAvailable() { }
	// RVA: 0x246ba50 VA: 0x7594a83a50
	public Void EnterDetailEvent() { }
	// RVA: 0x246baf0 VA: 0x7594a83af0
	public Void OnClick() { }
	// RVA: 0x246adf0 VA: 0x7594a82df0
	public Void Render(SkinShopViewModel viewModel) { }
	// RVA: 0x246c00c VA: 0x7594a8400c
	public Void .ctor() { }
}
```