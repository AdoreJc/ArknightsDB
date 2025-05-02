# StageZoneSpecialStoryOnlyPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIBlurFloatPanel _floatPanel`

- `Image _imgPanel`

- `Text _stageCodeText`

- `Text _stageTitleText`

- `Text _stageDescText`

- `UIPageFinder m_pageFinder`

- `Action m_startHandler`


## Methods

- `Void Show(Param)`

- `Void Hide()`

- `Void OnStartButtonPressed()`

- `Void OnBackgroundPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneSpecialStoryOnlyPanel : MonoBehaviour, IHotfixable
{
	private UIBlurFloatPanel _floatPanel; // 0x18
	private Image _imgPanel; // 0x20
	private Text _stageCodeText; // 0x28
	private Text _stageTitleText; // 0x30
	private Text _stageDescText; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	private Action m_startHandler; // 0x50
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0_OnStartButtonPressed; // 0x10
	private static DelegateBridge __Hotfix0_OnBackgroundPressed; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f72a8c VA: 0x759558aa8c
	public Void Show(Param param) { }
	// RVA: 0x2f72ca8 VA: 0x759558aca8
	public Void Hide() { }
	// RVA: 0x2f72d1c VA: 0x759558ad1c
	public Void OnStartButtonPressed() { }
	// RVA: 0x2f72dac VA: 0x759558adac
	public Void OnBackgroundPressed() { }
	// RVA: 0x2f72e2c VA: 0x759558ae2c
	public Void .ctor() { }
}
```