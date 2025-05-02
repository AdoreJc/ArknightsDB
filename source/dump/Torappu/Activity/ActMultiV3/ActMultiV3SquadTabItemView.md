# ActMultiV3SquadTabItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `CanvasGroup _alphaHandler`

- `GameObject _selectPartGO`

- `GameObject _unselectPartGO`

- `GameObject _charLackHintGO`

- `Text _textName`

- `Color _colorNameSelect`

- `Color _colorNameUnselect`

- `Image _imgModeIcon`

- `GameObject _lockIconGO`

- `Single _alphaSquadLock`

- `Color _colorModeIconSelect`

- `Color _colorModeIconUnselect`

- `GameObject _trackPointGO`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `ActMultiV3SquadModel m_squadModel`


## Methods

- `Void Render(ActMultiV3SquadModel, Boolean)`

- `Void EventOnTabClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadTabItemView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _alphaHandler; // 0x18
	private GameObject _selectPartGO; // 0x20
	private GameObject _unselectPartGO; // 0x28
	private GameObject _charLackHintGO; // 0x30
	private Text _textName; // 0x38
	private Color _colorNameSelect; // 0x40
	private Color _colorNameUnselect; // 0x50
	private Image _imgModeIcon; // 0x60
	private GameObject _lockIconGO; // 0x68
	private Single _alphaSquadLock; // 0x70
	private Color _colorModeIconSelect; // 0x74
	private Color _colorModeIconUnselect; // 0x84
	private GameObject _trackPointGO; // 0x98
	private UIPageFinder m_pageFinder; // 0xa0
	private UIStateFinder m_stateFinder; // 0xb0
	private ActMultiV3SquadModel m_squadModel; // 0xc0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnTabClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x314569c VA: 0x759575d69c
	public Void Render(ActMultiV3SquadModel squadModel, Boolean isSelect) { }
	// RVA: 0x3145b44 VA: 0x759575db44
	public Void EventOnTabClick() { }
	// RVA: 0x3145c50 VA: 0x759575dc50
	public Void .ctor() { }
}
```