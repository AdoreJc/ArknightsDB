# StageZoneHomeCrisisEntry

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Sprite _funcSprite`

- `Text _textPoint`

- `GameObject _panelNoRank`

- `ZoneHomeEntryCrisisV2Model m_viewModel`

- `UIPageFinder m_pageFinder`


## Methods

- `Sprite _LoadRankIcon(CrisisV2AppraiseType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeCrisisEntry : StageZoneHomeEntryItemPlugin
{
	private Sprite _funcSprite; // 0x30
	private Text _textPoint; // 0x38
	private GameObject _panelNoRank; // 0x40
	private ZoneHomeEntryCrisisV2Model m_viewModel; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private static DelegateBridge __Hotfix0_GetFuncIcon; // 0x0
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x8
	private static DelegateBridge __Hotfix0__LoadRankIcon; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2efad30 VA: 0x7595512d30
	protected override Sprite GetFuncIcon() { }
	// RVA: 0x2efad98 VA: 0x7595512d98
	protected override Void OnDataUpdated() { }
	// RVA: 0x2efaf34 VA: 0x7595512f34
	private Sprite _LoadRankIcon(CrisisV2AppraiseType rankType) { }
	// RVA: 0x2efb03c VA: 0x759551303c
	public Void .ctor() { }
}
```