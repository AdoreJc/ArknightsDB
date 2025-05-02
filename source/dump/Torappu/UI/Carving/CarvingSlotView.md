# CarvingSlotView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `UIAnimationLocation _animEnter`

- `CanvasGroup _canvasHighlight`

- `GameObject _pnlLocked`

- `CanvasGroup _raycastHandler`

- `RectTransform _dragBoundRect`

- `CanvasGroup _canvasHovering`

- `UIAtlasImage _emptyBg`

- `Int32 m_cachedIdx`

- `Boolean m_cachedHandCardSelected`

- `UISwitchTween m_highlightTween`

- `Boolean m_inited`

- `UIPageFinder m_pageFinder`

- `UISwitchTween m_hoveringTween`


## Properties

- `RectTransform dragBoundRect`


## Methods

- `RectTransform get_dragBoundRect()`

- `Void _InitIfNot()`

- `Tween GenerateShowAnim()`

- `Void Render(CarvingMainViewModel, Int32)`

- `Void OnSlotClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingSlotView : MonoBehaviour, IHotfixable
{
	private const Single LOCK_ALPHA; // 0x0
	private const Single UNLOCK_ALPHA; // 0x0
	private UIAnimationLocation _animEnter; // 0x18
	private CanvasGroup _canvasHighlight; // 0x28
	private GameObject _pnlLocked; // 0x30
	private CanvasGroup _raycastHandler; // 0x38
	private RectTransform _dragBoundRect; // 0x40
	private CanvasGroup _canvasHovering; // 0x48
	private UIAtlasImage _emptyBg; // 0x50
	private Int32 m_cachedIdx; // 0x58
	private Boolean m_cachedHandCardSelected; // 0x5c
	private UISwitchTween m_highlightTween; // 0x60
	private Boolean m_inited; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private UISwitchTween m_hoveringTween; // 0x80
	private static DelegateBridge __Hotfix0_get_dragBoundRect; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_GenerateShowAnim; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_OnSlotClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public RectTransform dragBoundRect { get; }

	// RVA: 0x2d9c564 VA: 0x75953b4564
	public RectTransform get_dragBoundRect() { }
	// RVA: 0x2d9f3d8 VA: 0x75953b73d8
	private Void _InitIfNot() { }
	// RVA: 0x2d9b044 VA: 0x75953b3044
	public Tween GenerateShowAnim() { }
	// RVA: 0x2d9c784 VA: 0x75953b4784
	public Void Render(CarvingMainViewModel model, Int32 idx) { }
	// RVA: 0x2d9f530 VA: 0x75953b7530
	public Void OnSlotClicked() { }
	// RVA: 0x2d9f5f4 VA: 0x75953b75f4
	public Void .ctor() { }
}
```