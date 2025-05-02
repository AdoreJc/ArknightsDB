# FifthAnnivExploreLineView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `UILineRenderer _lineRenderer`

- `CanvasGroup _canvasGroup`

- `Single _durationFadein`

- `Single _delayFadein`

- `UIPageFinder m_pageFinder`

- `Boolean m_isShown`


## Methods

- `Void Render(RenderParam)`

- `Void _PlayShowAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreLineView : MonoBehaviour, IHotfixable
{
	private UILineRenderer _lineRenderer; // 0x18
	private CanvasGroup _canvasGroup; // 0x20
	private Single _durationFadein; // 0x28
	private Single _delayFadein; // 0x2c
	private UIPageFinder m_pageFinder; // 0x30
	private Boolean m_isShown; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__PlayShowAnim; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29234d4 VA: 0x7594f3b4d4
	public Void Render(RenderParam renderParam) { }
	// RVA: 0x2924f20 VA: 0x7594f3cf20
	private Void _PlayShowAnim() { }
	// RVA: 0x2924fec VA: 0x7594f3cfec
	public Void .ctor() { }
}
```