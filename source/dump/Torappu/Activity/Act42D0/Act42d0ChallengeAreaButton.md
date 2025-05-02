# Act42d0ChallengeAreaButton

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Text _areaCodeText`

- `Text _lockTime`

- `GameObject _lockPartGo`

- `GameObject _normalPartGo`

- `GameObject _finishPartGo`

- `GameObject _selectedPartGo`

- `GameObject _iconCompleteGo`

- `GameObject _isNew`

- `GameObject _lockIconGo`

- `UIAnimationLocation _selectAnim`

- `Color _colorCodeNormal`

- `Color _colorCodeLocked`

- `Color _colorCodeAllCompleted`

- `String m_stageId`

- `UIPageFinder m_pageFinder`

- `Tween m_tween`

- `Boolean m_cachedSelected`


## Methods

- `Void RenderBtn(Act42D0ChallengeStageViewModel, Boolean)`

- `Void _PlaySelectAnimIfNeed(Boolean)`

- `Void EventOnChallengeStageClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42d0ChallengeAreaButton : MonoBehaviour, IHotfixable
{
	private Text _areaCodeText; // 0x18
	private Text _lockTime; // 0x20
	private GameObject _lockPartGo; // 0x28
	private GameObject _normalPartGo; // 0x30
	private GameObject _finishPartGo; // 0x38
	private GameObject _selectedPartGo; // 0x40
	private GameObject _iconCompleteGo; // 0x48
	private GameObject _isNew; // 0x50
	private GameObject _lockIconGo; // 0x58
	private UIAnimationLocation _selectAnim; // 0x60
	private Color _colorCodeNormal; // 0x70
	private Color _colorCodeLocked; // 0x80
	private Color _colorCodeAllCompleted; // 0x90
	private String m_stageId; // 0xa0
	private UIPageFinder m_pageFinder; // 0xa8
	private Tween m_tween; // 0xb8
	private Boolean m_cachedSelected; // 0xc0
	private static DelegateBridge __Hotfix0_RenderBtn; // 0x0
	private static DelegateBridge __Hotfix0__PlaySelectAnimIfNeed; // 0x8
	private static DelegateBridge __Hotfix0_EventOnChallengeStageClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x321a15c VA: 0x759583215c
	public Void RenderBtn(Act42D0ChallengeStageViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x321a398 VA: 0x7595832398
	private Void _PlaySelectAnimIfNeed(Boolean isSelected) { }
	// RVA: 0x321a4d0 VA: 0x75958324d0
	public Void EventOnChallengeStageClick() { }
	// RVA: 0x321a5d8 VA: 0x75958325d8
	public Void .ctor() { }
}
```