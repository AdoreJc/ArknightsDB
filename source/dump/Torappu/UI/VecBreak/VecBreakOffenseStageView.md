# VecBreakOffenseStageView

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `Image _imgStage`

- `Color _colorNotOpen`

- `GameObject _particleGo`

- `GameObject _notOpenPartGo`

- `GameObject _completeGo`

- `Text _textLockHint`

- `UIAnimationLocation _animOutLeft`

- `UIAnimationLocation _animOutRight`

- `UIAnimationLocation _animInLeft`

- `UIAnimationLocation _animInRight`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(VecBreakOffenseStageModel)`

- `Tween GetTweenByType(VecBreakOffenseTweenType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakOffenseStageView : MonoBehaviour, IHotfixable
{
	private Image _imgStage; // 0x18
	private Color _colorNotOpen; // 0x20
	private GameObject _particleGo; // 0x30
	private GameObject _notOpenPartGo; // 0x38
	private GameObject _completeGo; // 0x40
	private Text _textLockHint; // 0x48
	private UIAnimationLocation _animOutLeft; // 0x50
	private UIAnimationLocation _animOutRight; // 0x60
	private UIAnimationLocation _animInLeft; // 0x70
	private UIAnimationLocation _animInRight; // 0x80
	private UIPageFinder m_pageFinder; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_GetTweenByType; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22d3934 VA: 0x75948eb934
	public Void Render(VecBreakOffenseStageModel stageModel) { }
	// RVA: 0x22d37e8 VA: 0x75948eb7e8
	public Tween GetTweenByType(VecBreakOffenseTweenType fadeOutTweenType) { }
	// RVA: 0x22d6a10 VA: 0x75948eea10
	public Void .ctor() { }
}
```