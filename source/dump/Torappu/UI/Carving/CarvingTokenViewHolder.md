# CarvingTokenViewHolder

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMainCardView _prefabCard`

- `RectTransform _cardContainer`

- `CanvasGroup _alphaHandler`

- `Single _tweenDuration`

- `Single _hideMoveDuration`

- `Ease _tweenEase`

- `Single _scaleHide`

- `RectTransform _dragBoundRect`

- `Boolean m_inited`

- `CarvingMainCardView m_cardView`

- `Tween m_tween`

- `UIPageFinder m_pageFinder`

- `CarvingMainCardViewModel m_cachedCardViewModel`


## Properties

- `RectTransform dragBoundRect`


## Methods

- `RectTransform get_dragBoundRect()`

- `Void _InitIfNot()`

- `Void _ClearTween()`

- `Void OnShow(Single)`

- `Void OnHide()`

- `Void OnHideToSlot(String, Vector2)`

- `Void Render(CarvingMainCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingTokenViewHolder : MonoBehaviour, IHotfixable
{
	private CarvingMainCardView _prefabCard; // 0x18
	private RectTransform _cardContainer; // 0x20
	private CanvasGroup _alphaHandler; // 0x28
	private Single _tweenDuration; // 0x30
	private Single _hideMoveDuration; // 0x34
	private Ease _tweenEase; // 0x38
	private Single _scaleHide; // 0x3c
	private RectTransform _dragBoundRect; // 0x40
	private Boolean m_inited; // 0x48
	private CarvingMainCardView m_cardView; // 0x50
	private Tween m_tween; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private CarvingMainCardViewModel m_cachedCardViewModel; // 0x70
	private static DelegateBridge __Hotfix0_get_dragBoundRect; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__ClearTween; // 0x10
	private static DelegateBridge __Hotfix0_OnShow; // 0x18
	private static DelegateBridge __Hotfix0_OnHide; // 0x20
	private static DelegateBridge __Hotfix0_OnHideToSlot; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public RectTransform dragBoundRect { get; }

	// RVA: 0x2d9f664 VA: 0x75953b7664
	public RectTransform get_dragBoundRect() { }
	// RVA: 0x2d9f6cc VA: 0x75953b76cc
	private Void _InitIfNot() { }
	// RVA: 0x2d9f7b4 VA: 0x75953b77b4
	private Void _ClearTween() { }
	// RVA: 0x2d9f844 VA: 0x75953b7844
	public Void OnShow(Single startScale) { }
	// RVA: 0x2d9fac4 VA: 0x75953b7ac4
	public Void OnHide() { }
	// RVA: 0x2d9fdac VA: 0x75953b7dac
	public Void OnHideToSlot(String cardId, Vector2 targetPos) { }
	// RVA: 0x2da011c VA: 0x75953b811c
	public Void Render(CarvingMainCardViewModel viewModel) { }
	// RVA: 0x2da01e4 VA: 0x75953b81e4
	public Void .ctor() { }
}
```