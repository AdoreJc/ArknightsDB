# Act1VAutoChessHUDBasementView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _selfIcon`

- `Image _enemyIcon`

- `UIAnimationLocation _switchAnim`

- `Boolean m_isInited`

- `String m_selfIconId`

- `String m_enemyIconId`

- `UIPageFinder m_pageFinder`

- `Tween m_switchTween`

- `HUDSeqNumChecker m_stateChecker`

- `HUDSeqNumChecker m_campSwitchChecker`


## Methods

- `Void Render(Act1VAutoChessHUDViewModel)`

- `Void _PlaySwitchAnimIfNeeded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDBasementView : MonoBehaviour, IHotfixable
{
	private Image _selfIcon; // 0x18
	private Image _enemyIcon; // 0x20
	private UIAnimationLocation _switchAnim; // 0x28
	private Boolean m_isInited; // 0x38
	private String m_selfIconId; // 0x40
	private String m_enemyIconId; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private Tween m_switchTween; // 0x60
	private HUDSeqNumChecker m_stateChecker; // 0x68
	private HUDSeqNumChecker m_campSwitchChecker; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__PlaySwitchAnimIfNeeded; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x336ff94 VA: 0x7595987f94
	public Void Render(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x3370328 VA: 0x7595988328
	private Void _PlaySwitchAnimIfNeeded() { }
	// RVA: 0x337047c VA: 0x759598847c
	public Void .ctor() { }
}
```