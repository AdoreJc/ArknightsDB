# Act42D0EffectSelectItemView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `UIAtlasImage _bg`

- `Text _cost`

- `Text _name`

- `Image _icon`

- `UIAnimationLocation _lightAnim`

- `GameObject _light`

- `CanvasGroup _lightCanvasGroup`

- `Color _selectBgColor`

- `Color _unselectBgColor`

- `Color _selectColor`

- `Color _unselectColor`

- `GameObject _panelNull`

- `GameObject _panelView`

- `Boolean m_isInited`

- `SelectSwithTween m_switchTween`

- `Act42D0EffectItemViewModel m_cachedViewModel`

- `UIPageFinder m_pageFinder`

- `Int32 m_cachedSequenceNum`


## Methods

- `Void Render(Act42D0EffectItemViewModel, Int32)`

- `Void _InitIfNot()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EffectSelectItemView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _bg; // 0x18
	private Text _cost; // 0x20
	private Text _name; // 0x28
	private Image _icon; // 0x30
	private UIAnimationLocation _lightAnim; // 0x38
	private GameObject _light; // 0x48
	private CanvasGroup _lightCanvasGroup; // 0x50
	private Color _selectBgColor; // 0x58
	private Color _unselectBgColor; // 0x68
	private Color _selectColor; // 0x78
	private Color _unselectColor; // 0x88
	private GameObject _panelNull; // 0x98
	private GameObject _panelView; // 0xa0
	private Boolean m_isInited; // 0xa8
	private SelectSwithTween m_switchTween; // 0xb0
	private Act42D0EffectItemViewModel m_cachedViewModel; // 0xb8
	private UIPageFinder m_pageFinder; // 0xc0
	private Int32 m_cachedSequenceNum; // 0xd0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x320f210 VA: 0x7595827210
	public Void Render(Act42D0EffectItemViewModel viewModel, Int32 sequenceNum) { }
	// RVA: 0x320f40c VA: 0x759582740c
	private Void _InitIfNot() { }
	// RVA: 0x320f578 VA: 0x7595827578
	public Void OnClick() { }
	// RVA: 0x320f694 VA: 0x7595827694
	public Void .ctor() { }
}
```