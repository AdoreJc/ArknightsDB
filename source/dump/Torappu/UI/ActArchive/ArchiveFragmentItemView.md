# ArchiveFragmentItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _panelLocked`

- `GameObject _panelUnattained`

- `GameObject _panelUnlock`

- `Image _imgIcon`

- `CanvasGroup _canvasGroupSelected`

- `GameObject _panelNew`

- `Boolean m_hasInited`

- `FadeSwitchTween m_fadeSwitchTween`

- `String m_cachedItemId`

- `UIPageFinder m_pageFinder`


## Methods

- `Void set_onItemClicked(Action`1)`

- `Void Render(FragmentItemModel, Boolean, String)`

- `Void EventOnItemClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveFragmentItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelLocked; // 0x18
	private GameObject _panelUnattained; // 0x20
	private GameObject _panelUnlock; // 0x28
	private Image _imgIcon; // 0x30
	private CanvasGroup _canvasGroupSelected; // 0x38
	private GameObject _panelNew; // 0x40
	private Action`1 <onItemClicked>k__BackingField; // 0x48
	private Boolean m_hasInited; // 0x50
	private FadeSwitchTween m_fadeSwitchTween; // 0x58
	private String m_cachedItemId; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnItemClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onItemClicked { get; set; }

	// RVA: 0x3054a4c VA: 0x759566ca4c
	private Action`1 get_onItemClicked() { }
	// RVA: 0x3054128 VA: 0x759566c128
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x30541ac VA: 0x759566c1ac
	public Void Render(FragmentItemModel viewModel, Boolean showFadeAnim, String selectedItemId) { }
	// RVA: 0x3054b9c VA: 0x759566cb9c
	public Void EventOnItemClicked() { }
	// RVA: 0x3054ab4 VA: 0x759566cab4
	private Void _InitIfNot() { }
	// RVA: 0x3054c3c VA: 0x759566cc3c
	public Void .ctor() { }
}
```