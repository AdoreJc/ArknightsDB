# Act1VAutoChessHUDBattleButtonView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `UISwitchToggle _speedToggle`

- `UISwitchToggle _pauseToggle`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(Act1VAutoChessHUDViewModel)`

- `Void OnMenuClick()`

- `Void OnSpeedClick()`

- `Void OnPauseClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDBattleButtonView : MonoBehaviour, IHotfixable
{
	private UISwitchToggle _speedToggle; // 0x18
	private UISwitchToggle _pauseToggle; // 0x20
	private UIPageFinder m_pageFinder; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnMenuClick; // 0x8
	private static DelegateBridge __Hotfix0_OnSpeedClick; // 0x10
	private static DelegateBridge __Hotfix0_OnPauseClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x33705a4 VA: 0x75959885a4
	public Void Render(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x3370668 VA: 0x7595988668
	public Void OnMenuClick() { }
	// RVA: 0x337071c VA: 0x759598871c
	public Void OnSpeedClick() { }
	// RVA: 0x33707d0 VA: 0x75959887d0
	public Void OnPauseClick() { }
	// RVA: 0x3370884 VA: 0x7595988884
	public Void .ctor() { }
}
```