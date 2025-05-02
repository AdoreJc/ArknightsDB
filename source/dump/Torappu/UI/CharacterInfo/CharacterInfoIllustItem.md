# CharacterInfoIllustItem

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `RectTransform _container`

- `CharacterInfoIllustWrapper _illustWrapper`

- `CanvasGroup _alphaGroup`

- `CharacterInfoIllustWrapper m_illustWrapper`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void Render(CharViewModel, Boolean)`

- `Void SetPos(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoIllustItem : MonoBehaviour, IHotfixable
{
	private RectTransform _container; // 0x18
	private CharacterInfoIllustWrapper _illustWrapper; // 0x20
	private CanvasGroup _alphaGroup; // 0x28
	private const Single LENGTH_ILLUST; // 0x0
	private CharacterInfoIllustWrapper m_illustWrapper; // 0x30
	private Boolean m_isInited; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_SetPos; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d72430 VA: 0x759538a430
	private Void _InitIfNot() { }
	// RVA: 0x2d71e5c VA: 0x7595389e5c
	public Void Render(CharViewModel viewModel, Boolean isMiddle) { }
	// RVA: 0x2d71d9c VA: 0x7595389d9c
	public Void SetPos(Single pos) { }
	// RVA: 0x2d72518 VA: 0x759538a518
	public Void .ctor() { }
}
```