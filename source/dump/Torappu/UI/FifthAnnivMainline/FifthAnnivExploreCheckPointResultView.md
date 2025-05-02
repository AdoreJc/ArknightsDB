# FifthAnnivExploreCheckPointResultView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `GameObject _stageNumObj`

- `Text _stageNumText`

- `Text _targetDescText`

- `UIAtlasImage _groupIconImg`

- `UIAtlasObject _groupIconAtlas`

- `Image _endingIconImg`

- `GameObject _groupInfoObj`

- `Text _groupNameText`

- `Text _groupCodeText`

- `GameObject _nextHotspotObj`

- `Text _unexpandTitleText`

- `Text _unexpandDescText`

- `Text _expandSubTitleText`

- `Text _expandTitleText`

- `Text _clickHintText`

- `GameObject _darkenBkg`

- `GameObject _failNoiseImg`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _nextAnim`

- `UIAnimationLocation _failAnim`

- `Boolean m_isInited`

- `Tween m_tween`

- `UIPageFinder m_pageFinder`

- `Action <onNextBtnClick>k__BackingField`


## Properties

- `Action onNextBtnClick`


## Methods

- `Void set_onNextBtnClick(Action)`

- `Action get_onNextBtnClick()`

- `Void Render(FifthAnnivExploreCheckPointResultViewModel)`

- `Void OnNextBtnClick()`

- `Void _ResetAnimations()`

- `Void _PlayTween(UIAnimationLocation)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreCheckPointResultView : MonoBehaviour, IHotfixable
{
	private GameObject _stageNumObj; // 0x18
	private Text _stageNumText; // 0x20
	private Text _targetDescText; // 0x28
	private UIAtlasImage _groupIconImg; // 0x30
	private UIAtlasObject _groupIconAtlas; // 0x38
	private Image _endingIconImg; // 0x40
	private GameObject _groupInfoObj; // 0x48
	private Text _groupNameText; // 0x50
	private Text _groupCodeText; // 0x58
	private GameObject _nextHotspotObj; // 0x60
	private Text _unexpandTitleText; // 0x68
	private Text _unexpandDescText; // 0x70
	private Text _expandSubTitleText; // 0x78
	private Text _expandTitleText; // 0x80
	private Text _clickHintText; // 0x88
	private GameObject _darkenBkg; // 0x90
	private GameObject _failNoiseImg; // 0x98
	private UIAnimationLocation _enterAnim; // 0xa0
	private UIAnimationLocation _nextAnim; // 0xb0
	private UIAnimationLocation _failAnim; // 0xc0
	private Boolean m_isInited; // 0xd0
	private Tween m_tween; // 0xd8
	private UIPageFinder m_pageFinder; // 0xe0
	private Action <onNextBtnClick>k__BackingField; // 0xf0
	private static DelegateBridge __Hotfix0_set_onNextBtnClick; // 0x0
	private static DelegateBridge __Hotfix0_get_onNextBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnNextBtnClick; // 0x18
	private static DelegateBridge __Hotfix0__ResetAnimations; // 0x20
	private static DelegateBridge __Hotfix0__PlayTween; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action onNextBtnClick { get; set; }

	// RVA: 0x290af34 VA: 0x7594f22f34
	public Void set_onNextBtnClick(Action value) { }
	// RVA: 0x290be5c VA: 0x7594f23e5c
	private Action get_onNextBtnClick() { }
	// RVA: 0x290b1cc VA: 0x7594f231cc
	public Void Render(FifthAnnivExploreCheckPointResultViewModel viewModel) { }
	// RVA: 0x290c050 VA: 0x7594f24050
	public Void OnNextBtnClick() { }
	// RVA: 0x290bec4 VA: 0x7594f23ec4
	private Void _ResetAnimations() { }
	// RVA: 0x290bf64 VA: 0x7594f23f64
	private Void _PlayTween(UIAnimationLocation animLocaltion) { }
	// RVA: 0x290c100 VA: 0x7594f24100
	public Void .ctor() { }
}
```