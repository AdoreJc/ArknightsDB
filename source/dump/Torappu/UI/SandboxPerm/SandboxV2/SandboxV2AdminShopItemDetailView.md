# SandboxV2AdminShopItemDetailView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _textDesc`

- `Text _textUsage`

- `Image _imgItemIcon`

- `GameObject _panelOriginPrice`

- `Text _textOwnCount`

- `Text _textGoodItemCount`

- `Text _textBuyCount`

- `Text _textStock`

- `Image _imgDiscountGold`

- `Image _imgDiscountDimensionCoin`

- `UILongPressButtonEx _btnIncrease`

- `UILongPressButtonEx _btnDecrease`

- `UIStateFinder m_stateFinder`

- `Boolean m_hasInited`


## Methods

- `Void OnBuyBtnClicked()`

- `Void _InitIfNot()`

- `Void _OnIncreaseBtnClicked()`

- `Boolean _OnIncreaseBtnLongPressed()`

- `Void _OnDecreaseBtnClicked()`

- `Boolean _OnDecreaseBtnLongPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminShopItemDetailView : DataBinder`1, IHotfixable
{
	private Text[] _textName; // 0x20
	private Text _textDesc; // 0x28
	private Text _textUsage; // 0x30
	private Image _imgItemIcon; // 0x38
	private GameObject[] _panelGold; // 0x40
	private GameObject[] _panelDimensionCoin; // 0x48
	private GameObject _panelOriginPrice; // 0x50
	private Text[] _textOriginPrice; // 0x58
	private Text[] _textCurrentPrice; // 0x60
	private Text _textOwnCount; // 0x68
	private Text _textGoodItemCount; // 0x70
	private Text _textBuyCount; // 0x78
	private Text _textStock; // 0x80
	private Text[] _textPrice; // 0x88
	private Image _imgDiscountGold; // 0x90
	private Image _imgDiscountDimensionCoin; // 0x98
	private Image[] _imgGold; // 0xa0
	private Image[] _imgDimensionCoin; // 0xa8
	private MaskableGraphic[] _graphicGold; // 0xb0
	private MaskableGraphic[] _graphicDimensionCoin; // 0xb8
	private UILongPressButtonEx _btnIncrease; // 0xc0
	private UILongPressButtonEx _btnDecrease; // 0xc8
	private Button[] _btnBuy; // 0xd0
	private UIStateFinder m_stateFinder; // 0xd8
	private Boolean m_hasInited; // 0xe8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnBuyBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnIncreaseBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnIncreaseBtnLongPressed; // 0x20
	private static DelegateBridge __Hotfix0__OnDecreaseBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnDecreaseBtnLongPressed; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x24f8ed4 VA: 0x7594b10ed4
	public override Void OnValueChanged(SandboxV2AdminShopItemDetailProperty property) { }
	// RVA: 0x24f9998 VA: 0x7594b11998
	public Void OnBuyBtnClicked() { }
	// RVA: 0x24f9740 VA: 0x7594b11740
	private Void _InitIfNot() { }
	// RVA: 0x24f9a3c VA: 0x7594b11a3c
	private Void _OnIncreaseBtnClicked() { }
	// RVA: 0x24f9ae0 VA: 0x7594b11ae0
	private Boolean _OnIncreaseBtnLongPressed() { }
	// RVA: 0x24f9b50 VA: 0x7594b11b50
	private Void _OnDecreaseBtnClicked() { }
	// RVA: 0x24f9bf4 VA: 0x7594b11bf4
	private Boolean _OnDecreaseBtnLongPressed() { }
	// RVA: 0x24f9c64 VA: 0x7594b11c64
	public Void .ctor() { }
}
```