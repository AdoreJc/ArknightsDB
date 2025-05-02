# Act38sideMapDecorFireworkCraftPlugin

**Namespace:** `Torappu.Activity.Act38side`


## Fields

- `GameObject _panelSelf`

- `Image _imgAnimIcon`

- `Image _imgAnimBkg`

- `GameObject _panelNew`

- `RectTransform _plateContainer`

- `UIColorGraphic _buttonTarget`

- `UIPageFinder m_pageFinder`

- `String m_cachedActId`

- `String m_cachedAnimalId`

- `Boolean m_hasInited`

- `FireworkPlateView m_plateView`

- `FireworkPlateViewStyle m_style`


## Methods

- `Void EventOnBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act38side
public class Act38sideMapDecorFireworkCraftPlugin : TemplateActivityCommonPlugin, IHotfixable
{
	private GameObject _panelSelf; // 0x28
	private Image _imgAnimIcon; // 0x30
	private Image _imgAnimBkg; // 0x38
	private GameObject _panelNew; // 0x40
	private RectTransform _plateContainer; // 0x48
	private UIColorGraphic _buttonTarget; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private String m_cachedActId; // 0x68
	private String m_cachedAnimalId; // 0x70
	private Boolean m_hasInited; // 0x78
	private FireworkPlateView m_plateView; // 0x80
	private FireworkPlateViewStyle m_style; // 0x88
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x323e298 VA: 0x7595856298
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x323e75c VA: 0x759585675c
	public Void EventOnBtnClicked() { }
	// RVA: 0x323e4ec VA: 0x75958564ec
	private Void _InitIfNot() { }
	// RVA: 0x323e88c VA: 0x759585688c
	public Void .ctor() { }
}
```