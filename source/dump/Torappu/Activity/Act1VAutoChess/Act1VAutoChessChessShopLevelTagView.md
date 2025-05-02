# Act1VAutoChessChessShopLevelTagView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _imgDescDown`

- `Image _imgTag`

- `CanvasGroup _canvasCharDesc`

- `CanvasGroup _canvasItemDesc`

- `Int32 m_cachedLevel`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `FadeSwitchTween m_fadeSwitchTweenCharDesc`

- `FadeSwitchTween m_fadeSwitchTweenItemDesc`


## Methods

- `Void Render(Act1VAutoChessShopLevelTagViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopLevelTagView : MonoBehaviour, IHotfixable
{
	private Image _imgDescDown; // 0x18
	private Image _imgTag; // 0x20
	private CanvasGroup _canvasCharDesc; // 0x28
	private CanvasGroup _canvasItemDesc; // 0x30
	private Int32 m_cachedLevel; // 0x38
	private Boolean m_hasInited; // 0x3c
	private UIPageFinder m_pageFinder; // 0x40
	private FadeSwitchTween m_fadeSwitchTweenCharDesc; // 0x50
	private FadeSwitchTween m_fadeSwitchTweenItemDesc; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3313948 VA: 0x759592b948
	public Void Render(Act1VAutoChessShopLevelTagViewModel tagViewModel) { }
	// RVA: 0x3313b18 VA: 0x759592bb18
	private Void _InitIfNot() { }
	// RVA: 0x3313c70 VA: 0x759592bc70
	public Void .ctor() { }
}
```