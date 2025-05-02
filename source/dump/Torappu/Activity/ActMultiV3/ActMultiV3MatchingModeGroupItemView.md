# ActMultiV3MatchingModeGroupItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Image _imgModeIcon`

- `Image _imgGlow`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(ActMultiV3QuickMatchModel, ActMultiV3MatchModeGroupModel)`

- `Void _UpdateDiffList(ActMultiV3QuickMatchModel, ActMultiV3MatchModeGroupModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MatchingModeGroupItemView : MonoBehaviour, IHotfixable
{
	private Image _imgModeIcon; // 0x18
	private Image _imgGlow; // 0x20
	private DiffItem[] _diffList; // 0x28
	private UIPageFinder m_pageFinder; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__UpdateDiffList; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3126148 VA: 0x759573e148
	public Void Render(ActMultiV3QuickMatchModel matchModel, ActMultiV3MatchModeGroupModel groupModel) { }
	// RVA: 0x31262e0 VA: 0x759573e2e0
	private Void _UpdateDiffList(ActMultiV3QuickMatchModel matchModel, ActMultiV3MatchModeGroupModel groupModel) { }
	// RVA: 0x3126430 VA: 0x759573e430
	public Void .ctor() { }
}
```