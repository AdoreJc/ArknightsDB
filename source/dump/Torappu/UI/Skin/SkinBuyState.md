# SkinBuyState

**Namespace:** `Torappu.UI.Skin`


## Fields

- `SkinSelectStateBean _stateBean`

- `GameObject _cashPart`

- `GameObject _diamondPart`

- `Image _imgDiamond`

- `Image _imgCash`

- `Text _priceText`

- `Text _infoText`

- `Text _tmplText`

- `Transform _container`

- `GameObject _objBuyPart`

- `GameObject _objVoucherPart`

- `Text _textVoucherTitle`

- `Text _textVoucherDesc`

- `SkinShopPerItemView m_cacheView`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void SendBuyState()`

- `Void _RenderPaymentInfo(SkinSelectViewModel)`

- `String _GetVoucherItemName()`

- `Void _SendGetSkinViaVoucher(SkinShopViewModel)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinBuyState : PopupFloatState
{
	private SkinSelectStateBean _stateBean; // 0x70
	private GameObject _cashPart; // 0x78
	private GameObject _diamondPart; // 0x80
	private Image _imgDiamond; // 0x88
	private Image _imgCash; // 0x90
	private Text _priceText; // 0x98
	private Text _infoText; // 0xa0
	private Text _tmplText; // 0xa8
	private Transform _container; // 0xb0
	private GameObject _objBuyPart; // 0xb8
	private GameObject _objVoucherPart; // 0xc0
	private Text _textVoucherTitle; // 0xc8
	private Text _textVoucherDesc; // 0xd0
	private SkinShopPerItemView m_cacheView; // 0xd8
	private Boolean m_isInited; // 0xe0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_SendBuyState; // 0x18
	private static DelegateBridge __Hotfix0__RenderPaymentInfo; // 0x20
	private static DelegateBridge __Hotfix0__GetVoucherItemName; // 0x28
	private static DelegateBridge __Hotfix0__SendGetSkinViaVoucher; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x23cfda4 VA: 0x75949e7da4
	private Void _InitIfNot() { }
	// RVA: 0x23cfea4 VA: 0x75949e7ea4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23cff0c VA: 0x75949e7f0c
	protected override Void OnEnter() { }
	// RVA: 0x23d063c VA: 0x75949e863c
	public Void SendBuyState() { }
	// RVA: 0x23d0284 VA: 0x75949e8284
	private Void _RenderPaymentInfo(SkinSelectViewModel skinViewModel) { }
	// RVA: 0x23d0b84 VA: 0x75949e8b84
	private String _GetVoucherItemName() { }
	// RVA: 0x23d0828 VA: 0x75949e8828
	private Void _SendGetSkinViaVoucher(SkinShopViewModel viewModel) { }
	// RVA: 0x23d0ccc VA: 0x75949e8ccc
	public Void .ctor() { }
	// RVA: 0x23d0d3c VA: 0x75949e8d3c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```