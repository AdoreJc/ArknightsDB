# Rl03OuterBuffSummaryDifficultyGroupView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Image _icon`

- `UIAtlasImage _deco`

- `Text _title`

- `Text _effectDesc`

- `GameObject _panelEffect`

- `CanvasGroup _canvasGroup`

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `RawTextAdapter m_adapter`


## Methods

- `Void Render(String, Rl03OuterBuffSummaryDifficultyItemModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffSummaryDifficultyGroupView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private UIAtlasImage _deco; // 0x20
	private Text _title; // 0x28
	private Text _effectDesc; // 0x30
	private GameObject _panelEffect; // 0x38
	private CanvasGroup _canvasGroup; // 0x40
	private SimpleLayoutContent _content; // 0x48
	private Boolean m_isInited; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private RawTextAdapter m_adapter; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26ac544 VA: 0x7594cc4544
	public Void Render(String topicId, Rl03OuterBuffSummaryDifficultyItemModel viewModel) { }
	// RVA: 0x26ac7bc VA: 0x7594cc47bc
	private Void _InitIfNot() { }
	// RVA: 0x26acae8 VA: 0x7594cc4ae8
	public Void .ctor() { }
}
```