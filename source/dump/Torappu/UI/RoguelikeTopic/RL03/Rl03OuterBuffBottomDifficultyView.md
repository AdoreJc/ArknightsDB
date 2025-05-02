# Rl03OuterBuffBottomDifficultyView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `UIAtlasImage _difficultDeco`

- `Text _difficultName`

- `GameObject _panelEffect`

- `GameObject _panelNoEffect`

- `GameObject _panelActive`

- `GameObject _panelInactive`

- `Text _effectTip`

- `SimpleLayoutContent _difficultContent`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `ContentAdapter m_adapter`


## Methods

- `Void Render(Rl03OuterBuffDifficultyNodeViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffBottomDifficultyView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _difficultDeco; // 0x18
	private Text _difficultName; // 0x20
	private GameObject _panelEffect; // 0x28
	private GameObject _panelNoEffect; // 0x30
	private GameObject _panelActive; // 0x38
	private GameObject _panelInactive; // 0x40
	private Text _effectTip; // 0x48
	private SimpleLayoutContent _difficultContent; // 0x50
	private Boolean m_isInited; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private ContentAdapter m_adapter; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26a64c8 VA: 0x7594cbe4c8
	public Void Render(Rl03OuterBuffDifficultyNodeViewModel viewModel) { }
	// RVA: 0x26a672c VA: 0x7594cbe72c
	private Void _InitIfNot() { }
	// RVA: 0x26a6ab8 VA: 0x7594cbeab8
	public Void .ctor() { }
}
```