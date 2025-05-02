# CardSelectPanelShowTween

**Namespace:** ` `


## Fields

- `UIBattleLegionCardSelectPanel m_closure`

- `TweenWrapper m_tween`


## Methods

- `Void PlayTween()`

- `Void _AfterShowEffect()`

- `Void _AfterShowCards()`

- `Void ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CardSelectPanelShowTween : IHotfixable
{
	private UIBattleLegionCardSelectPanel m_closure; // 0x10
	private TweenWrapper m_tween; // 0x18
	private const Single ENTER_PANEL_DELAY; // 0x0
	private const Single CARD_SHOW_DUR; // 0x0
	private const Single CARD_SHOW_DELAY; // 0x0
	private const Single ENTER_BTN_DELAY; // 0x0
	private const Single ENTER_BTN_SHOW_DUR; // 0x0
	private const Single ENTER_BTN_MOVE_DUR; // 0x0
	private static readonly Vector2 CARD_SHOW_START_POS; // 0x0
	private static readonly Vector2 CARD_SHOW_END_POS; // 0x8
	private static readonly Vector2 CANCEL_BTN_START_POS; // 0x10
	private static readonly Vector2 CANCEL_BTN_END_POS; // 0x18
	private static readonly Vector2 CONFIRM_BTN_START_POS; // 0x20
	private static readonly Vector2 CONFIRM_BTN_END_POS; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30
	private static DelegateBridge __Hotfix0_PlayTween; // 0x38
	private static DelegateBridge __Hotfix0__AfterShowEffect; // 0x40
	private static DelegateBridge __Hotfix0__AfterShowCards; // 0x48
	private static DelegateBridge __Hotfix0_ResetToState; // 0x50


	// RVA: 0x1db5fa0 VA: 0x75943cdfa0
	public Void .ctor(UIBattleLegionCardSelectPanel closure) { }
	// RVA: 0x1db6db4 VA: 0x75943cedb4
	public Void PlayTween() { }
	// RVA: 0x1db7364 VA: 0x75943cf364
	private Void _AfterShowEffect() { }
	// RVA: 0x1db742c VA: 0x75943cf42c
	private Void _AfterShowCards() { }
	// RVA: 0x1db5230 VA: 0x75943cd230
	public Void ResetToState(Boolean isShow) { }
	// RVA: 0x1db753c VA: 0x75943cf53c
	private static Void .cctor() { }
}
```