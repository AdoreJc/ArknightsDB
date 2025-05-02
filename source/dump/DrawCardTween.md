# DrawCardTween

**Namespace:** ` `


## Fields

- `UIBattleLegionWidgetsPanel m_closure`

- `TweenWrapper m_tween`


## Methods

- `Void PlayGoldGlowTween(Int32, Int32, Int32, Boolean)`

- `Void PlayCanDrawTwinkLoopTween()`

- `Void PlayUseGoldNumDownTween()`

- `Void ResetToState(GOLD_DRAW_STATE)`

- `Void KillTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DrawCardTween : IHotfixable
{
	private UIBattleLegionWidgetsPanel m_closure; // 0x10
	private TweenWrapper m_tween; // 0x18
	private const Single GOLD_PER_NUM_GLOWING_DUR; // 0x0
	private const Single GOLD_NUM_LIMIT_MAX_GLOWING_DUR; // 0x0
	private const Single GOLD_TEXT_GLOWING_START_SIZE; // 0x0
	private const Single GOLD_TEXT_UP_DUR; // 0x0
	private const Single CAN_DRAW_BG_BLINK_ALPHA; // 0x0
	private const Single CAN_DRAW_BG_BLINK_DUR; // 0x0
	private const Single CAN_DRAW_BG_BLINK_END; // 0x0
	private const Single CAN_DRAW_FADE_OUT_DUR; // 0x0
	private const Single GOLD_TEXT_DOWN_START; // 0x0
	private const Single GOLD_TEXT_DOWN_DUR; // 0x0
	private static readonly Vector2 GOLD_TEXT_GLOWING_START_POS; // 0x0
	private static readonly Vector2 GOLD_TEXT_GLOWING_END_POS; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_PlayGoldGlowTween; // 0x18
	private static DelegateBridge __Hotfix0_PlayCanDrawTwinkLoopTween; // 0x20
	private static DelegateBridge __Hotfix0_PlayUseGoldNumDownTween; // 0x28
	private static DelegateBridge __Hotfix0_ResetToState; // 0x30
	private static DelegateBridge __Hotfix0_KillTween; // 0x38


	// RVA: 0x1dbad08 VA: 0x75943d2d08
	public Void .ctor(UIBattleLegionWidgetsPanel closure) { }
	// RVA: 0x1dbb5dc VA: 0x75943d35dc
	public Void PlayGoldGlowTween(Int32 curNum, Int32 targetNum, Int32 drawNeedGoldPrice, Boolean isCardFull) { }
	// RVA: 0x1dbbbbc VA: 0x75943d3bbc
	public Void PlayCanDrawTwinkLoopTween() { }
	// RVA: 0x1dba378 VA: 0x75943d2378
	public Void PlayUseGoldNumDownTween() { }
	// RVA: 0x1db9748 VA: 0x75943d1748
	public Void ResetToState(GOLD_DRAW_STATE state) { }
	// RVA: 0x1dbc1b4 VA: 0x75943d41b4
	public Void KillTween() { }
	// RVA: 0x1dbc240 VA: 0x75943d4240
	private static Void .cctor() { }
}
```