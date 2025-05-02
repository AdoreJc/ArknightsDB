# TuningHandbookGroupItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `GameObject _objNormalItem`

- `GameObject _objLockItem`

- `GameObject _objSelectItem`

- `Text _txtNameNormal`

- `Text _txtNameSelect`

- `Image _imgEmotion`

- `UICommonTrackPoint _trackPoint`

- `UIPageFinder m_pageFinder`

- `TuningHandbookGroupViewModel m_viewModel`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `TrackPointViewProperty m_trackPointProperty`


## Methods

- `Void _InitIfNot()`

- `Void Render(TuningHandbookGroupViewModel)`

- `Void EventOnEmotionClick()`

- `Void EventOnLockEmotionClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHandbookGroupItemView : MonoBehaviour, IHotfixable
{
	private GameObject _objNormalItem; // 0x18
	private GameObject _objLockItem; // 0x20
	private GameObject _objSelectItem; // 0x28
	private Text _txtNameNormal; // 0x30
	private Text _txtNameSelect; // 0x38
	private Image _imgEmotion; // 0x40
	private UICommonTrackPoint _trackPoint; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private TuningHandbookGroupViewModel m_viewModel; // 0x60
	private Boolean m_isInited; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private TrackPointViewProperty m_trackPointProperty; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_EventOnEmotionClick; // 0x10
	private static DelegateBridge __Hotfix0_EventOnLockEmotionClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x232215c VA: 0x759493a15c
	private Void _InitIfNot() { }
	// RVA: 0x23222c8 VA: 0x759493a2c8
	public Void Render(TuningHandbookGroupViewModel viewModel) { }
	// RVA: 0x23224c4 VA: 0x759493a4c4
	public Void EventOnEmotionClick() { }
	// RVA: 0x23225bc VA: 0x759493a5bc
	public Void EventOnLockEmotionClick() { }
	// RVA: 0x23226b4 VA: 0x759493a6b4
	public Void .ctor() { }
}
```