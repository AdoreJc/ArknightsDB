# TuningProductSlotImageItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Image _slotImage`

- `Single _imgShowAlpha`

- `Single _imgHideAlpha`

- `Single _imgTweenDuration`

- `Sequence m_sequence`

- `String m_cachedImageName`

- `Boolean m_cachedIsShow`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(String)`

- `Void _SetIfShow(Boolean, Boolean)`

- `Void _LoadSprite()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductSlotImageItemView : MonoBehaviour, IHotfixable
{
	private Image _slotImage; // 0x18
	private Single _imgShowAlpha; // 0x20
	private Single _imgHideAlpha; // 0x24
	private Single _imgTweenDuration; // 0x28
	private Sequence m_sequence; // 0x30
	private String m_cachedImageName; // 0x38
	private Boolean m_cachedIsShow; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__SetIfShow; // 0x8
	private static DelegateBridge __Hotfix0__LoadSprite; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2335a5c VA: 0x759494da5c
	public Void Render(String imageName) { }
	// RVA: 0x2337854 VA: 0x759494f854
	private Void _SetIfShow(Boolean isShow, Boolean isChangeSprite) { }
	// RVA: 0x2337a3c VA: 0x759494fa3c
	private Void _LoadSprite() { }
	// RVA: 0x2337b14 VA: 0x759494fb14
	public Void .ctor() { }
}
```