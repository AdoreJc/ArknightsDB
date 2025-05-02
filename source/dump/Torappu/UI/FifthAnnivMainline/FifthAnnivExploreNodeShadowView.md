# FifthAnnivExploreNodeShadowView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Graphic _graphicNode`

- `CanvasGroup _canvasGroup`

- `Single _durationFadein`

- `Single _delayFirstNodeShow`

- `Single _delayShow`

- `UIPageFinder m_pageFinder`

- `Vector2 m_cachedPos`


## Methods

- `Void Render(FifthAnnivExploreMapNodeViewModel)`

- `Void _PlayShowAnim(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreNodeShadowView : MonoBehaviour, IHotfixable
{
	private Graphic _graphicNode; // 0x18
	private CanvasGroup _canvasGroup; // 0x20
	private Single _durationFadein; // 0x28
	private Single _delayFirstNodeShow; // 0x2c
	private Single _delayShow; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private Vector2 m_cachedPos; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__PlayShowAnim; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29227f8 VA: 0x7594f3a7f8
	public Void Render(FifthAnnivExploreMapNodeViewModel nodeViewModel) { }
	// RVA: 0x2926180 VA: 0x7594f3e180
	private Void _PlayShowAnim(Single delay) { }
	// RVA: 0x2926260 VA: 0x7594f3e260
	public Void .ctor() { }
}
```