# Rl03OuterBuffSummaryRawTextGroupView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Image _icon`

- `GameObject _back`

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `RawTextAdapter m_adapter`


## Methods

- `Void Render(String, Rl03OuterBuffSummaryRawTextGroupItemModel, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffSummaryRawTextGroupView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private GameObject _back; // 0x20
	private GameObject[] _iconLevelGroup; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private Boolean m_isInited; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	private RawTextAdapter m_adapter; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26add88 VA: 0x7594cc5d88
	public Void Render(String topicId, Rl03OuterBuffSummaryRawTextGroupItemModel viewModel, Boolean hasBack) { }
	// RVA: 0x26adf78 VA: 0x7594cc5f78
	private Void _InitIfNot() { }
	// RVA: 0x26ae1f8 VA: 0x7594cc61f8
	public Void .ctor() { }
}
```