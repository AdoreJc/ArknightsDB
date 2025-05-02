# IntermissionPanelRestShowTween

**Namespace:** ` `


## Fields

- `UIBattleLegionIntermissionTipsPanel m_closure`

- `TweenWrapper m_tween`


## Methods

- `Void PlayTween()`

- `Void ResetToState(Boolean)`

- `Void <PlayTween>b__15_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class IntermissionPanelRestShowTween : IHotfixable
{
	private UIBattleLegionIntermissionTipsPanel m_closure; // 0x10
	private TweenWrapper m_tween; // 0x18
	private const Single REST_SLIDER_START_TIME; // 0x0
	private const Single REST_SLIDER_SHOW_DUR; // 0x0
	private const Single REST_TIPS_START_TIME; // 0x0
	private const Single REST_TIPS_SHOW_DUR; // 0x0
	private const Single REST_LINE_START_FADE_TIME; // 0x0
	private const Single REST_LINE_FADE_DUR; // 0x0
	private const Single REST_LINE_MOVE_DUR; // 0x0
	private const Single REST_TIPS_START_FADE_TIME; // 0x0
	private const Single REST_TIPS_FADE_DUR; // 0x0
	private const Single REST_SLIDER_VALUE_START_DELAY; // 0x0
	private static readonly Vector2 REST_TIPS_LINE_START_POS; // 0x0
	private static readonly Vector2 REST_TIPS_LINE_END_POS; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_PlayTween; // 0x18
	private static DelegateBridge __Hotfix0_ResetToState; // 0x20


	// RVA: 0x1db7b74 VA: 0x75943cfb74
	public Void .ctor(UIBattleLegionIntermissionTipsPanel closure) { }
	// RVA: 0x1db7d88 VA: 0x75943cfd88
	public Void PlayTween() { }
	// RVA: 0x1db7c18 VA: 0x75943cfc18
	public Void ResetToState(Boolean isShow) { }
	// RVA: 0x1db82d8 VA: 0x75943d02d8
	private static Void .cctor() { }
	// RVA: 0x1db8334 VA: 0x75943d0334
	private Void <PlayTween>b__15_1(Single val) { }
}
```