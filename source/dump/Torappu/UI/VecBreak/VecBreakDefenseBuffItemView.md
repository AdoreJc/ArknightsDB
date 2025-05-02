# VecBreakDefenseBuffItemView

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `GameObject _lockPartGo`

- `GameObject _inactivePartGo`

- `GameObject _activePartGo`

- `Image _imgIcon`

- `Color _colorIconInactive`

- `Color _colorIconActive`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(VecBreakDefenseBuffModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefenseBuffItemView : MonoBehaviour, IHotfixable
{
	private GameObject _lockPartGo; // 0x18
	private GameObject _inactivePartGo; // 0x20
	private GameObject _activePartGo; // 0x28
	private Image _imgIcon; // 0x30
	private Color _colorIconInactive; // 0x38
	private Color _colorIconActive; // 0x48
	private UIPageFinder m_pageFinder; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x22ce270 VA: 0x75948e6270
	public Void Render(VecBreakDefenseBuffModel buffModel) { }
	// RVA: 0x22ce450 VA: 0x75948e6450
	public Void .ctor() { }
}
```