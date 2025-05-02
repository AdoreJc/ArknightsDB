# Act36sideFoodHandbookTabItem

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `Act36sideFoodHandbookTabType _tabType`

- `TwoStateToggle _selectToggle`

- `GameObject _newPanel`

- `UIAnimationLocation _clickAnim`

- `UIPageFinder m_pageFinder`

- `Act36sideFoodHandbookTabType m_cachedSelectedType`

- `Tween m_clickAnimTween`


## Methods

- `Void Render(Act36sideFoodHandbookViewModel)`

- `Void OnSelectTab()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideFoodHandbookTabItem : MonoBehaviour, IHotfixable
{
	private Act36sideFoodHandbookTabType _tabType; // 0x18
	private TwoStateToggle _selectToggle; // 0x20
	private GameObject _newPanel; // 0x28
	private UIAnimationLocation _clickAnim; // 0x30
	private UIPageFinder m_pageFinder; // 0x40
	private Act36sideFoodHandbookTabType m_cachedSelectedType; // 0x50
	private Tween m_clickAnimTween; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__CheckHasNewByType; // 0x8
	private static DelegateBridge __Hotfix0_OnSelectTab; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3247cfc VA: 0x759585fcfc
	public Void Render(Act36sideFoodHandbookViewModel model) { }
	// RVA: 0x3247dcc VA: 0x759585fdcc
	private static Boolean _CheckHasNewByType(Act36sideFoodHandbookViewModel model, Act36sideFoodHandbookTabType tabType) { }
	// RVA: 0x3247e74 VA: 0x759585fe74
	public Void OnSelectTab() { }
	// RVA: 0x324803c VA: 0x759586003c
	public Void .ctor() { }
}
```