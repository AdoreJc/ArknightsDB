# RoguelikeGameBankSimpleWithdrawView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textCurrent`

- `Text _textTarget`

- `CanvasGroup _btnAlphaHandler`

- `Single _btnInactiveAlpha`

- `Button _btnConfirm`

- `Text _textCost`

- `TwoStateToggle _toggleConfirmText`

- `Text _textTips`


## Methods

- `Void OnBtnWithdraw()`

- `Void OnBtnCancel()`

- `Void OnOpenBankReward()`

- `RoguelikeGameBankWithdrawlViewType <>xLuaBaseProxy_get_viewType()`

- `Void <>xLuaBaseProxy_Render(RoguelikeGameBankViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameBankSimpleWithdrawView : RoguelikeGameBankWithdrawlBaseView`1
{
	private Text _textCurrent; // 0x50
	private Text _textTarget; // 0x58
	private CanvasGroup _btnAlphaHandler; // 0x60
	private Single _btnInactiveAlpha; // 0x68
	private Button _btnConfirm; // 0x70
	private Text _textCost; // 0x78
	private TwoStateToggle _toggleConfirmText; // 0x80
	private Text _textTips; // 0x88
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_BindShopController; // 0x10
	private static DelegateBridge __Hotfix0_OnBtnWithdraw; // 0x18
	private static DelegateBridge __Hotfix0_OnBtnCancel; // 0x20
	private static DelegateBridge __Hotfix0_OnOpenBankReward; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override RoguelikeGameBankWithdrawlViewType viewType { get; }

	// RVA: 0x2adf0c4 VA: 0x75950f70c4
	public override RoguelikeGameBankWithdrawlViewType get_viewType() { }
	// RVA: 0x2adf12c VA: 0x75950f712c
	public override Void Render(RoguelikeGameBankViewModel bankModel) { }
	// RVA: 0x2adf600 VA: 0x75950f7600
	protected override Void BindShopController(RoguelikeBankWithdrawControllerBindings bindings) { }
	// RVA: 0x2adf684 VA: 0x75950f7684
	public Void OnBtnWithdraw() { }
	// RVA: 0x2adf780 VA: 0x75950f7780
	public Void OnBtnCancel() { }
	// RVA: 0x2adf87c VA: 0x75950f787c
	public Void OnOpenBankReward() { }
	// RVA: 0x2adf978 VA: 0x75950f7978
	public Void .ctor() { }
	// RVA: 0x2adfa14 VA: 0x75950f7a14
	private RoguelikeGameBankWithdrawlViewType <>xLuaBaseProxy_get_viewType() { }
	// RVA: 0x2adfa18 VA: 0x75950f7a18
	private Void <>xLuaBaseProxy_Render(RoguelikeGameBankViewModel P0) { }
}
```