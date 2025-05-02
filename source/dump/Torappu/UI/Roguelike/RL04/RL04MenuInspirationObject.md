# RL04MenuInspirationObject

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Image _iconImg`

- `CanvasGroup _canvasGroup`

- `FadeTranslationSwitchTween m_showSwitchTween`

- `UIPageFinder m_pageFinder`

- `String m_cachedInspirationItemId`


## Methods

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04MenuInspirationObject : RoguelikeMenuObject`1, IHotfixable
{
	private static readonly Vector2 HIDE_POS; // 0x0
	private static readonly Vector2 SHOW_POS; // 0x8
	private Image _iconImg; // 0x28
	private CanvasGroup _canvasGroup; // 0x30
	private FadeTranslationSwitchTween m_showSwitchTween; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	private String m_cachedInspirationItemId; // 0x50
	private static DelegateBridge __Hotfix0_get_menuType; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2b2d388 VA: 0x7595145388
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2b2d400 VA: 0x7595145400
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2b2d54c VA: 0x759514554c
	public override Void Render(RL04MenuInspirationViewModel viewModel) { }
	// RVA: 0x2b2d790 VA: 0x7595145790
	public Void .ctor() { }
	// RVA: 0x2b2d830 VA: 0x7595145830
	private static Void .cctor() { }
	// RVA: 0x2b2d88c VA: 0x759514588c
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
}
```