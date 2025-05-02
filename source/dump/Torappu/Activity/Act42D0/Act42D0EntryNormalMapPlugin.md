# Act42D0EntryNormalMapPlugin

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Text _textAreaCode`

- `Text _textStageCode`

- `Image _imgRating`

- `GameObject _objAllClear`

- `GameObject _objHasProgress`

- `GameObject _objNoProgress`

- `GameObject _objClosed`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void OnNormalMapClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EntryNormalMapPlugin : TemplateActivityCommonPlugin
{
	private Text _textAreaCode; // 0x28
	private Text _textStageCode; // 0x30
	private Image _imgRating; // 0x38
	private GameObject _objAllClear; // 0x40
	private GameObject _objHasProgress; // 0x48
	private GameObject _objNoProgress; // 0x50
	private GameObject _objClosed; // 0x58
	private Boolean m_isInited; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_OnNormalMapClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3216eec VA: 0x759582eeec
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3217120 VA: 0x759582f120
	public Void OnNormalMapClick() { }
	// RVA: 0x32172a4 VA: 0x759582f2a4
	public Void .ctor() { }
}
```