# SkinSelectDetailView

**Namespace:** `Torappu.UI.Skin`


## Fields

- `GameObject _buyState`

- `GameObject _withGiftPart`

- `GameObject _withoutGiftPart`

- `Image _giftImage`

- `GameObject _giftCard`

- `GameObject _wearState`

- `GameObject _wearingState`

- `GameObject _noCharState`

- `GameObject _onlyShowState`

- `GameObject _diffTmplState`

- `GameObject _voucherExchangeState`

- `GameObject _hasGotState`

- `GameObject _notRedeemState`

- `Text _textTmplNotMatch`

- `Text _detailBuyText`

- `CanvasGroup _canvasGroup`

- `UISkinEvent _onClick`

- `UISkinEvent _onReleaseClick`

- `SkinSelectViewModel m_cacheViewModel`

- `UIItemViewModel m_giftModel`

- `Boolean m_isInited`


## Methods

- `Void OnClick()`

- `Void OnReleaseClick()`

- `Void OnGiftInfoClick()`

- `Void Init(Single, SkinSelectViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinSelectDetailView : MonoBehaviour, IHotfixable
{
	private GameObject _buyState; // 0x18
	private GameObject _withGiftPart; // 0x20
	private GameObject _withoutGiftPart; // 0x28
	private Image _giftImage; // 0x30
	private GameObject _giftCard; // 0x38
	private GameObject _wearState; // 0x40
	private GameObject _wearingState; // 0x48
	private GameObject _noCharState; // 0x50
	private GameObject _onlyShowState; // 0x58
	private GameObject _diffTmplState; // 0x60
	private GameObject _voucherExchangeState; // 0x68
	private GameObject _hasGotState; // 0x70
	private GameObject _notRedeemState; // 0x78
	private Text _textTmplNotMatch; // 0x80
	private Text _detailBuyText; // 0x88
	private CanvasGroup _canvasGroup; // 0x90
	private UISkinEvent _onClick; // 0x98
	private UISkinEvent _onReleaseClick; // 0xa0
	private SkinSelectViewModel m_cacheViewModel; // 0xa8
	private UIItemViewModel m_giftModel; // 0xb0
	private Boolean m_isInited; // 0xb8
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0_OnReleaseClick; // 0x8
	private static DelegateBridge __Hotfix0_OnGiftInfoClick; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x23d494c VA: 0x75949ec94c
	public Void OnClick() { }
	// RVA: 0x23d49e4 VA: 0x75949ec9e4
	public Void OnReleaseClick() { }
	// RVA: 0x23d4a7c VA: 0x75949eca7c
	public Void OnGiftInfoClick() { }
	// RVA: 0x23d4b08 VA: 0x75949ecb08
	public Void Init(Single state, SkinSelectViewModel viewModel) { }
	// RVA: 0x23d4f54 VA: 0x75949ecf54
	private Void _InitIfNot() { }
	// RVA: 0x23d50f0 VA: 0x75949ed0f0
	public Void .ctor() { }
}
```