# RoguelikeGameBankEntryView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textBankCurrent`

- `GameObject _btnWithdrawGo`

- `GameObject _faultyIconGo`

- `RoguelikeBankEntryControllerBindings m_controllerBindings`


## Methods

- `Void BindShopController(RoguelikeBankEntryControllerBindings)`

- `Void OnOpenWithdraw()`

- `Void OnOpenInvest()`

- `Void OnCancel()`

- `Void OnOpenBankReward()`

- `Void <>xLuaBaseProxy_Render(RoguelikeGameBankViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameBankEntryView : RoguelikeGameShopBaseView
{
	private Text _textBankCurrent; // 0x48
	private GameObject _btnWithdrawGo; // 0x50
	private GameObject _faultyIconGo; // 0x58
	private RoguelikeBankEntryControllerBindings m_controllerBindings; // 0x60
	private static DelegateBridge __Hotfix0_GetShopStatus; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_BindShopController; // 0x10
	private static DelegateBridge __Hotfix0_OnOpenWithdraw; // 0x18
	private static DelegateBridge __Hotfix0_OnOpenInvest; // 0x20
	private static DelegateBridge __Hotfix0_OnCancel; // 0x28
	private static DelegateBridge __Hotfix0_OnOpenBankReward; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2addc54 VA: 0x75950f5c54
	public override RoguelikeGameShopStatusEnum GetShopStatus() { }
	// RVA: 0x2addcbc VA: 0x75950f5cbc
	public override Void Render(RoguelikeGameBankViewModel bankModel) { }
	// RVA: 0x2ad6894 VA: 0x75950ee894
	public Void BindShopController(RoguelikeBankEntryControllerBindings bindings) { }
	// RVA: 0x2adde1c VA: 0x75950f5e1c
	public Void OnOpenWithdraw() { }
	// RVA: 0x2addf18 VA: 0x75950f5f18
	public Void OnOpenInvest() { }
	// RVA: 0x2ade014 VA: 0x75950f6014
	public Void OnCancel() { }
	// RVA: 0x2ade110 VA: 0x75950f6110
	public Void OnOpenBankReward() { }
	// RVA: 0x2ade20c VA: 0x75950f620c
	public Void .ctor() { }
	// RVA: 0x2ade2e8 VA: 0x75950f62e8
	private Void <>xLuaBaseProxy_Render(RoguelikeGameBankViewModel P0) { }
}
```