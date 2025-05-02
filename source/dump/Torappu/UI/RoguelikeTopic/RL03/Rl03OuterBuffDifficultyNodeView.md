# Rl03OuterBuffDifficultyNodeView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Image _icon`

- `UIAnimationLocation _selectAnim`

- `UIAnimationLocation _activeAnim`

- `Single _animDelay`

- `Boolean m_isInited`

- `String m_buffId`

- `Boolean m_isActive`

- `Tween m_tween`

- `UIPageFinder m_pageFinder`

- `AnimationSwitchTween m_selectSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void _PlayActiveAnim(Rl03OuterBuffDifficultyNodeViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffDifficultyNodeView : Rl03OuterBuffNodeBaseView`1, IHotfixable
{
	private Image _icon; // 0x38
	private UIAnimationLocation _selectAnim; // 0x40
	private UIAnimationLocation _activeAnim; // 0x50
	private Single _animDelay; // 0x60
	private Boolean m_isInited; // 0x64
	private String m_buffId; // 0x68
	private Boolean m_isActive; // 0x70
	private Tween m_tween; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private AnimationSwitchTween m_selectSwitchTween; // 0x90
	private static DelegateBridge __Hotfix0_GetType; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlayActiveAnim; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x26aa804 VA: 0x7594cc2804
	public override Rl03OuterBuffViewType GetType() { }
	// RVA: 0x26aa86c VA: 0x7594cc286c
	public override Void Init(Rl03OuterBuffDifficultyNodeViewModel model) { }
	// RVA: 0x26aac10 VA: 0x7594cc2c10
	public override Void Render(String selectedBuffId, Rl03OuterBuffDifficultyNodeViewModel model) { }
	// RVA: 0x26aaad4 VA: 0x7594cc2ad4
	private Void _InitIfNot() { }
	// RVA: 0x26aadc4 VA: 0x7594cc2dc4
	private Void _PlayActiveAnim(Rl03OuterBuffDifficultyNodeViewModel model) { }
	// RVA: 0x26aaf5c VA: 0x7594cc2f5c
	public Void OnClick() { }
	// RVA: 0x26aafe4 VA: 0x7594cc2fe4
	public Void .ctor() { }
}
```