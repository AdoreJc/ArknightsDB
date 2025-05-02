# EnemyDuelPrepareModeBannerPreviewCardView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `UIAnimationLocation _previewOutAnim`

- `Image _previewImg`

- `Boolean m_isInited`

- `String m_spriteId`

- `Int32 m_viewIdx`

- `UIPageFinder m_pageFinder`

- `AnimationSwitchTween m_notPreviewSwitchTween`


## Methods

- `Void set_onClick(Action`1)`

- `Void _InitIfNot()`

- `Void Render(Param)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareModeBannerPreviewCardView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _previewOutAnim; // 0x18
	private Image _previewImg; // 0x28
	private Boolean m_isInited; // 0x30
	private String m_spriteId; // 0x38
	private Int32 m_viewIdx; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private AnimationSwitchTween m_notPreviewSwitchTween; // 0x58
	private Action`1 <onClick>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_set_onClick; // 0x0
	private static DelegateBridge __Hotfix0_get_onClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onClick { get; set; }

	// RVA: 0x2992ea0 VA: 0x7594faaea0
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x2992f24 VA: 0x7594faaf24
	private Action`1 get_onClick() { }
	// RVA: 0x2992f8c VA: 0x7594faaf8c
	private Void _InitIfNot() { }
	// RVA: 0x299305c VA: 0x7594fab05c
	public Void Render(Param param) { }
	// RVA: 0x2993220 VA: 0x7594fab220
	public Void EventOnClick() { }
	// RVA: 0x29932c0 VA: 0x7594fab2c0
	public Void .ctor() { }
}
```