# Rl03OuterBuffNormalNodeView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Image _icon`

- `UIAnimationLocation _selectAnim`

- `UIAnimationLocation _unlockLightAnim`

- `UIAnimationLocation _activeAnim`

- `UIAnimationLocation _activeLightAnim`

- `Single _activeAnimDelay`

- `Single _unlockAnimDelay`

- `Boolean m_isInited`

- `String m_buffId`

- `Boolean m_isUnlock`

- `Boolean m_isActive`

- `Tween m_nodeTween`

- `Tween m_lightTween`

- `UIPageFinder m_pageFinder`

- `AnimationSwitchTween m_selectSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void _InitNodeStatus(Rl03OuterBuffNormalNodeViewModel)`

- `Void _InitLightStatus(Rl03OuterBuffNormalNodeViewModel)`

- `Void _PlayActiveAnim(Rl03OuterBuffNormalNodeViewModel)`

- `Void _PlayUnlockAnim(Rl03OuterBuffNormalNodeViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffNormalNodeView : Rl03OuterBuffNodeBaseView`1, IHotfixable
{
	private Image _icon; // 0x38
	private UIAnimationLocation _selectAnim; // 0x40
	private UIAnimationLocation _unlockLightAnim; // 0x50
	private UIAnimationLocation _activeAnim; // 0x60
	private UIAnimationLocation _activeLightAnim; // 0x70
	private Single _activeAnimDelay; // 0x80
	private Single _unlockAnimDelay; // 0x84
	private Boolean m_isInited; // 0x88
	private String m_buffId; // 0x90
	private Boolean m_isUnlock; // 0x98
	private Boolean m_isActive; // 0x99
	private Tween m_nodeTween; // 0xa0
	private Tween m_lightTween; // 0xa8
	private UIPageFinder m_pageFinder; // 0xb0
	private AnimationSwitchTween m_selectSwitchTween; // 0xc0
	private static DelegateBridge __Hotfix0_GetType; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__InitNodeStatus; // 0x20
	private static DelegateBridge __Hotfix0__InitLightStatus; // 0x28
	private static DelegateBridge __Hotfix0__PlayActiveAnim; // 0x30
	private static DelegateBridge __Hotfix0__PlayUnlockAnim; // 0x38
	private static DelegateBridge __Hotfix0_OnClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x26aba08 VA: 0x7594cc3a08
	public override Rl03OuterBuffViewType GetType() { }
	// RVA: 0x26aba6c VA: 0x7594cc3a6c
	public override Void Init(Rl03OuterBuffNormalNodeViewModel model) { }
	// RVA: 0x26abf48 VA: 0x7594cc3f48
	public override Void Render(String selectedBuffId, Rl03OuterBuffNormalNodeViewModel model) { }
	// RVA: 0x26abbf4 VA: 0x7594cc3bf4
	private Void _InitIfNot() { }
	// RVA: 0x26abcc8 VA: 0x7594cc3cc8
	private Void _InitNodeStatus(Rl03OuterBuffNormalNodeViewModel model) { }
	// RVA: 0x26abde0 VA: 0x7594cc3de0
	private Void _InitLightStatus(Rl03OuterBuffNormalNodeViewModel model) { }
	// RVA: 0x26ac208 VA: 0x7594cc4208
	private Void _PlayActiveAnim(Rl03OuterBuffNormalNodeViewModel model) { }
	// RVA: 0x26ac070 VA: 0x7594cc4070
	private Void _PlayUnlockAnim(Rl03OuterBuffNormalNodeViewModel model) { }
	// RVA: 0x26ac42c VA: 0x7594cc442c
	public Void OnClick() { }
	// RVA: 0x26ac4b4 VA: 0x7594cc44b4
	public Void .ctor() { }
}
```