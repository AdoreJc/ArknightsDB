# TemplateActivityMissionArchivePlugin

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `GameObject _normalPanel`

- `GameObject _lockedPanel`

- `Text _unlockDescText`

- `GameObject _trackPointPrefab`

- `Transform _trackPointContainer`

- `UIPageFinder m_pageFinder`

- `Boolean m_hasInited`

- `GameObject m_trackPoint`

- `String m_cachedTopicId`


## Methods

- `Void OnClickEvent()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMissionArchivePlugin : TemplateActivityCommonPlugin
{
	private GameObject _normalPanel; // 0x28
	private GameObject _lockedPanel; // 0x30
	private Text _unlockDescText; // 0x38
	private GameObject _trackPointPrefab; // 0x40
	private Transform _trackPointContainer; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private Boolean m_hasInited; // 0x60
	private GameObject m_trackPoint; // 0x68
	private String m_cachedTopicId; // 0x70
	private static DelegateBridge __Hotfix0_OnClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3097184 VA: 0x75956af184
	public Void OnClickEvent() { }
	// RVA: 0x3097280 VA: 0x75956af280
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x309743c VA: 0x75956af43c
	private Void _InitIfNot() { }
	// RVA: 0x3097524 VA: 0x75956af524
	public Void .ctor() { }
}
```