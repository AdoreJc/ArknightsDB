# Act42d0AreaButton

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `UIAtlasImage _areaCodeIcon`

- `UIAtlasObject _iconAtlas`

- `GameObject _selectMaskGo`

- `GameObject _lockPartGo`

- `GameObject _normalPartGo`

- `GameObject _lastProgress`

- `GameObject _isNew`

- `Image _imgRateIcon`

- `Text _lastStageName`

- `GameObject _btnGo`

- `UIAnimationLocation _progressAnim`

- `String m_areaId`

- `UIPageFinder m_pageFinder`

- `Tween m_progressTween`


## Properties

- `GameObject btnGo`


## Methods

- `GameObject get_btnGo()`

- `Void _PlayAnimIfNecessary(Boolean)`

- `Void RenderBtn(Act42d0AreaViewModel, Boolean, NewestProgress, Boolean)`

- `Void EventOnAreaClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42d0AreaButton : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _areaCodeIcon; // 0x18
	private UIAtlasObject _iconAtlas; // 0x20
	private GameObject _selectMaskGo; // 0x28
	private GameObject _lockPartGo; // 0x30
	private GameObject _normalPartGo; // 0x38
	private GameObject _lastProgress; // 0x40
	private GameObject _isNew; // 0x48
	private Image _imgRateIcon; // 0x50
	private Text _lastStageName; // 0x58
	private GameObject _btnGo; // 0x60
	private UIAnimationLocation _progressAnim; // 0x68
	private String m_areaId; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private Tween m_progressTween; // 0x90
	private static DelegateBridge __Hotfix0_get_btnGo; // 0x0
	private static DelegateBridge __Hotfix0__PlayAnimIfNecessary; // 0x8
	private static DelegateBridge __Hotfix0_RenderBtn; // 0x10
	private static DelegateBridge __Hotfix0_EventOnAreaClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public GameObject btnGo { get; }

	// RVA: 0x3217314 VA: 0x759582f314
	public GameObject get_btnGo() { }
	// RVA: 0x321737c VA: 0x759582f37c
	private Void _PlayAnimIfNecessary(Boolean showStatusChanged) { }
	// RVA: 0x32174a4 VA: 0x759582f4a4
	public Void RenderBtn(Act42d0AreaViewModel viewModel, Boolean isSelected, NewestProgress progressInfo, Boolean showStatusChanged) { }
	// RVA: 0x3217734 VA: 0x759582f734
	public Void EventOnAreaClick() { }
	// RVA: 0x3217818 VA: 0x759582f818
	public Void .ctor() { }
}
```