# BottleAnimator

**Namespace:** ` `


## Fields

- `UIAnimationLocation m_animationLocation`

- `CanvasGroup m_leftBottleGroup`

- `CanvasGroup m_rightNearBottleGroup`

- `CanvasGroup m_rightFarBottleGroup`

- `Single m_animationLength`

- `Int32 m_maxPosition`

- `Int32 m_cachedPosition`

- `Tweener m_playingTweener`

- `Single m_playingPosition`


## Properties

- `Int32 bottleLimit`


## Methods

- `Void set_bottleLimit(Int32)`

- `Void ResetPosition(Int32)`

- `Void UpdatePosition(Int32)`

- `Single _GetPosition()`

- `Void _SetPosition(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BottleAnimator : IHotfixable
{
	private UIAnimationLocation m_animationLocation; // 0x10
	private CanvasGroup m_leftBottleGroup; // 0x20
	private CanvasGroup m_rightNearBottleGroup; // 0x28
	private CanvasGroup m_rightFarBottleGroup; // 0x30
	private Single m_animationLength; // 0x38
	private Int32 m_maxPosition; // 0x3c
	private Int32 m_cachedPosition; // 0x40
	private Tweener m_playingTweener; // 0x48
	private Single m_playingPosition; // 0x50
	private static DelegateBridge __Hotfix0_set_bottleLimit; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ResetPosition; // 0x10
	private static DelegateBridge __Hotfix0_UpdatePosition; // 0x18
	private static DelegateBridge __Hotfix0__GetPosition; // 0x20
	private static DelegateBridge __Hotfix0__SetPosition; // 0x28

	public Int32 bottleLimit { set; }

	// RVA: 0x24c5eac VA: 0x7594addeac
	public Void set_bottleLimit(Int32 value) { }
	// RVA: 0x24c68c8 VA: 0x7594ade8c8
	public Void .ctor(UIAnimationLocation animationLocation, BottleCanvases bottleCanvases) { }
	// RVA: 0x24c5f50 VA: 0x7594addf50
	public Void ResetPosition(Int32 position) { }
	// RVA: 0x24c6230 VA: 0x7594ade230
	public Void UpdatePosition(Int32 position) { }
	// RVA: 0x24c7250 VA: 0x7594adf250
	private Single _GetPosition() { }
	// RVA: 0x24c72b8 VA: 0x7594adf2b8
	private Void _SetPosition(Single position) { }
}
```