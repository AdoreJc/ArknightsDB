# RoguelikeCommonOuterBuffSummaryDifficultyGroupView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Image _icon`

- `Image _deco`

- `Text _title`

- `Text _enableDesc`

- `GameObject _panelEffect`

- `CanvasGroup _canvasGroup`

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `RawTextAdapter m_adapter`


## Methods

- `Void Render(String, RoguelikeCommonOuterBuffSummaryDifficultyItemModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffSummaryDifficultyGroupView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private Image _deco; // 0x20
	private Text _title; // 0x28
	private Text _enableDesc; // 0x30
	private GameObject _panelEffect; // 0x38
	private CanvasGroup _canvasGroup; // 0x40
	private SimpleLayoutContent _content; // 0x48
	private Boolean m_isInited; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private RawTextAdapter m_adapter; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26632e0 VA: 0x7594c7b2e0
	public Void Render(String topicId, RoguelikeCommonOuterBuffSummaryDifficultyItemModel viewModel) { }
	// RVA: 0x266352c VA: 0x7594c7b52c
	private Void _InitIfNot() { }
	// RVA: 0x2663750 VA: 0x7594c7b750
	public Void .ctor() { }
}
```