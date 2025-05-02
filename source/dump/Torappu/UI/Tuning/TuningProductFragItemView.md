# TuningProductFragItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Text _fragNameText`

- `Text _fragNumText`

- `Text _fragSelectText`

- `Image _fragImage`

- `Color _emptyTextColor`

- `Color _nonEmptyTextColor`

- `Single _emptyFragImageAlpha`

- `Single _nonEmptyFragImageAlpha`

- `GameObject _emptyPanel`

- `GameObject _nonEmptyPanel`

- `CanvasGroup _selectNumGroup`

- `Single _showAlpha`

- `Single _hideAlpha`

- `Single _showDuration`

- `TuningFragModel m_cachedModel`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `Tween m_showTween`

- `Boolean m_cachedIsShow`


## Methods

- `Void Render(TuningFragModel)`

- `Void _SelectNumShow(Boolean)`

- `Void SelectFrag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductFragItemView : MonoBehaviour, IHotfixable
{
	private Text _fragNameText; // 0x18
	private Text _fragNumText; // 0x20
	private Text _fragSelectText; // 0x28
	private Image _fragImage; // 0x30
	private Color _emptyTextColor; // 0x38
	private Color _nonEmptyTextColor; // 0x48
	private Single _emptyFragImageAlpha; // 0x58
	private Single _nonEmptyFragImageAlpha; // 0x5c
	private GameObject _emptyPanel; // 0x60
	private GameObject _nonEmptyPanel; // 0x68
	private CanvasGroup _selectNumGroup; // 0x70
	private Single _showAlpha; // 0x78
	private Single _hideAlpha; // 0x7c
	private Single _showDuration; // 0x80
	private TuningFragModel m_cachedModel; // 0x88
	private UIStateFinder m_stateFinder; // 0x90
	private UIPageFinder m_pageFinder; // 0xa0
	private Tween m_showTween; // 0xb0
	private Boolean m_cachedIsShow; // 0xb8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__SelectNumShow; // 0x8
	private static DelegateBridge __Hotfix0_SelectFrag; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2334978 VA: 0x759494c978
	public Void Render(TuningFragModel model) { }
	// RVA: 0x2334c30 VA: 0x759494cc30
	private Void _SelectNumShow(Boolean isShow) { }
	// RVA: 0x2334d0c VA: 0x759494cd0c
	public Void SelectFrag() { }
	// RVA: 0x2334e00 VA: 0x759494ce00
	public Void .ctor() { }
}
```