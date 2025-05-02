# FifthAnnivExploreGroupChoiceItemView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Text _groupNameText`

- `UIAtlasImage _groupIconImg`

- `UIAtlasObject _groupIconAtlasObject`

- `RectTransform _valueGroupViewContainer`

- `UIAnimationLocation _selectAnim`

- `Boolean m_isInited`

- `Int32 m_cachedPosition`

- `FifthAnnivExploreValueGroupView m_exploreValueGroupView`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `AnimationSwitchTween m_selectTween`


## Methods

- `Void _InitIfNot()`

- `Void Render(FifthAnnivExploreGroupChoiceItemViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreGroupChoiceItemView : MonoBehaviour, IHotfixable
{
	private Text _groupNameText; // 0x18
	private UIAtlasImage _groupIconImg; // 0x20
	private UIAtlasObject _groupIconAtlasObject; // 0x28
	private RectTransform _valueGroupViewContainer; // 0x30
	private UIAnimationLocation _selectAnim; // 0x38
	private Boolean m_isInited; // 0x48
	private Int32 m_cachedPosition; // 0x4c
	private FifthAnnivExploreValueGroupView m_exploreValueGroupView; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private UIPageFinder m_pageFinder; // 0x68
	private AnimationSwitchTween m_selectTween; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2919b5c VA: 0x7594f31b5c
	private Void _InitIfNot() { }
	// RVA: 0x2919cfc VA: 0x7594f31cfc
	public Void Render(FifthAnnivExploreGroupChoiceItemViewModel viewModel) { }
	// RVA: 0x291a100 VA: 0x7594f32100
	public Void OnClick() { }
	// RVA: 0x291a1f8 VA: 0x7594f321f8
	public Void .ctor() { }
}
```