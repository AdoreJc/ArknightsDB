# RoguelikeGameBankFaultyView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textBankCurrent`

- `RoguelikeBankFaultyControllerBindings m_controllerBindings`


## Methods

- `Void BindShopController(RoguelikeBankFaultyControllerBindings)`

- `Void OnCancel()`

- `Void OnOpenBankReward()`

- `Void <>xLuaBaseProxy_Render(RoguelikeGameBankViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameBankFaultyView : RoguelikeGameShopBaseView
{
	private Text _textBankCurrent; // 0x48
	private RoguelikeBankFaultyControllerBindings m_controllerBindings; // 0x50
	private static DelegateBridge __Hotfix0_GetShopStatus; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_BindShopController; // 0x10
	private static DelegateBridge __Hotfix0_OnCancel; // 0x18
	private static DelegateBridge __Hotfix0_OnOpenBankReward; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2ade35c VA: 0x75950f635c
	public override RoguelikeGameShopStatusEnum GetShopStatus() { }
	// RVA: 0x2ade3c4 VA: 0x75950f63c4
	public override Void Render(RoguelikeGameBankViewModel bankModel) { }
	// RVA: 0x2ad6aa4 VA: 0x75950eeaa4
	public Void BindShopController(RoguelikeBankFaultyControllerBindings bindings) { }
	// RVA: 0x2ade478 VA: 0x75950f6478
	public Void OnCancel() { }
	// RVA: 0x2ade574 VA: 0x75950f6574
	public Void OnOpenBankReward() { }
	// RVA: 0x2ade670 VA: 0x75950f6670
	public Void .ctor() { }
	// RVA: 0x2ade6dc VA: 0x75950f66dc
	private Void <>xLuaBaseProxy_Render(RoguelikeGameBankViewModel P0) { }
}
```