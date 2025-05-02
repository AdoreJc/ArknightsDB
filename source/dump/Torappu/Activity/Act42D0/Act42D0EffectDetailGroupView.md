# Act42D0EffectDetailGroupView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Act42D0EffectDetailItemView _itemViewPrefab`

- `Single _showHideDuration`

- `Single _moveDuration`

- `Rect _padding`

- `Single _spacing`

- `RectTransform _viewPort`

- `ScrollRect _scrollRect`

- `CanvasGroup _noInfoCanvasGroup`

- `CanvasGroup _detailCanvasGroup`

- `Boolean m_isInited`

- `Act42D0EffectViewModel m_cachedViewModel`

- `InnerLayouter m_layouter`

- `InnerAdapter m_adapter`

- `UIPageFinder m_pageFinder`

- `FadeSwitchTween m_noInfoFadeTween`

- `GroupFadeSwitchTween m_detailGroupFadeTween`

- `Int32 m_cachedSequenceNum`

- `Boolean m_cachedNeedReset`


## Methods

- `Void _InitIfNot()`

- `Void Render(Act42D0EffectViewModel)`

- `Void OnClearEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EffectDetailGroupView : UICustomAdapterLayout`2, IHotfixable
{
	private Act42D0EffectDetailItemView _itemViewPrefab; // 0x78
	private Single _showHideDuration; // 0x80
	private Single _moveDuration; // 0x84
	private Rect _padding; // 0x88
	private Single _spacing; // 0x98
	private RectTransform _viewPort; // 0xa0
	private ScrollRect _scrollRect; // 0xa8
	private CanvasGroup _noInfoCanvasGroup; // 0xb0
	private CanvasGroup _detailCanvasGroup; // 0xb8
	private Boolean m_isInited; // 0xc0
	private Act42D0EffectViewModel m_cachedViewModel; // 0xc8
	private InnerLayouter m_layouter; // 0xd0
	private InnerAdapter m_adapter; // 0xd8
	private UIPageFinder m_pageFinder; // 0xe0
	private FadeSwitchTween m_noInfoFadeTween; // 0xf0
	private GroupFadeSwitchTween m_detailGroupFadeTween; // 0xf8
	private Int32 m_cachedSequenceNum; // 0x100
	private Boolean m_cachedNeedReset; // 0x104
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClearEffect; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x320b7d4 VA: 0x75958237d4
	private Void _InitIfNot() { }
	// RVA: 0x320bb80 VA: 0x7595823b80
	public Void Render(Act42D0EffectViewModel viewModel) { }
	// RVA: 0x320bd20 VA: 0x7595823d20
	public Void OnClearEffect() { }
	// RVA: 0x320bde0 VA: 0x7595823de0
	public Void .ctor() { }
}
```