# RoguelikeCommonOuterBuffBottomDifficultyView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Image _difficultDeco`

- `Text _difficultName`

- `GameObject _panelEffect`

- `GameObject _panelNoEffect`

- `GameObject _panelActive`

- `GameObject _panelInactive`

- `Text _enableDesc`

- `SimpleLayoutContent _difficultContent`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `ContentAdapter m_adapter`


## Methods

- `Void Render(RoguelikeCommonOuterBuffDifficultyNodeViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffBottomDifficultyView : MonoBehaviour, IHotfixable
{
	private Image _difficultDeco; // 0x18
	private Text _difficultName; // 0x20
	private GameObject _panelEffect; // 0x28
	private GameObject _panelNoEffect; // 0x30
	private GameObject _panelActive; // 0x38
	private GameObject _panelInactive; // 0x40
	private Text _enableDesc; // 0x48
	private SimpleLayoutContent _difficultContent; // 0x50
	private Boolean m_isInited; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private ContentAdapter m_adapter; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x265c4c8 VA: 0x7594c744c8
	public Void Render(RoguelikeCommonOuterBuffDifficultyNodeViewModel viewModel) { }
	// RVA: 0x265c76c VA: 0x7594c7476c
	private Void _InitIfNot() { }
	// RVA: 0x265cb30 VA: 0x7594c74b30
	public Void .ctor() { }
}
```