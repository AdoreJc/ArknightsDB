# HandCardFullTipsTween

**Namespace:** ` `


## Fields

- `UIBattleLegionWidgetsPanel m_closure`

- `TweenWrapper m_tween`

- `Action tweenEndCallBack`


## Methods

- `Void PlayTween(Boolean)`

- `Void ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class HandCardFullTipsTween : IHotfixable
{
	private UIBattleLegionWidgetsPanel m_closure; // 0x10
	private TweenWrapper m_tween; // 0x18
	private const Single CARD_FULL_TIPS_FADE_IN_START_TIME; // 0x0
	private const Single CARD_FULL_TIPS_FADE_DUR; // 0x0
	private const Single CARD_FULL_TIPS_SHAKE_START_TIME; // 0x0
	private const Single CARD_FULL_TIPS_SHAKE_PER_DUR; // 0x0
	private const Int32 CARD_FULL_TIPS_SHAKE_TIMES; // 0x0
	private const Single CARD_FULL_TIPS_EFFECT_START_TIME; // 0x0
	private const Single CARD_FULL_TIPS_FADE_OUT_START_TIME; // 0x0
	private static readonly Vector2 CARD_FULL_TIPS_SHAKE_START; // 0x0
	private static readonly Vector2 CARD_FULL_TIPS_SHAKE_END; // 0x8
	public Action tweenEndCallBack; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_PlayTween; // 0x18
	private static DelegateBridge __Hotfix0_ResetToState; // 0x20


	// RVA: 0x1dbadac VA: 0x75943d2dac
	public Void .ctor(UIBattleLegionWidgetsPanel closure) { }
	// RVA: 0x1dba7f4 VA: 0x75943d27f4
	public Void PlayTween(Boolean showBlastEffect) { }
	// RVA: 0x1db95f0 VA: 0x75943d15f0
	public Void ResetToState(Boolean isShow) { }
	// RVA: 0x1dbc5d8 VA: 0x75943d45d8
	private static Void .cctor() { }
}
```