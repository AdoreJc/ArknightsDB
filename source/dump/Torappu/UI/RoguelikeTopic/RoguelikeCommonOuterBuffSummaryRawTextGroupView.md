# RoguelikeCommonOuterBuffSummaryRawTextGroupView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Image _icon`

- `GameObject _back`

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `RawTextAdapter m_adapter`


## Methods

- `Void Render(String, RoguelikeCommonOuterBuffSummaryRawTextGroupItemModel, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffSummaryRawTextGroupView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private GameObject _back; // 0x20
	private SimpleLayoutContent _content; // 0x28
	private Boolean m_isInited; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private RawTextAdapter m_adapter; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26649f0 VA: 0x7594c7c9f0
	public Void Render(String topicId, RoguelikeCommonOuterBuffSummaryRawTextGroupItemModel viewModel, Boolean hasBack) { }
	// RVA: 0x2664b4c VA: 0x7594c7cb4c
	private Void _InitIfNot() { }
	// RVA: 0x2664dcc VA: 0x7594c7cdcc
	public Void .ctor() { }
}
```