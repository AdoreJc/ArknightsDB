# ChaosView

**Namespace:** ` `


## Fields

- `GameObject _pnlChaos`

- `Image _imgChaosIcon`

- `UIAtlasImage _imgChaosLevel1`

- `UIAtlasImage _imgChaosLevel2`

- `Text _textChaosName`

- `Text _textChaosDesc`

- `Color _colorLight`

- `Color _colorDark`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(String, ChaosModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ChaosView : IHotfixable
{
	private GameObject _pnlChaos; // 0x10
	private Image _imgChaosIcon; // 0x18
	private UIAtlasImage _imgChaosLevel1; // 0x20
	private UIAtlasImage _imgChaosLevel2; // 0x28
	private Text _textChaosName; // 0x30
	private Text _textChaosDesc; // 0x38
	private Color _colorLight; // 0x40
	private Color _colorDark; // 0x50
	private UIPageFinder m_pageFinder; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bb69d4 VA: 0x75951ce9d4
	public Void Render(String topicId, ChaosModel chaosViewModel) { }
	// RVA: 0x2bb6be8 VA: 0x75951cebe8
	public Void .ctor() { }
}
```