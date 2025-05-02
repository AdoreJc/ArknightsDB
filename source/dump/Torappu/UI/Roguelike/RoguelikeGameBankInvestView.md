# RoguelikeGameBankInvestView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textCurrent`

- `Text _textTarget`

- `CanvasGroup _btnAlphaHandler`

- `Single _btnInactiveAlpha`

- `Button _btnConfirm`

- `TwoStateToggle _toggleConfirmText`

- `RoguelikeBankInvestControllerBindings m_controllerBindings`


## Methods

- `Void BindShopController(RoguelikeBankInvestControllerBindings)`

- `Void OnInvest()`

- `Void OnCancel()`

- `Void OnOpenBankReward()`

- `Void <>xLuaBaseProxy_Render(RoguelikeGameBankViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameBankInvestView : RoguelikeGameShopBaseView
{
	private Text _textCurrent; // 0x48
	private Text _textTarget; // 0x50
	private CanvasGroup _btnAlphaHandler; // 0x58
	private Single _btnInactiveAlpha; // 0x60
	private Button _btnConfirm; // 0x68
	private TwoStateToggle _toggleConfirmText; // 0x70
	private RoguelikeBankInvestControllerBindings m_controllerBindings; // 0x78
	private static DelegateBridge __Hotfix0_GetShopStatus; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_BindShopController; // 0x10
	private static DelegateBridge __Hotfix0_OnInvest; // 0x18
	private static DelegateBridge __Hotfix0_OnCancel; // 0x20
	private static DelegateBridge __Hotfix0_OnOpenBankReward; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2ade750 VA: 0x75950f6750
	public override RoguelikeGameShopStatusEnum GetShopStatus() { }
	// RVA: 0x2ade7b8 VA: 0x75950f67b8
	public override Void Render(RoguelikeGameBankViewModel bankModel) { }
	// RVA: 0x2ad69a4 VA: 0x75950ee9a4
	public Void BindShopController(RoguelikeBankInvestControllerBindings bindings) { }
	// RVA: 0x2ade968 VA: 0x75950f6968
	public Void OnInvest() { }
	// RVA: 0x2adea64 VA: 0x75950f6a64
	public Void OnCancel() { }
	// RVA: 0x2adeb60 VA: 0x75950f6b60
	public Void OnOpenBankReward() { }
	// RVA: 0x2adec5c VA: 0x75950f6c5c
	public Void .ctor() { }
	// RVA: 0x2adecd4 VA: 0x75950f6cd4
	private Void <>xLuaBaseProxy_Render(RoguelikeGameBankViewModel P0) { }
}
```