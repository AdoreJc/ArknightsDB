# VoucherSkinGoodView

**Namespace:** `Torappu.UI.VoucherSkin`


## Fields

- `Text _textSkinName`

- `Text _textCharName`

- `GameObject _objHasGot`

- `GameObject _notRedeem`

- `UIAtlasImage _imgPortrait`

- `Image _imgLogo`

- `Button _buttonPart`

- `VoucherSkinGoodViewModel m_cacheModel`


## Methods

- `Void set_onClicked(Action`1)`

- `Void Render(VoucherSkinGoodViewModel)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoucherSkin
public class VoucherSkinGoodView : MonoBehaviour, IHotfixable
{
	private Text _textSkinName; // 0x18
	private Text _textCharName; // 0x20
	private GameObject _objHasGot; // 0x28
	private GameObject _notRedeem; // 0x30
	private UIAtlasImage _imgPortrait; // 0x38
	private Image _imgLogo; // 0x40
	private Button _buttonPart; // 0x48
	private VoucherSkinGoodViewModel m_cacheModel; // 0x50
	private Action`1 <onClicked>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Action`1 onClicked { get; set; }

	// RVA: 0x2291db0 VA: 0x75948a9db0
	public Action`1 get_onClicked() { }
	// RVA: 0x2291e18 VA: 0x75948a9e18
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x2291e9c VA: 0x75948a9e9c
	public Void Render(VoucherSkinGoodViewModel viewModel) { }
	// RVA: 0x22921e8 VA: 0x75948aa1e8
	public Void EventOnClicked() { }
	// RVA: 0x2292288 VA: 0x75948aa288
	public Void .ctor() { }
}
```