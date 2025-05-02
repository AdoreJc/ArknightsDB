# RoguelikeGameBankConsumeWithdrawView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textBankCount`

- `Text _textCurrentWithdraw`

- `Text _textWithdrawCaption`

- `Image _imgItemIcon`

- `CanvasGroup _btnAlphaHandler`

- `Single _btnInactiveAlpha`

- `Button _btnConfirm`

- `Boolean m_hasInited`

- `UIStateFinder m_finder`


## Methods

- `Void _InitIfNot(RoguelikeGameBankViewModel)`

- `Void OnBtnWithdraw()`

- `Void OnBtnCancel()`

- `Void IncrementCurrent()`

- `Void DecrementCurrent()`

- `Void MaxCurrent()`

- `Void MinCurrent()`

- `RoguelikeGameBankWithdrawlViewType <>xLuaBaseProxy_get_viewType()`

- `Void <>xLuaBaseProxy_Render(RoguelikeGameBankViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameBankConsumeWithdrawView : RoguelikeGameBankWithdrawlBaseView`1
{
	private Text _textBankCount; // 0x50
	private Text _textCurrentWithdraw; // 0x58
	private Text _textWithdrawCaption; // 0x60
	private Image _imgItemIcon; // 0x68
	private CanvasGroup _btnAlphaHandler; // 0x70
	private Single _btnInactiveAlpha; // 0x78
	private Button _btnConfirm; // 0x80
	private Boolean m_hasInited; // 0x88
	private UIStateFinder m_finder; // 0x90
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_BindShopController; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnBtnWithdraw; // 0x20
	private static DelegateBridge __Hotfix0_OnBtnCancel; // 0x28
	private static DelegateBridge __Hotfix0_IncrementCurrent; // 0x30
	private static DelegateBridge __Hotfix0_DecrementCurrent; // 0x38
	private static DelegateBridge __Hotfix0_MaxCurrent; // 0x40
	private static DelegateBridge __Hotfix0_MinCurrent; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override RoguelikeGameBankWithdrawlViewType viewType { get; }

	// RVA: 0x2adcf38 VA: 0x75950f4f38
	public override RoguelikeGameBankWithdrawlViewType get_viewType() { }
	// RVA: 0x2adcfa0 VA: 0x75950f4fa0
	public override Void Render(RoguelikeGameBankViewModel bankModel) { }
	// RVA: 0x2add390 VA: 0x75950f5390
	protected override Void BindShopController(RoguelikeBankConsumeWithdrawShopControllerBindings bindings) { }
	// RVA: 0x2add1c4 VA: 0x75950f51c4
	private Void _InitIfNot(RoguelikeGameBankViewModel bankModel) { }
	// RVA: 0x2add47c VA: 0x75950f547c
	public Void OnBtnWithdraw() { }
	// RVA: 0x2add578 VA: 0x75950f5578
	public Void OnBtnCancel() { }
	// RVA: 0x2add674 VA: 0x75950f5674
	public Void IncrementCurrent() { }
	// RVA: 0x2add770 VA: 0x75950f5770
	public Void DecrementCurrent() { }
	// RVA: 0x2add86c VA: 0x75950f586c
	public Void MaxCurrent() { }
	// RVA: 0x2add968 VA: 0x75950f5968
	public Void MinCurrent() { }
	// RVA: 0x2adda64 VA: 0x75950f5a64
	public Void .ctor() { }
	// RVA: 0x2addb00 VA: 0x75950f5b00
	private RoguelikeGameBankWithdrawlViewType <>xLuaBaseProxy_get_viewType() { }
	// RVA: 0x2addb68 VA: 0x75950f5b68
	private Void <>xLuaBaseProxy_Render(RoguelikeGameBankViewModel P0) { }
}
```