# TrainingCampStageListItemView

**Namespace:** `Torappu.UI.TrainingCamp`


## Fields

- `DynContent _availContent`

- `DynContent _selectContent`

- `DynContent _doneContent`

- `GameObject _doneObj`

- `GameObject _trackPointObj`

- `GameObject _stageViewContainer`

- `GameObject _tipsViewContainer`

- `Text _tipsText`

- `Boolean m_isInited`

- `TrainingCampStageListItemViewModel m_cachedViewModel`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `ILoadAsset m_assetLoader`

- `Sprite m_cachedIcon`


## Methods

- `Void Render(TrainingCampStageListItemViewModel)`

- `Void EventOnClick()`

- `Void _InitIfNot()`

- `Void _SetDynContent(DynContent)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TrainingCamp
public class TrainingCampStageListItemView : MonoBehaviour, IHotfixable
{
	private DynContent _availContent; // 0x18
	private DynContent _selectContent; // 0x20
	private DynContent _doneContent; // 0x28
	private GameObject _doneObj; // 0x30
	private GameObject _trackPointObj; // 0x38
	private GameObject _stageViewContainer; // 0x40
	private GameObject _tipsViewContainer; // 0x48
	private Text _tipsText; // 0x50
	private Boolean m_isInited; // 0x58
	private TrainingCampStageListItemViewModel m_cachedViewModel; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private UIStateFinder m_stateFinder; // 0x78
	private ILoadAsset m_assetLoader; // 0x88
	private Sprite m_cachedIcon; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__SetDynContent; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2349ac0 VA: 0x7594961ac0
	public Void Render(TrainingCampStageListItemViewModel viewModel) { }
	// RVA: 0x234a15c VA: 0x759496215c
	public Void EventOnClick() { }
	// RVA: 0x2349dfc VA: 0x7594961dfc
	private Void _InitIfNot() { }
	// RVA: 0x234a0a0 VA: 0x75949620a0
	private Void _SetDynContent(DynContent comp) { }
	// RVA: 0x234a32c VA: 0x759496232c
	public Void .ctor() { }
}
```