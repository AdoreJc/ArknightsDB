# Act1ArcadeStageScoreInfoDialog

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `RectTransform _bgRect`

- `CanvasGroup _canvasGroup`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `Boolean m_isBlockClick`


## Methods

- `Void _InitIfNot()`

- `Void EventOnCloseClicked()`

- `IEnumerator _OnShowCoroutine()`

- `IEnumerator _OnHideCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStageScoreInfoDialog : UICompDialog`1
{
	private const Single FADE_DURATION; // 0x0
	private List`1 _itemViews; // 0x48
	private RectTransform _bgRect; // 0x50
	private CanvasGroup _canvasGroup; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private Boolean m_isInited; // 0x70
	private Boolean m_isBlockClick; // 0x71
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x8
	private static DelegateBridge __Hotfix0__OnShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__OnHideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_OnRender; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3413f44 VA: 0x7595a2bf44
	private Void _InitIfNot() { }
	// RVA: 0x3414054 VA: 0x7595a2c054
	public Void EventOnCloseClicked() { }
	// RVA: 0x341418c VA: 0x7595a2c18c
	private IEnumerator _OnShowCoroutine() { }
	// RVA: 0x34140e0 VA: 0x7595a2c0e0
	private IEnumerator _OnHideCoroutine() { }
	// RVA: 0x3414288 VA: 0x7595a2c288
	protected override Void OnRender(Input input) { }
	// RVA: 0x34145f4 VA: 0x7595a2c5f4
	public Void .ctor() { }
}
```