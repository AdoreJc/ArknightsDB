# Act42D0EffectBottomView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Text _energyMaxPerfect`

- `Text _energy`

- `Text _energyMax`

- `GameObject _panelPerfect`

- `GameObject _panelElse`

- `Text _rating`

- `GameObject _panelNormal`

- `GameObject _panelHard`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Int32 m_cachedSequenceNum`


## Methods

- `Void _InitIfNot()`

- `Void Render(Act42D0EffectViewModel)`

- `Void OnCloseEffect()`

- `Void OnStartBattle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EffectBottomView : MonoBehaviour, IHotfixable
{
	private Text _energyMaxPerfect; // 0x18
	private Text _energy; // 0x20
	private Text _energyMax; // 0x28
	private GameObject _panelPerfect; // 0x30
	private GameObject _panelElse; // 0x38
	private Text _rating; // 0x40
	private GameObject _panelNormal; // 0x48
	private GameObject _panelHard; // 0x50
	private List`1 _canvasGroups; // 0x58
	private Boolean m_isInited; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private List`1 m_fadeSwitchTweens; // 0x78
	private Int32 m_cachedSequenceNum; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnCloseEffect; // 0x10
	private static DelegateBridge __Hotfix0_OnStartBattle; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x320b040 VA: 0x7595823040
	private Void _InitIfNot() { }
	// RVA: 0x320b27c VA: 0x759582327c
	public Void Render(Act42D0EffectViewModel viewModel) { }
	// RVA: 0x320b588 VA: 0x7595823588
	public Void OnCloseEffect() { }
	// RVA: 0x320b648 VA: 0x7595823648
	public Void OnStartBattle() { }
	// RVA: 0x320b708 VA: 0x7595823708
	public Void .ctor() { }
}
```